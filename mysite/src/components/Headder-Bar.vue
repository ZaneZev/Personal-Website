<template>
    <div class="bar">
        <span class="leftbit">Hello There</span>
        <img src="https://media-exp1.licdn.com/dms/image/C5603AQGGnxriDUa-XQ/profile-displayphoto-shrink_200_200/0/1517852449485?e=1620259200&v=beta&t=cKZWGhlFI8A_JvcTY9KUOQvc7hv_ey6eULkjyql_Q2U"/>
        <span class="rightside">I am Zane Young, majoring in mechanical engineering at WSU and a hobbiest electronics designer, robotics designer, and programmer.</span>
    </div>
</template>

<script>
export default {
  name: 'HeadderBar',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.bar{
    background-color: rgb(53, 53, 53);
    width: 100%;
    height : 100px;
    top:0;
    display: block;
}
span{
    font-size: medium;
    margin-left:10px;
    margin-right: 10px;
    vertical-align: text-top;
    background-color: inherit;
    color:lightgray;
}
.leftbit{
    margin-left:calc(160px + 10px);
}
img{
    max-height: 100px;
    vertical-align: middle;
}
@media screen and (max-width: 600px){
    .leftbit{
        margin-left: 50px;
    }
    .rightside{
        margin: 10px 25px 10px 25px;
        position: relative;
        display: inline-block;

    }
    .bar{
        height: fit-content;
    }
}
</style>
