<script setup>
const webapp = window.Telegram.WebApp
if(webapp){
  webapp.ready()
  console.log("Telegram--start")
  console.log(webapp.initDataUnsafe.username)
  console.log("----end----")
}

const aaa= "aaa"

</script>

<template>
  <div>
    {{aaa}}

  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
