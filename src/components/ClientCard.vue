<template>
  <div class="client-card">
    <img :src="imageSrc" alt="" class="client-img">
    <div class="card-body">
      <h5>{{clientName}}</h5>
      <img src="" alt="" class="ratings">
      <blockquote>{{clientQuote}}</blockquote>
    </div>
  </div>
</template>

<script>
export default {
  name: "ClientCard",
  props: {
    imageSrc: {
      type: String,
      required: true
    },
    clientName: {
      type: String,
      required: true
    },
    clientQuote: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>

</style>