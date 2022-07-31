<template>
  <div>
    <button>{{msgBtn}}</button>
  </div>
</template>

<script>
export default {
  name: 'ButtonComp',
  props: {
    msgBtn: {
      type: String,
      default: 'BACK TO HOMEPAGE'
    }
  }
}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Space+Mono&display=swap');

button{
    font-family: "Space Mono", monospace;
    width: 216px;
    height: 68px;
    background-color: #333333;
    font-size: 14px;
    color: #ffffff;
    font-weight: 700;
}
</style>
