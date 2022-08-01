<template>
    <div>
        <h1 :class="TitleClass" :style="{ 'color': TitleColor}">{{TitleText}}</h1>
    </div>
</template>

<script>
export default {
  name: 'TitleComp',
  props: {
    TitleText: {
      type: String,
      default: 'I have bad news for you'
    },
    
  }
}
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Space+Mono&display=swap");

h1 {
    font-family: "Space Mono", monospace;
    font-size: 64px;
    line-height: 95px;
    color: #333333;
    font-weight: 700;
    margin-right: 25px;

    @media (max-width: 750px) {
      font-size: 48px;
      line-height: 60px;
      margin-right: 0px;
    }
}
</style>
