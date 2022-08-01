<template>
  <header :class="HeaderClass" :style="{'color': HeaderColor}">
    {{TextHeader}}
  </header>
</template>

<script>
export default {
  name: 'HeaderComp',
  props: {
    TextHeader: {
      type: String,
      default: '404 NOT FOUND'
    },
    HeaderClass: {
      type: String,
      default: 'inconsolata'
    },
    HeaderColor: {
      type: String,
      default: '#333333'
    }
  }
}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Inconsolata:wght@200&display=swap');

.inconsolata{
    font-family: "Inconsolata", monospace;
    width: 100%;
    font-size: 24px;
    font-weight: 700;
}

.space-mono{
  font-family: "Space Mono", monospace;
  width: 100%;
  font-size: 24px;
  font-weight: 700;
}

.montserrat{
  font-family: "Montserrat";
  width: 100%;
  font-size: 24px;
  font-weight: 700;
}
</style>
