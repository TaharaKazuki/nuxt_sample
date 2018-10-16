<template>
  <div>
    <input type="text" v-model="userId">
    <button @click="movePath">Click</button>
    <nuxt-child />
  </div>
</template>
<script>

  export default {
    data() {
      return {
        userId: ''
      }
    },
    methods: {
      movePath() {
        this.$router.push(`/users/${this.userId}`)
      }
    }
  }

</script>
