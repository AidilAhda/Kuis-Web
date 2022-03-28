<template>  
        <section class="about" id="about">
    <div class="max-width">
      <h2 class="title">About me</h2>
        <div class="about-content">
            <div class="left">
                <img src="../assets/orangAbout.jpg">
            </div>
        </div>
    </div>
</section>
      
  <footer>
    <hr />
    <p>@Copyright2022,Aidil Ahda</p>
  </footer>
</template>
<style scoped>
section{
  padding: 100px,0;
}
  .about{
    font-family: sans-serif;
  }
  .about .title{
    text-align: center;
    font-size: 40px;
    font-weight: 500;
    margin-bottom: 60px;
    padding-bottom:20px ;
    font-family: sans-serif;
  }
  .about.title ::before{
    content:"";
    position: absolute;
    width: 180px;
    height: 3px;
    background: #1111;
  }
  .about .about-content .left img{
    height: 400px;
    width: 400px;
    object-fit: cover;
  } 
  
</style>
