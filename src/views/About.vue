<template>
  <div class="about">
    <h1>This is an about page</h1>
    <button v-on:click="jump">JUMP!</button>
  </div>
</template>

<script>
export default {
  methods: {
    jump() {
        this.$router.push({ path: '/'});
    }
  }
}
</script>
