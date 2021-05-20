<template>
  <div class="feature-card">
    <img :src="imageSrc" alt="" class="card-img">
    <div class="card-body">
      <h1>{{cardHeader}}</h1>
      <p>{{cardParagraph}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "FeatureCard",
  props: {
    imageSrc: {
      type: String,
      required: true
    },
    cardHeader: {
      type: String,
      required: true
    },
    cardParagraph: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>

</style>