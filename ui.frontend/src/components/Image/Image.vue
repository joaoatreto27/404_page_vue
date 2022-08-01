<template>
  <img :src="src" />
</template>

<script>
export default {
  name: 'Image',
  props: {
    src: {
      type: String,
      default: './assets/error404.png'
    }
  }
}
</script>

<style lang="scss" scoped>
img {
  display: flex;
  justify-content: center;
  width: 30vw;
  margin-top: 100px;
  margin-left: auto;
  margin-right: auto;

  @media (max-width: 750px ) {
    width: 60vw;
    margin-top: 50px;
  }
}
</style>
