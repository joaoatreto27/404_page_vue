<template>
  <header>
    {{text}}
  </header>
</template>

<script>
export default {
  name: 'HeaderComp',
  props: {
    text: {
      type: String,
      default: '404 NOT FOUND'
    }
  }
}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Inconsolata:wght@200&display=swap');

header{
    font-family: "Inconsolata", monospace;
    width: 100%;
    font-size: 24px;
    font-weight: 700;
    color: #333333;
}
</style>
