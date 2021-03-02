<template>
    <div class="SideBar">
        <lu>
            <li><a href="#">Projects</a></li>
        </lu>
    </div>
</template>

<script>
export default {
  name: 'SideBar',
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
.SideBar{
    width: 160px;
    height:100%;
    position: fixed;
    z-index: 1;
    left:0;
    top:0;
    padding-top: 20px;
    overflow-x:hidden;
    background-color: green;

}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 25%;
  background-color: #f1f1f1;
  height: 100%; /* Full height */
  position: fixed; /* Make it stick, even on scroll */
  overflow: auto; /* Enable scrolling if the sidenav has too much content */
}
li{
    list-style-type: none;
}
li a {
  display: block;
  color: #429bf5;
  padding: 8px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #555;
  color: white;
}
</style>
