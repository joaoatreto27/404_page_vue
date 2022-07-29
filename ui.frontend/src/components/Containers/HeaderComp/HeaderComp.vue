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

<style scooped>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@200&display=swap');

* {
    font-family: "Inconsolata", monospace;
}

header{
    width: 100%;
    font-size: 24px;
    font-weight: 700;
    color: #333333;
}
</style>
