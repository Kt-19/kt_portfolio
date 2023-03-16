<script setup>
import Right_item from './Right_item.vue'
import InstagramIcon from './icons/Instagram.vue'
import GithubIcon from './icons/Github.vue'
import LinkedInIcon from './icons/LinkedIn.vue'
</script>

<template>
  <div class="container-fluid">
    <div class="row">
      <Right_item>
        <template #title>
          <a href="https://kblock-fyp.onrender.com/" target="_blank">My Projects</a>
        </template>
      </Right_item>
    </div>
    <div class="row">
      <Right_item>
        <template #title>
          <a href="./assets/kt_resume.pdf" download>About Me</a>
        </template>
      </Right_item>
    </div>
    <div class="row">
      <Right_item>
        <template #title>
            <a href="#" target="_blank">Notes</a>
        </template>
      </Right_item>
    </div>
    <div class="social">
      <a href="https://www.instagram.com/kean.toh/"><InstagramIcon /></a>
      <a href="https://github.com/Kt-19"><GithubIcon /></a>
      <a href="https://www.linkedin.com/in/keantoh/"><LinkedInIcon /></a>
    </div>
  </div>
</template>


<style scoped>
.container-fluid{
  text-align: center;
}
.social{
  padding: 2rem 0 0.5rem 0;
}
.social a{
  margin: 0 1.5rem;
}
.row a {
  background: linear-gradient(#6AABD2 0 0) calc(100% - var(--p,0%)) / var(--p,0%) no-repeat;
  transition: .5s, background-position 0s;
  padding: 0 2rem;
}
.row a:hover {
  --p: 100%;
  background-color: #D9E4EC;
}
</style>