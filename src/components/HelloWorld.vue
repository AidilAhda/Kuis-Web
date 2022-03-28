<template>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

  <div class="hello">
    <div class="name">
      <div class="letter">
        <h4> <span>Hey</span>  this is my homepage, so I have to say something about myself. Sometimes it is hard to introduce yourself because you know yourself so well that you do not know where to start with. Let me give a try to see what kind of image you have about me through my self-description. I hope that my impression about myself and your impression about me are not so different. Here it goes</h4>

      </div>
    </div>
    <a href="../views/AboutView.vue"> Download My CV</a>
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
.letter{
  margin-top: 18%;
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
  display: inline-block;
  background-color: rgb(211, 19, 211);
  color: #fff;
  font-size: 25px;
  padding: 12px 36px;
  margin-top: 20px;
  border-radius: 6px;
  border: 2px solid rgb(211, 19, 211);
  transition: all 0.3s ease;
}
a:hover{
  color: rgb(252, 48, 252);
  background: none;
}
span{
 color: rgb(252, 48, 252);
  font-size: 34px;
}
</style>
