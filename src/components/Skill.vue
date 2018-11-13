
<template>
  <div class="output">
    <div class="content">
    <h3> {{ name }} </h3>
    <p> {{ text }} </p>
  </div>
  <div class="content2">
    <h3> {{ name1 }} </h3>
    <p> {{ text1 }} </p>
  </div>
  <div class="content3">
    <h3> {{ name2 }} </h3>
    <p> {{ text2 }} </p>
  </div>
  </div>
</template>

<script>
export default {
  name: 'skill',
  data () {
    return {
        name: "英語力",
        text: "TOEIC810点",
        name1:"プログラミング",
        text1:"Node.js,Vue.js",
        name2:"WEBサイト運営",
        text2:"3万PV/月"
    }
  }
}
</script>

<style scoped>

div.skill {
  text-align: center;
}

div.content {
  background-color: #eee;
  display: inline-block;
  margin: 10px;
  width: 30%;
}
div.content2 {
  background-color: #eee;
  display: inline-block;
  margin: 10px;
  width: 30%;
}
div.content3 {
  background-color: #eee;
  display: inline-block;
  margin: 10px;
  width: 30%;
}

h3 {
  color: rgb(50, 58, 58);
}

p {
  width: 90%;
  padding-left: 10em;
  display: inline-block;
  text-align: left;
  color:blue
}

</style>