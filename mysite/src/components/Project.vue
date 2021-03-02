<template>
    <li>
        <div class="Project-block">
            <h1>{{ title }}</h1>
            <img :alt=alt :src=pic class="projectpic" align="left">
            <p>{{info}}</p>
        </div>
    </li>
</template>

<script>
export default {
  name: 'Project',
  props: {
      alt:String,
      title: String,
      pic:String,
      info:String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img.projectpic{
    max-width: 25%;
    padding-inline: 40px;
}
h3 {
    text-align: left;
    margin: 40px 0 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
h1{
    text-align: left;
    margin: 40px 60px 10px;
    color:white;
}
a {
  color:white;
}
p{
    margin: 40px;
    text-align: left;
    color:#429bf5;
}
.Project-block{
    margin-right:200px;
}
@media screen and (max-width: 600px){
    .Project-block{
        margin-right:10px;
    }

    img.projectpic{
        max-width: 75%;
        align-content: center;
    }
}
</style>
