<template>
<footer>
    <p>created by <div class="username">{{username}}</div> - devChallenges.io</p>
</footer>  
</template>

<script>
export default {
    name: 'FooterComp',
    props:{
        username:{
            type: String,
            default: joaoatreto27
        }
    }
}
</script>

<style scooped>

@import url("https://fonts.googleapis.com/css2?family=Montserrat&display=swap");

*{
    font-family: "Montserrat", sans-serif;
}

footer {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;

}

p {
    font-size: 14px;
    color: #bdbdbd;
}

div {
    font-weight: bold;
}
</style>