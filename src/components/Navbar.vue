<template>
  <nav class="navbar">
    <div class="container">
      <div class="logo">
        <a href="#"><span class="span-logo">UIX</span>withme</a>
      </div>
      <div class="navigation-link">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
      </div>
      <div class="navigation-button">
        <button class="view-portfolio"><a href="#">View Portfolio</a></button>
      </div>
    </div>
  </nav>
</template>

<script setup></script>

<style>
* {
  padding: 0;
  margin: 0;
}

.navbar {
  height: 90px;
  background-color: rgb(255, 255, 255);
  display: flex;
  justify-content: center;
  align-items: center;
  position: sticky;
  top: 0;
  box-shadow: 0 0 8px 0 rgba(139, 139, 139, 0.774);
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.container ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.container li {
  padding: 0 30px;
}

.logo {
  padding-right: 120px;
}

.logo .span-logo {
  font-weight: bold;
  font-size: 2.2rem;
}

.logo a {
  font-size: 2rem;
  list-style: none;
  color: black;
  text-decoration: none;
}

.navigation-link a {
  font-size: 1.2rem;
}

.navigation-link ul {
  list-style-type: none;
}

.navigation-link a {
  text-decoration: none;
  color: rgb(77, 77, 77);
  font-weight: bolder;
  transition-duration: 0.2s;
}

.navigation-link a:hover {
  color: orangered;
}

.navigation-button {
  padding-left: 120px;
}

.view-portfolio a{
  text-decoration: none;
  color: white;

}
.view-portfolio {
  background-color: #8d99ae;
  color: white;
  border: none;
  border-radius: 4px;
  padding: 15px 40px;
  font-size: 1.2rem;
  cursor: pointer;
}

.view-portfolio:hover {
  background-color: #616772;
}
</style>
