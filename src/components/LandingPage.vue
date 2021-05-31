<template>
  <div>
    <div class="nav-bar">
      <div class="container">
        <div class="logo"><a href="#">Brakly</a></div>
        <nav>
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Service</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Why us?</a></li>
            <li><a href="#">Download</a></li>
          </ul>
        </nav>
      </div>
    </div>
    <section class="hero">
      <div class="container">
        <div class="left-col">
          <h1>Turning banking<br/>on its head.</h1>
          <p>We'll nail your next project, because nobody
            wants a screw up!</p>
          <a class="hero-button">Learn More</a>
        </div>
        <div class="right-col">
          <div class="user-dashboard">
            <img src="../assets/dashboard.png" alt="user-dashboard">
          </div>
        </div>
      </div>
    </section>
    <section class="wellness">
      <div class="container">
        <h1 class="title">Brakly Financial Wellness</h1>
        <div class="card">
          <FeatureCard :image-src="require('../assets/feature-card-img-1.svg')" card-header="Pay Bill"
                       card-paragraph="Banks are a very important part of the economy because they provide
                                    vital services for both consumers and businesses."/>
          <FeatureCard :image-src="require('../assets/feature-card-img-2.svg')" card-header="Easy to use"
                       card-paragraph="The goal of a bank is to earn profit
                                      for its owners. For most banks, the
                                      owners are their shareholders."/>
          <FeatureCard :image-src="require('../assets/feature-card-img-3.svg')" card-header="Save your card"
                       card-paragraph="This number includes national banks,
                                    state-chartered banks, commercial banks."/>
        </div>
      </div>
    </section>
    <section class="personal">
      <div class="container">
        <div class="left-col">
          <img src="../assets/recent-report.png" alt="recent-report">
        </div>
        <div class="right-col">
          <h1>Personal Internet Banking</h1>
          <p>Banks also provide credit opportunities for people
            and corporations. The money you deposit at the
            bank short-term cash is used to lend to others
            for long-term debt such as car loans, credit cards,
            mortgages, and other debt vehicles. </p>
          <a href="#">Learn more</a>
        </div>
      </div>
    </section>
    <section class="international">
      <div class="container">
        <div class="left-col">
          <h1>International Banking</h1>
          <p>The money you deposit at the bank short-term cash is
            used to lend to others for long-term debt such as car
            loans, credit cards, mortgages, and other debt vehicles.
          </p>
          <div class="feature-list">
            <ul>
              <li>Quick Account Opening</li>
              <li>Get Your Pay Easily</li>
              <li>Free Checking</li>
              <li>Higher Interest Rates</li>
            </ul>
          </div>
        </div>
        <div class="right-col">
          <img src="../assets/happy-couple.png" alt="happy-couple">
        </div>
      </div>
    </section>
    <section class="download">
      <div class="container">
        <img src="../assets/download-app.svg" alt="app-download">
      </div>
    </section>
    <section class="clients">
      <div class="container">
        <h1>What our Client Say?</h1>
        <div class="card">
          <ClientCard  client-name="John Alex" :image-src="require('../assets/client-img1.svg')"
                       client-quote="When it comes to booking a holiday, we know
                                    everyone likes something different - so we've
                                    designed our getaways with you in mind."/>
          <ClientCard  client-name="john Reb" :image-src="require('../assets/client-img2.svg')"
                       client-quote="When it comes to booking a holiday, we know
                                    everyone likes something different - so we've
                                    designed our getaways with you in mind."/>
          <ClientCard  client-name="john Alex" :image-src="require('../assets/client-img3.svg')"
                       client-quote="When it comes to booking a holiday, we know
                                    everyone likes something different - so we've
                                    designed our getaways with you in mind."/>
        </div>
      </div>
    </section>
    <footer>
      <div class="container">
        <div class="footer-item">
          <h6>Quick Links</h6>
          <ul>
            <li>Home</li>
            <li>About Us</li>
            <li>Services</li>
            <li>Products</li>
          </ul>
        </div>
        <div class="footer-item">
          <h6>Customer Care</h6>
          <ul>
            <li>Help center</li>
            <li>Support</li>
            <li>Faq</li>
            <li>Social</li>
          </ul>
        </div>
        <div class="footer-item">
          <h6>Contact Us</h6>
          <ul>
            <li>Sylhet,Bangladesh.</li>
            <li>himelsunnath66@gmail.com</li>
            <li>+8801633187369</li>
          </ul>
        </div>
        <div class="footer-item">
          <p>The money you deposit at the bank short-term
            cash is used to lend to others for long-term
            debt such as car loans.</p>
          <div class="social">
            <img src="../assets/facebook.svg" alt="facebook">
            <img src="../assets/twitter.svg" alt="twitter">
            <img src="../assets/youtube.svg" alt="youtube">
            <img src="../assets/linkedin.svg" alt="linkedin">
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import FeatureCard from "@/components/FeatureCard";
import ClientCard from "@/components/ClientCard";
export default {
  name: "LandingPage",
  components: {ClientCard, FeatureCard},
}
</script>

<style scoped>
</style>