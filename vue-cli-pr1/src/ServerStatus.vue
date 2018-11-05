<template>
  <div>
    <p>Server Status: {{ status }}</p>
    <hr>
    <button type="button" name="button" @click="changeStatus">Change Status</button>
  </div>
</template>

<script>
  export default {
    data: function() {
      return {
        status: 'Not normal'
      }
    },
    methods: {
      changeStatus() {
        this.status = 'Normal'
      }
    }
  }
</script>
