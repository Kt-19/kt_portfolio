<script setup>
// defineProps({
//   msg: {
//     type: String,
//     required: true
//   }
// })
</script>

<template>
  <div class="greetings">
    <h1 class>Leong Kean Toh - 梁健涛</h1>
    <h2>
      I'm a fresh graduate who is looking to gain experience in software field.
    </h2>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.5rem;
}

h2 {
  font-size: 1.3rem;
  font-family: serif;
}

a{
  color: #385E72;
}
.greetings h1,
.greetings h3 {
  text-align: center;
}

/* @media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
} */
</style>
