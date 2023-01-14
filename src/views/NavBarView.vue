<template>
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/resume">Resume</router-link> |
      <router-link to="/projects">Projects</router-link> |
      <router-link to="/testimonials">Testimonials</router-link> |
      <router-link to="/contact">Contact</router-link>
    </nav>
    <NavBar/>
    <router-view/>
  </template>

  <script>
  import NavBar from './components/NavBar.vue'
  export default {
      components: {
        NavBar
      }
  }
  </script>
  <style>
  nav{
    display: flex;
  }
  </style>