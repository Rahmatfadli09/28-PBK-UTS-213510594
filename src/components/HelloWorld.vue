<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="black">{{ msg }}</h1>
    <h3>
      <a href="https://instagram.com/rmt.fadli?igshid=ZGUzMzM3NWJiOQ==" target="_blank" rel="noopener"><img src="@/assets/ig.jpeg" alt=""></a> +
      <a href="https://github.com/Rahmatfadli09/28-PBK-UTS-213510594/" target="_blank" rel="noopener"><img src="@/assets/github.png" alt=""></a>
    </h3>
  </div>
</template>

<style scoped>
img {
  width: 8%;
  border: 2px solid black;
  border-radius: 50%;
  
}
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
  color: black;
}

h3 a {
  font-size: 1.2rem;
  color: black;
  
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
