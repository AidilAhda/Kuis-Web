<template>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

  <div class="hello">
    <section class="home" id="home">
        <div class="max-width">
            <div class="home-content">
                <div class="text-1"> Hello,My Name is </div>
                <div class="text-2"> Aidil Ahda</div>
                <div class="text-3"> and I'm a <span>Student</span></div>
                <router-link to="/about">Download My CV</router-link> 
            </div>
        </div>
    </section>
  </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* home styling */ 
.home .max-width {
  margin: auto 0 auto 40px;
}

.home .home-content .text-1 {
  font-size: 27px;
}
.home .home-content {
  align-content: center;
  margin: 25px;
  width: 500px;
  height: 200px;
  
}

.home .home-content .text-2 {
  font-size: 75px;
  font-weight: 600;
  margin-left: -3px;
}

.home .home-content .text-3 {
  font-size: 40px;
  margin: 5px 0;
}

.home .home-content .text-3 span {
  color: rgb(252, 48, 252);
  font-weight: 500;
}

.home .home-content a {
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

.home .home-content a:hover {
  color: rgb(252, 48, 252);
  background: none;
}
</style>
