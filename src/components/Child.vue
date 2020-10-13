<template>
  <div id="child">
    <slot :on="onListener" name="child"></slot>
  </div>
</template>

<script>
export default {
  name: 'Child',
  methods: {
    onListener() {
      alert('You clicked')
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
