<template>
  <div>
    <button :style="{'color': TextColor, 'font-family': FontBtn, 'background-color' : BtnColor }">{{msgBtn}}</button>
  </div>
</template>

<script>
export default {
  name: 'ButtonComp',
  props: {
    msgBtn: {
      type: String,
      default: 'BACK TO HOMEPAGE'
    },
    TextColor: {
      type: String,
      default: '#ffffff'
    },
    FontBtn: {
      type: String,
      default: 'space-mono'
    },
    BtnColor: {
      type: String,
      default: '#333333'
    }
  }
}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Space+Mono&display=swap');
@import url("https://fonts.googleapis.com/css2?family=Inconsolata&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat&display=swap");

button{
    font-family: "Space Mono", monospace;
    width: 216px;
    height: 68px;
    background-color: #333333;
    font-size: 14px;
    color: #ffffff;
    font-weight: 700;
    margin-top: 50px;
    border: none;

    @media (max-width: 415px) {
      margin-top: 50px;
    }

    @media (max-width: 395px) {
      margin-top: 25px;
    }
}
</style>
