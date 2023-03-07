<script setup lang="ts">
const menus = [
  {
    text: "Home",
    to: "/",
  },
  {
    text: "About",
    to: "/about",
  },
  {
    text: "Experience",
    to: "/experience",
  },
  {
    text: "Education",
    to: "/education"
  },
  {
    text: "Project",
    to: "/project",
    class: "hover:text-sky-700 font-bold"
  }
];
</script>

<style>
nav {
  gap: 10px;
}
</style>

<template>
  <VNavbar :menus="menus" class="bg-blue-200"></VNavbar>
</template>
