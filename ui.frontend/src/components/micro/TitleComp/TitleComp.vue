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
    TitleClass: {
      type: String,
      default: 'space-Mono'
    },
    TitleColor: {
      type: String,
      default: ''
    }
  }
}
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Space+Mono&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Inconsolata&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat&display=swap");

.space-mono {
    font-family: "Space Mono", monospace;
    font-size: 64px;
    line-height: 95px;
    font-weight: 700;
    margin-right: 25px;

    @media (max-width: 750px) {
      font-size: 48px;
      line-height: 60px;
      margin-right: 0px;
    }
}

.inconsolata {
    font-family: 'Inconsolata';
    font-size: 64px;
    line-height: 95px;
    font-weight: 700;
    margin-right: 25px;

    @media (max-width: 750px) {
      font-size: 48px;
      line-height: 60px;
      margin-right: 0px;
    }
}

.montserrat {
    font-family: 'Montserrat';
    font-size: 64px;
    line-height: 95px;
    font-weight: 700;
    margin-right: 25px;

    @media (max-width: 750px) {
      font-size: 48px;
      line-height: 60px;
      margin-right: 0px;
    }
}

</style>
