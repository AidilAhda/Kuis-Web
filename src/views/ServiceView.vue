<template>
  <section class="service" >
    <div class="max-width">
      <h2 class="title">My Academic</h2>
      <div class="serv-content">
          <div class="card">
              <div class="box">
                  <i class="fa-solid fa-graduation-cap"></i>
                  <div class="text">SDN 002 LANGGINI BANGKINANG KOTA</div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Earum beatae temporibus eligendi, perferendis numquam laboriosam!</p>
                  
              </div>
          </div>
          <div class="card">
              <div class="box">
                  <i class="fa-solid fa-graduation-cap"></i>
                  <div class="text">SMPN 1 BANGKINANG KOTA</div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Earum beatae temporibus eligendi, perferendis numquam laboriosam!</p>
              </div>
          </div>
          <div class="card">
              <div class="box">
                  <i class="fa-solid fa-graduation-cap"></i>
                  <div class="text">SMAN 1  BANGKINANG KOTA</div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Earum beatae temporibus eligendi, perferendis numquam laboriosam!</p>
              </div>
          </div>
          <div class="card">
              <div class="box">
                  <i class="fa-solid fa-graduation-cap"></i>
                  <div class="text">UIN SUSKA RIAU</div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Earum beatae temporibus eligendi, perferendis numquam laboriosam!</p>
              </div>
          </div>
      </div>
     </div>
  </section>
   <footer>
    <hr />
    <p class="footer"><i class="fa-solid fa-copyright"></i>Copyright2022,Aidil Ahda</p>
  </footer>
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
.service {
  font-family: sans-serif;
  
}
.service .title {
  text-align: center;
  font-size: 40px;
  font-weight: 500;
  margin-bottom: 60px;
  padding-bottom: 20px;
  font-family: sans-serif;
}
.service.title ::before {
  content: "";
  position: absolute;
  width: 180px;
  height: 3px;
  background: #1111;
}
.service .serv-content{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    
}
.service .serv-content .card{
   width: calc(33% - 20px);
   background: rgb(252, 215, 252);
   text-align: center;
   border-radius: 6px;
   padding: 25px,20px;
   cursor: pointer;
    margin-top: 50px;
}
.service .serv-content .card i{
  font-size: 50px;
  color: blueviolet;
  transition: all 0.3s ease-in-out;
}
.service .serv-content .card:hover i{
  font-size: 50px;
  color: white;
 
}
.service .serv-content .card .box{
  transition: all 0.3s ease-in-out;
}
.service .serv-content .card:hover .box{
 transform: scale(1.05);
 background: rgb(184, 54, 184);
 color: white;
}

.service .serv-content .card .text{
   margin-bottom: 14px;
   font-size: 20px;
   font-weight: 500;

}


</style>