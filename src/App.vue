<script setup>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";
import Jumbotron from "./components/Jumbotron.vue";
import Tabs from "./components/Tabs.vue";
if (
  localStorage.getItem("color-theme") === "dark" ||
  (!("color-theme" in localStorage) && window.matchMedia("(prefers-color-scheme: dark)").matches)
) {
  document.documentElement.classList.add("dark");
} else {
  document.documentElement.classList.remove("dark");
}
</script>

<template>
  <div>
    <Navbar />
  </div>

  <div>
    <Jumbotron />
  </div>
  
  <div>
    <Tabs/>
  </div>
  <div>
    <Footer></Footer>
  </div>
</template>

<style></style>
