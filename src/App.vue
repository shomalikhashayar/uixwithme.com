<template>
  <Navbar />
  <div class="hero-section">
    <div class="hero-section-content">
      <h1>An excellent center for UI/UX Design Learning</h1>
      <p>
        UIXwithme is online learning platform that offers various courses for
        Design Development.
      </p>
      <p>If you wana learn Design like a pro, Subscribe our Newsletter.</p>
    </div>
    <div class="hero-section-image">
      <img src="../src/assets/uixwithme-hierarchy.webp" alt="uixwithme" />
      <div class="hero-section-image-buttons">
        <button class="learn-design-for-free">
          <a href="">Learn Design For Free</a>
        </button>
        <button class="subscribe-newsletter">
          <a href="">subscribe Newsletter</a>
        </button>
      </div>
    </div>
  </div>
</template>

<script setup>
import Navbar from "./components/Navbar.vue";
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Rubik&display=swap");

* {
  font-family: "Rubik", sans-serif;
}

.hero-section {
  height: 550px;
  background: rgb(2, 0, 36);
  background: -moz-linear-gradient(
    66deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(141, 153, 174, 1) 0%,
    rgb(185, 191, 201) 0%,
    rgba(97, 103, 114, 1) 100%
  );
  background: -webkit-linear-gradient(
    66deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(141, 153, 174, 1) 0%,
    rgba(141, 153, 174, 1) 0%,
    rgba(97, 103, 114, 1) 100%
  );
  background: linear-gradient(
    66deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(141, 153, 174, 1) 0%,
    rgba(141, 153, 174, 1) 0%,
    rgba(97, 103, 114, 1) 100%
  );
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#020024",endColorstr="#616772",GradientType=1);
  display: flex;
  justify-content: center;
  padding-top: 50px;
}

.hero-section-image img {
  width: 300px;
  height: auto;
  padding-left: 25px;
}

.hero-section-content {
  padding-right: 150px;
  padding-top: 20px;
}

.hero-section-content h1 {
  font-size: 3rem;
  width: 550px;
  font-weight: bolder;
  line-height: 75px;
  margin-bottom: 50px;
}

.hero-section-content p {
  font-size: 1.5rem;
  width: 600px;
  font-weight: 600;
  line-height: 40px;
  margin-bottom: 35px;
}

.hero-section-image-buttons {
  display: flex;
  flex-direction: column;
}

.hero-section-image-buttons button {
  margin: 10px 0;
  padding: 20px 80px;
}

.learn-design-for-free {
  background-color: white;
  border: none;
  border-radius: 9px;
  padding: 20px 40px;
  font-size: 1.2rem;
  font-weight: bolder;
}
.learn-design-for-free a {
  text-decoration: none;
  color: orangered;
}

.subscribe-newsletter {
  background-color: transparent;
  border: dashed;
  border-color: white;
  border-radius: 9px;
  padding: 20px 40px;
  font-size: 1.2rem;
  font-weight: bolder;
}

.subscribe-newsletter a {
  text-decoration: none;
  color: white;
}
</style>
