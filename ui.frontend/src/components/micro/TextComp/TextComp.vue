<template>
  <div>
    <p>{{msg}}</p>
  </div>
</template>

<script>
export default {
    name: 'TextComp',
    props: {
        msg: {
            type: String,
            default: 'The page you are looking for might be removed or is temporarily unavailable'
        }
    }
}
</script>

<style scooped>
@import url("https://fonts.googleapis.com/css2?family=Space+Mono&display=swap");

* {
    font-family: "Space Mono", monospace;
}

p {
    font-size: 24px;
    line-height: 36px;
    font-weight: 400;
    color: #4f4f4f;
}

</style>