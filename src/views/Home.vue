<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">


    <h1>Hola mundo</h1>

    <button @click="goTo" class="btn btn-primary" >Primary</button>
    <button @click="goTo" class="btn btn-secondary">Secondary</button>
    <button @click="goTo" class="btn btn-success">Success</button>
  </div>
</template>
<script>
export default {
  methods: {
    goTo () {
      this.$router.push({name: 'no-entry'})
    }
  }
}
</script>
