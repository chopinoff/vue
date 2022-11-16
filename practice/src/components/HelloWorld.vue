<template>
  <div class="hello">
    <div class="top"></div>
    <div class="wrap">
      <div class="left"></div>
      <button>하잉</button>
      <div class="right"></div>
      <div class="bottom"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
button {
  width: 10%;
  height: 50px;
  font-size: 20px;
  font-weight: 900;
}
.top {
  /* background-color: blueviolet; */
  height: 200px;
}
.wrap {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
.left {
  width: 20%;
}
.right {
  width: 20%;
}
.bottom {
  width: 100%;
  height: 200px;
  padding-top: 200px;
}
.top:hover {
  margin-bottom: 100px;
}
.left:hover {
  margin-right: 20%;
}
.right:hover {
  margin-left: 20%;
}
.bottom:hover {
  margin-top: 0px;
}
button:hover {
  transform: translateY(200px);
}
.wrap:hover {
  padding-top: 300px;
}
</style>
