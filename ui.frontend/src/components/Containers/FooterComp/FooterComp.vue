<template>
<footer>
    <p>created by {{username}} - devChallenges.io</p>
</footer>
</template>

<script>
export default {
  name: 'FooterComp',
  props: {
    username: {
      type: String,
      default: 'joaoatreto27'
    }
  }
}
</script>

<style lang="scss" scoped>

@import url("https://fonts.googleapis.com/css2?family=Montserrat&display=swap");

footer {
    font-family: "Montserrat", sans-serif;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 308px;
}

p {
    font-size: 14px;
    color: #bdbdbd;
}

</style>
