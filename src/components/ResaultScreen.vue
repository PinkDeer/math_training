<template>
  <div class="alert alert-primary">
    <h3>Success: {{ stats.success }}</h3>
    <h3>Error: {{ stats.error }}</h3>
    <hr>
    <button class="btn btn primary" @click="$emit('repeat')">Reapet</button>
    <button class="btn btn primary" @click="$emit('nextLevel')">Next level</button>
  </div>
</template>

<script>
  export default {
    props: ['stats']
  }
</script>

<style>

</style>
