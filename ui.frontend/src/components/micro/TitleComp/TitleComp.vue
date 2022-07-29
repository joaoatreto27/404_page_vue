<template>
    <div>
        <h1>{{TitleText}}</h1>
    </div>
</template>

<script>
export default {
    name: 'TitleComp',
    props: {
        TitleText: {
            type: String,
            default: 'I have bad news for you' 
        }
    }
}
</script>

<style scooped>
@import url("https://fonts.googleapis.com/css2?family=Space+Mono&display=swap");

* {
    font-family: "Space Mono", monospace;
}

h1 {
    font-size: 64px;
    line-height: 95px;
    color: #333333;
    font-weight: 700;
}
</style>