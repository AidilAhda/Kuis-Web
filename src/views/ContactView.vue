<template>
  <section class="contact">
        <div class="max-width">
      <h2 class="title">Contact me</h2>
      <div class="contact-content">
      <div class="coloumn left">
          <div class="text">Get in Touch</div>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Omnis, expedita? Optio soluta nobis tempora ipsa facilis repellendus, molestiae sapiente tenetur.</p>
          <div class="icons">
              <div class="row">
               <i class="fa-solid fa-user"></i>
                <div class="info">
                    <div class="head">Name</div>
                    <div class="sub-title">Aidil Ahda</div>
                </div>
              </div>
              <div class="row">
               <i class="fa-solid fa-location-dot"></i>
                <div class="info">
                    <div class="head">Address</div>
                    <div class="sub-title">Bangkinang,Kampar,Riau</div>
                </div>
              </div>
              <div class="row">
              <i class="fa-solid fa-envelope"></i>
                <div class="info">
                    <div class="head">Email</div>
                    <div class="sub-title">AidilAhda@gmail.com</div>
                </div>
              </div>
          </div>
      </div>
      <div class="coloumn right">
          <div class="text">Message me</div>
          <form action="#">
              <div class="fields">
              
                  <div class="field name">
                      <input type="text" placeholder="Name" required>
                  </div>
                  <div class="field email">
                      <input type="email" placeholder="Email" required>
                  </div>
              </div>
                  <div class="field textArea">
                      <textarea  cols="30" rows="10" placeholder="Message me" required></textarea>
                  </div>
                  <div class="button">
                      <button type="submit">Submit</button>
                  </div>
              
          </form>
      </div>
     </div>
     </div>
  </section>
</template>



<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  
}
section {
  padding: 100px, 0; 
}
.contact {
  font-family: sans-serif;
  
}
.contact .title {
  text-align: center;
  font-size: 40px;
  font-weight: 500;
  margin-bottom: 60px;
  padding-bottom: 20px;
  font-family: sans-serif;
}
.contact .contact-content{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  margin-left: 34px;

  
}
.contact .contact-content .text{
    font-size: 20px;
    font-weight: 600;
    margin-bottom: 10px;
}
.contact .contact-content .coloumn{
    width: calc(50% - 30px);

}
.contact .contact-content .left p{
    text-align: justify;
}
.contact .contact-content .left .icons{
    margin: 10px 0;
}
.contact .contact-content  .row{
    display: flex;
    height: 65px;
    align-items: center;
}
.contact .contact-content  .row .info{
    margin-left: 30px;
}
.contact .contact-content  .row i{
    font-size: 25px;
    color: blueviolet;
}
.contact .contact-content .info .head{
    font-weight: 600;
}
.contact .contact-content .info .sub-title{
    color: rgba(0, 0, 0, 0.719);
}
.contact .right{
    margin-right: 24px;
}
.contact .right form .fields{
    display: flex;

}
.contact .right form .name{
    margin-right: 10px;
}
.contact .right form .textArea{
  height: 80px;
margin-bottom: 10px;
}
contact .right form .field,
.contact .right form .fields .field {
    height: 45px;
    width: 100%;
    margin-bottom: 15px;
}
.contact .right form .field input, 
.contact .right form .textArea textarea{
    height: 100%;
    width: 100%;
    border: 1px solid lightgray;
    border-radius: 6px;
    outline: none;
    padding: 0 15px;
    font-family: "Poppins",sans-serif;
    font-size: 17px;
}
.contact .right form .textArea textarea{
    padding-top: 10px;
    resize: none;
}
.contact .right form .button{
    height: 47px;
    width: 170px;
}
.contact .right form .button button{
    width: 100%;
    height: 100%;
    border: 2px solid rgb(255, 0, 242);
    background: rgb(255, 0, 242);
    color: white;
    font-size: 20px;
    font-weight: 500;
    border-radius: 6px;
    cursor: pointer;
    transition: all 0.3s ease;
}
.contact .right form .button button:hover{
    color: rgb(255, 0, 242);
    background: white;
}


</style>