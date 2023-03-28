<template>
  <div>
    <footer>
        <div class="content">
          <div class="top">
            <div class="logo-details">
              <i class="fab fa-slack"></i>
              <span class="logo_name">Sunrise Solar</span>
            </div>
            <div class="media-icons">
              <a href="#"><i id="social-footer" class="fab fa-facebook-f"></i></a>
              <a href="#"><i id="social-footer" class="fab fa-twitter"></i></a>
              <a href="#"><i id="social-footer" class="fab fa-instagram"></i></a>
              <a href="#"><i id="social-footer" class="fab fa-linkedin-in"></i></a>
              <a href="#"><i id="social-footer" class="fab fa-youtube"></i></a>
            </div>
          </div>
          <div class="link-boxes">
            <ul class="box">
              <li class="link_name">Quick Links</li>
              <li><a href="#">Home</a></li>
              <li><a href="#">About Us</a></li>
              <li><a href="#">Simple Steps</a></li>
              <li><a href="#">Contact Us</a></li>
            </ul>
            <ul class="box" id="boox">
              <li class="link_name">Services</li>
              <li><a href="#">Inspection</a></li>
              <li><a href="#">Installation</a></li>
              <li><a href="#">Financing</a></li>
              <li><a href="#">Home Insurance</a></li>
            </ul>
            <ul class="box">
              <li class="link_name">Contact</li>
              <li><a href="#">+1-234-56789</a></li>
              <li><a href="#">+1-234-56789</a></li>
              <li><a href="#">info@sunrise.com</a></li>
              <li><a href="#">info@sgainc.com</a></li>
            </ul>
            <ul class="box" id="boox">
              <li class="link_name">Skills</li>
              <li><a href="#">HTML & CSS</a></li>
              <li><a href="#">JavaScript</a></li>
              <li><a href="#">Photography</a></li>
              <li><a href="#">Photoshop</a></li>
            </ul>
            <ul class="box input-box">
              <li class="link_name">Subscribe</li>
              <li><input type="text" placeholder="Enter your email"></li>
              <li><input type="button" value="Subscribe"></li>
            </ul>
          </div>
        </div>
        <div class="bottom-details">
          <div class="bottom_text">
            <span class="copyright_text">Copyright <b>©</b> 2022 <b>(SGA Developers)</b> | All rights reserved</span>
            <span class="policy_terms">
              <a href="#">Privacy policy</a>
              <a href="#">Terms & condition</a>
            </span>
          </div>
        </div>
    </footer>
  </div>
</template>



<style scoped>
footer{
  font-size: 16px;
}
body{
  background: #EEECEB;
}

footer{
  background: #140B5C;
  width: 100%;
}

footer::before{
  content: '';
  height: 1px;
  width: 100%;
  background: #AFAFB6;
}

footer .content{
  max-width: 1250px;
  margin: auto;
  padding: 30px 40px 40px 40px;
}

.box a{
  text-transform: none;
}

footer .content .top{
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 50px;
}

.content .top .logo-details{
  color: #fff;
  font-size: 30px;
}

.content .top .media-icons{
  display: flex;
}

.content .top .media-icons a{
  height: 40px;
  width: 40px;
  margin: 0 8px;
  border-radius: 50%;
  text-align: center;
  /* line-height: 40px; */
  color: #fff;
  font-size: 17px;
  text-decoration: none;
  transition: all 0.4s ease;
}

#social-footer{
  position: relative;
  top: 11px;
}

.top .media-icons a:nth-child(1){
  background: #4267B2;
}

.top .media-icons a:nth-child(1):hover{
  color: #4267B2;
  background: #fff;
}

.top .media-icons a:nth-child(2){
  background: #1DA1F2;
}

.top .media-icons a:nth-child(2):hover{
  color: #1DA1F2;
  background: #fff;
}

.top .media-icons a:nth-child(3){
  background: #E1306C;
}

.top .media-icons a:nth-child(3):hover{
  color: #E1306C;
  background: #fff;
}

.top .media-icons a:nth-child(4){
  background: #0077B5;
}

.top .media-icons a:nth-child(4):hover{
  color: #0077B5;
  background: #fff;
}

.top .media-icons a:nth-child(5){
  background: #FF0000;
}

.top .media-icons a:nth-child(5):hover{
  color: #FF0000;
  background: #fff;
}

footer .content .link-boxes{
  width: 100%;
  display: flex;
  justify-content: space-between;
}

footer .content .link-boxes .box{
  width: calc(100% / 5 - 10px);
}

.content .link-boxes .box .link_name{
  color: #000;
  font-size: 23px;
  font-weight: 400;
  margin-bottom: 10px;
}

.link-boxes .box .link_name::before{
  content: '';
  height: 2px;
  width: 35px;
  background: #fff;
}

.content .link-boxes .box li{
  margin: 6px 0;
  list-style: none;
}

.content .link-boxes .box li a{
  color: #fff;
  font-size: 14px;
  font-weight: 400;
  text-decoration: none;
  opacity: 0.8;
  transition: all 0.4s ease
}

.content .link-boxes .box li a:hover{
  opacity: 1;
  text-decoration: underline;
}

.content .link-boxes .input-box{
  margin-right: 55px;
}

.link-boxes .input-box input{
  height: 40px;
  width: calc(100% + 55px);
  outline: none;
  border: 2px solid #AFAFB6;
  background: #140B5C;
  border-radius: 4px;
  padding: 0 15px;
  font-size: 15px;
  color: #fff;
  margin-top: 5px;
}

.link-boxes .input-box input::placeholder{
  color: #AFAFB6;
  font-size: 16px;
}

.link-boxes .input-box input[type="button"]{
  background: #fff;
  color: #140B5C;
  border: none;
  font-size: 18px;
  font-weight: 500;
  margin: 4px 0;
  opacity: 0.8;
  cursor: pointer;
  transition: all 0.4s ease;
}

.input-box input[type="button"]:hover{
  opacity: 1;
}

footer .bottom-details{
  width: 100%;
  background: #0F0844;
}

footer .bottom-details .bottom_text{
  max-width: 1250px;
  margin: auto;
  padding: 20px 40px;
  display: flex;
  justify-content: space-between;
}

.copyright_text b{
  color: #464e61;
}

.bottom-details .bottom_text span,
.bottom-details .bottom_text a{
  font-size: 14px;
  font-weight: 300;
  color: #fff;
  opacity: 0.8;
  text-decoration: none;
}

.bottom-details .bottom_text a:hover{
  opacity: 1;
  text-decoration: underline;
}

.bottom-details .bottom_text a{
  margin-right: 10px;
}

@media (max-width: 900px) {

  footer .content .link-boxes{
    flex-wrap: wrap;
  }
  footer .content .link-boxes .input-box{
    width: 40%;
    margin-top: 10px;
  }

}

@media (max-width: 700px){

  .content .top .logo-details{
    font-size: 26px;
  }
  .content .top .media-icons a{
    height: 35px;
    width: 35px;
    font-size: 14px;
    /* line-height: 35px; */
  }
  footer .content .link-boxes .box{
    width: calc(100% / 3 - 10px);
  }
  footer .content .link-boxes .input-box{
    width: 60%;
  }
  .bottom-details .bottom_text span,
  .bottom-details .bottom_text a{
    font-size: 12px;
  }

}

@media (max-width: 520px){

  footer::before{
    top: 145px;
  }
  .policy_terms{
    display: none;
  }
  #boox{
    text-align: right;
  }
  .copyright_text{
    text-align: center;
  }
  footer .content .top{
    flex-direction: column;
  }
  .content .top .media-icons{
    margin-top: 16px;
  }
  footer .content .link-boxes .box{
    width: calc(100% / 2 - 10px);
  }
  footer .content .link-boxes .input-box{
    width: 100%;
  }

}


</style>