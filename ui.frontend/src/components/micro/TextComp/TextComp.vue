<template>
  <div>
    <p :class="TextClass" :style="{'color': TextColor}">{{msg}}</p>
  </div>
</template>

<script>
export default {
  name: 'TextComp',
  props: {
    msg: {
      type: String,
      default: 'The page you are looking for might be removed or is temporarily unavailable'
    },
    TextClass: {
      type: String,
      default: 'space-mono'
    },
    TextColor: {
      type: String,
      default: '#4f4f4f'
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
    font-size: 24px;
    line-height: 36px;
    font-weight: 400;
    margin-right: 25px;
    width: 381px;

    @media (max-width: 750px) {
      font-size: 18px;
      margin-right: 0px;
    }

    @media (max-width: 415px) {
      margin-top: 50px;
    }

    @media (max-width: 395px) {
      margin-top: 25px;
    }
}
.inconsolata {
    font-family: 'Inconsolata';
    font-size: 24px;
    line-height: 36px;
    font-weight: 400;
    margin-right: 25px;
    width: 381px;

    @media (max-width: 750px) {
      font-size: 18px;
      margin-right: 0px;
    }

    @media (max-width: 415px) {
      margin-top: 50px;
    }

    @media (max-width: 395px) {
      margin-top: 25px;
    }
}
.montserrat {
    font-family: 'Montserrat';
    font-size: 24px;
    line-height: 36px;
    font-weight: 400;
    margin-right: 25px;
    width: 381px;

    @media (max-width: 750px) {
      font-size: 18px;
      margin-right: 0px;
    }

    @media (max-width: 415px) {
      margin-top: 50px;
    }

    @media (max-width: 395px) {
      margin-top: 25px;
    }

}

</style>
