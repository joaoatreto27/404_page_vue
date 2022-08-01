<template>
<footer>
    <p>created by <span>{{username}}</span> - devChallenges.io</p>
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
    margin-top: 80px;

    @media (max-width: 415px) {
      margin-top: 125px;
    }

    @media (max-width: 395px) {
      margin-top: 85px;
    }
}

p {
    font-size: 14px;
    color: #bdbdbd;

    span {
      font-weight: bold;
      border-bottom: 1px;
    }
}

</style>
