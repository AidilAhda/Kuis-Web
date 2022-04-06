<template>

  <section class="about" id="about">
    <div class="max-width">
      <h2 class="title">About me</h2>
      <div class="about-content">
        <div class="left">
          <img src="../assets/o1.jpg" />
        </div>
        <div class="right">
          <div class="text">
            I'm Aidil Ahda and I'm a <span>Student</span>
             </div>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Consequuntur incidunt explicabo, architecto labore voluptatem
              quidem laudantium porro quasi, ex similique rem non quod rerum eum
              debitis nisi sint quia distinctio? Deserunt deleniti saepe rerum
              officiis neque illum alias quia ipsa qui pariatur quaerat
              explicabo quo quis quas, perferendis ab laborum sint est quae?
              Saepe in dolorem doloremque, animi aspernatur ullam.
            </p>
            <a href="https://drive.google.com/file/d/1tPluotJpR88UG2CEp0s8Ok6KZLwbvLFb/view?usp=sharing">Download My CV
            <i class="fa-solid fa-download"></i>
           </a>
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
.about {
  font-family: sans-serif;
}
.about .title {
  text-align: center;
  font-size: 40px;
  font-weight: 500;
  margin-bottom: 60px;
  padding-bottom: 20px;
  font-family: sans-serif;
}
.about.title ::before {
  content: "";
  position: absolute;
  width: 180px;
  height: 3px;
  background: #1111;
}
.about .about-content .left img {
  height: 400px;
  width: 400px;
  object-fit: cover;
  border-radius: 6px;
}
.about .about-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}
.about .about-content .left {
  width: 45%;
}
.about .about-content .right {
  width: 55%;
}
.about .about-content .right .text{
  font-size: 25px;
  font-weight: 600;
  margin-bottom: 10px;
}
.about .about-content .right .text span{
  color: rgb(252, 48, 252);
}
.about .about-content .right p{
  text-align: justify;
}
.about .about-content .right a{
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
</style>
