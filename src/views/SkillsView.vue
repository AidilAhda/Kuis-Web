<template>
   <section class="skills"> 
        <div class="max-width">
      <h2 class="title">My Skills</h2>
      <div class="skills-content">
          <div class="column left">
              <div class="text">My Creative Skills</div>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto sunt, odit ex dolorum distinctio at reiciendis ipsam perspiciatis facilis ipsum dolores eius saepe fuga vitae quae odio. Fugiat, doloremque architecto?</p>
          </div>
          <div class="column right">
              <div class="bars">
                  <div class="info">
                      <span>Java</span>
                      <span>45%</span>
                  </div>
                  <div class="line java"></div>
              </div>
              <div class="bars">
                  <div class="info">
                      <span>My SQL</span>
                      <span>45%</span>
                  </div>
                  <div class="line sql"></div>
              </div>
          </div>
      
      </div>
     </div>
   </section>
   
</template>


<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  
}
section {
  padding: 100px, 0; 
}
.skills {
  font-family: sans-serif;
  
}
.skills .skills-content{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  
}
.skills .title {
  text-align: center;
  font-size: 40px;
  font-weight: 500;
  margin-bottom: 60px;
  padding-bottom: 20px;
  font-family: sans-serif;
}
.skills .skills-content .column{
    width: calc(50% - 30px);
    margin-left: 20%;
}
.skills .skills-content .left .text{
    font-size: 25px;
    font-weight: 600;
    margin-bottom: 10px;
}
.skills .skills-content .right .bars{
    margin: 15px;
}
.skills .skills-content .right span{
    font-weight: 500;
    font-size: 18px;
}
.skills .skills-content .right .info{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.skills .skills-content .right .line{
   height: 5px;
   width: 100%;
   
   position: relative;
}
.skills .skills-content .right .line::before {
   content: "";
   position: absolute;
   height: 100%;
   width: 45%;
   left: 0;
   top: 0;
   background: rgb(255, 0, 242);


}
</style>