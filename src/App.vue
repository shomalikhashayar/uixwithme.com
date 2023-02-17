<template>
  <Navbar />
  <div class="hero-section">
    <div class="hero-section-content">
      <h1>An excellent center for UI/UX Design Learning</h1>
      <p id="second">
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
  <div class="who-we-are-section">
    <div class="who-we-are-section-image">
      <img src="../src/assets/Question-Mark.webp" alt="Question?" />
    </div>
    <div class="who-we-are-section-content">
      <h2>Who We Are?</h2>
      <p>
        We are two professional software engineering students from IRAN, named
        <span>Khashayar Shomali</span> and
        <span>Mohammad Hossein Khan Mohammadi</span>, who intend to help others
        interested in the field of <span>UI/UX Design</span> by presenting our
        learnings for <span>free</span>.
      </p>
    </div>
  </div>
  <div class="our-services-section">
    <div class="our-services-section-image">
      <img
        src="../src/assets/Portfolio-Khashayar-Shomali.png"
        alt="Portfolio"
      />
    </div>
    <div class="our-services-section-content">
      <h2>Good Design is All You Need!</h2>
      <p>
        We help businesses to convert their ideas into successful mobile
        applications and websites through strategy, creativity and technology.
      </p>
      <div class="our-services-section-buttons">
        <button class="view-our-services-button">
          <span><a href="#">View Our Services</a></span>
          <span
            ><a href="#"
              ><svg
                style="color: white"
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                fill="currentColor"
                class="bi bi-arrow-right-circle"
                viewBox="0 0 16 16"
              >
                <path
                  fill-rule="evenodd"
                  d="M1 8a7 7 0 1 0 14 0A7 7 0 0 0 1 8zm15 0A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM4.5 7.5a.5.5 0 0 0 0 1h5.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.708.708L10.293 7.5H4.5z"
                  fill="white"
                ></path></svg></a
          ></span>
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

/* Hero Section */
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

.hero-section-content #second {
  color: rgba(255, 255, 255, 0.644);
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

/* Who We Are? */

.who-we-are-section {
  height: 600px;
  background-color: white;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 50px;
  padding: 0 90px;
}

.who-we-are-section-image img {
  width: 350px;
  height: auto;
  box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.3);
  border-radius: 9px;
}

.who-we-are-section-content h2 {
  font-size: 3.5rem;
  font-weight: bold;
}

.who-we-are-section-content p {
  font-size: 24px;
  margin-top: 10px;
  line-height: 1.7em;
}

.who-we-are-section-content span {
  font-weight: bold;
}

/* Good Design is All You Need */

.our-services-section {
  height: 600px;
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
  align-items: center;
  gap: 70px;
}

.our-services-section-image img {
  width: 550px;
  height: auto;
  display: flex;
  border-radius: 9px;
  justify-content: space-between;
  align-items: center;
}

.our-services-section-content {
  gap: 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 20px;
}

.our-services-section-content h2 {
  font-weight: bold;
  font-size: 3.5rem;
  line-height: 70px;
  margin-bottom: 10px;
  max-width: 400px;
}

.our-services-section-content p {
  background-color: white;
  font-size: 22px;
  line-height: 30px;
  max-width: 467px;
  margin-bottom: 40px;
}

.view-our-services-button {
  background-color: transparent;
  border: 2.5px white solid;
  border-radius: 50px;
  border-color: white;
  font-size: 14px;
  cursor: pointer;
  width: 180px;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.our-services-section-buttons button {
  padding: 5px 10px;
  margin-bottom: 10px;
}

.view-our-services-button:hover {
  background-color: orangered;
}

.view-our-services-button a {
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none;
  color: white;
}

.view-our-services-button svg {
  padding-left: 10px;
}

</style>
