<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia&effect=neon|outline|emboss|shadow-multiple">
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
    <style>
       @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&display=swap");
 
   
 
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
  
}

body {
  background: black;
}

header {
  position: fixed;
  top: 0;
  left: 0;
  z-index: 5;
  width: 100%;
  display: flex;
  justify-content: center;
  background: #333;
}

.navbar {
  display: flex;
  padding: 0 10px;
  max-width: 1200px;
  width: 100%;
  align-items: center;
  justify-content: space-between;
  cursor: pointer;
}



.navbar .links {
  display: flex;
  align-items: center;
}

.navbar .links li {
  position: relative;
  list-style: none;
}

.navbar .logo a {
  display: flex;
  align-items: center;
  margin-left: 0;
  font-size: 50px;
  font-family: "sofia",sans-serif;
}

header a, footer a {
  margin-left: 40px;
  text-decoration: none;
  color: #fff;
  height: 100%;
  padding: 20px 0;
  display: inline-block;
}

header a:hover, footer a:hover {
  color: rgb(216, 199, 199);
}

.homepage {
  height: 1000px;
  width: 100%;
  position:relative;
  background: url("images/home-bg.jpg");
  background-size: cover;
  background-attachment: fixed;
}

.homepage::before {
  
  position: absolute;
  left: 0;
  top: 0;
  height: 100%;
  width: 100%;
  background: rgba(0, 0, 0, 0.2);
}

.homepage .content {
  display: flex;
  height: 85%;
  z-index: 3;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.homepage .content h1 {
  font-size: 60px;
  font-weight: 700;
  margin-bottom: 10px;
  font-family: "sofia",sans-serif;
}

.homepage .content .text {
  margin-bottom: 50px;
  color: #fff;
  font-size: 20px;
  text-align: center;
  text-shadow: 0px 0px 10px rgba(0, 0, 0, 0.3);
}
.content{
    background-image: url("https://image.slidesdocs.com/responsive-images/background/coffee-beans-white-coffee-cup-coffee-table-powerpoint-background_f4ab4a034a__960_540.jpg");
    width: 100%;
    height:2500px;
    background-repeat: no-repeat;
    display: flex;
    justify-content: space-around;
    background-size: cover;
}
.content a {
  color: #000;
  display: block;
  text-transform: uppercase;
  font-size: 18px;
  margin: 0 10px;
  }
.About .text{
           font-family:sans-serif;
            display:flex;
            align-items:center;
            color:aliceblue;
            position: relative;
            flex-direction: column;
            gap:20px;
            padding: 100px 50px;
        }

 .contactform{
    display: flex;
    justify-content: center;
    width:100%;
    margin-top: 100px;
    height :500px;
    border: 2px solid black;
     border-radius: 20px;
    box-shadow: 3px 4px 100px rgb(239, 239, 248);
   
 }
.contact .row .col {
  padding: 0 10px;
  width: calc(100% / 2 - 50px);
}

.contact .col p {
  margin-bottom: 10px;
}

.contact .col p i {
  color: #7a7a7a;
  margin-right: 10px;
}

.contactform input {
  height: 45px;
  margin-top: 20px;
  margin-bottom: 20px;
  padding: 10px;
  width: 90%;
  font-size: 16px;
  outline: none;
  border: 1px solid #bfbfbf;
}

.contactform textarea {
  padding: 10px;
  width: 90%;
  font-size: 16px;
  height: 150px;
  outline: none;
  resize: vertical;
  border: 1px solid #bfbfbf;
  box-shadow:2px 3px 10px solid white;
}

.contactform button {
  margin-top: 10px;
  padding: 10px 20px;
  font-size: 17px;
  color: #fff;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  background: #333;
  transition: 0.2s ease;
  box-shadow:2px 3px 10px solid white;
  align-items: center;

}

.contactform button:hover {
  background: #525252;
}

footer {
  width: 100%;
  height: 400px;
  display: flex;
  justify-content: center;
  background: #7c7b7b;
  padding: 20px 0;
}


footer div {
  padding: 0 10px;
  max-width: 1200px;
  width: 100%;
  display: flex;
  justify-content: space-between;
}

footer span {
  color: #fff;
}

footer a {
  padding: 0;
}
.footericon{
    display: flex;
    align-items:center;
    justify-content: right;
    float: right;
}
.card img{
    width: 100%;
    height: 300px;
    display: flex;
    border: 2px solid black;
    border-radius: 60%;

}

.footer1 a {
    font-size: 14px;
    color:rgb(241, 227, 227);
    text-decoration: none;
    cursor: pointer;
    display: flex;
    justify-content:space-between;
    margin-left:10px;
}

.footer-item {
    display: flex;
    flex-direction: column;
    gap: 20px;
    position: relative;
    justify-content: center;
    
}
.footer-item span{
    font-size: 20px;
}
.categories .cards{
    background-image: url("https://png.pngtree.com/background/20230519/original/pngtree-an-old-coffee-shop-with-very-dark-walls-picture-image_2652909.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    height: 1000px;
    width: 100%;
    
    }
    .categories h2{
      font-size: 50px;
      font-family: 'Courier New', Courier, monospace;
      color: #fff;
      display: flex;
    }
    .categories p{
      font-size: 20px;
      color: #fff;
    }
@media screen and (max-width: 860px) {
  .navbar .logo a{
    font-size: 30px;
  }
  .navbar .links a{
    position: sticky;
    font-size: 10px;  
    width: 40px;
    display: relative;
    height: 10px;
    background: #333;
  }
   .navbar a{
    font-size: 5px;
   }
  

  .navbar .links li {
    font-size: 18px;
  }

 
.homepage .text h1{
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  font-size: 30px;
  margin-top: -50px;
}  
.homepage .text p{
  display: flex;
  margin-left: 0px;

}
  .content{
    width: 100%;
    height:500px;
    background-repeat: no-repeat;
    display: flex;
    background-size:contain;
    align-items: center;
    justify-content: center;
    margin-left: 200px;
    margin-top: 100px;
  }
  .content a {
    font-size: 17px;
    padding: 9px 20px;
  }
  .About img{
    width: 200px;
    height: 200px;
    border: 2px solid black;
    border-radius: 50%;
    display: flex;
    
  }
 
  .About{
    width: 550px;
    height:500px;
    margin-left: 10px;
    margin-top: -250px;
  }
  .categories h2,p{
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    margin-left: 60px;
    margin-top: 10px;
    flex-direction: row;
  }
  .categories h2{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-size: 20px;
   
}
  .categories p{
    display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  font-size: 5px;
  

  }
  .categories .cards{
    display: flex;
    height: fit-content;
    flex-grow: 1;
    flex-wrap: wrap;
    width: 100%;
  }
  .cards .card p {
    padding: 0 5px;
    margin-top: 5px;
    font-size: 20px;
    text-wrap: wrap;
    
    text-overflow: hidden;
  }
  form{
    width:500px;
    height: 350px;
    margin-left: 70px;
}
.contactform{
  width: 550px;
  margin-left: 270px;
  height: 400px;
}
footer{
  width: 550px;
  margin-left: 10px;
}
.footericon a{
  justify-content: space-around;
  margin-left: 10px;
  margin-right: 20px;

}
.footer-item{
  gap: 5px;
}
.footer-item span{
  margin-top: 20px;

}
.card img{
  object-fit: fill;
  height: 250px;

}
.categories{
  width: 550px;
}
  
}


    </style>
    
      
    
  </head>
  <body>
    <header>
      <nav class="navbar">
        <h2 class="logo"><a href="#">Caffeine</a></h2>
      
        <ul class="links">
          <li><a href="#home">Home</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#portfolio">Portfolio</a></li>
          <li><a href="#about">About Us</a></li>
          <li><a href="#contact">Contact Us</a></li>
        </ul>
                  <h3>Americano Coffee</h3>
          <p>An Americano is made by pouring hot water over one or two espresso shots, resulting in a drink of similar volume and strength to regular coffee. </p>
        </div>
        <div class="card">
          <img src="https://t4.ftcdn.net/jpg/06/85/03/65/360_F_685036582_QOdhu9QUVJQ2JdJJz9rhPbVLtPZ7KNNQ.jpg" alt="">
          <h3>Mocha Coffee</h3>
          <p>the basis is that a shot of espresso is combined with a chocolate powder or syrup, followed by milk or cream.</p>
        </div>
        <div class="card">
          <img src="https://t4.ftcdn.net/jpg/03/14/89/39/360_F_314893999_RjsSgKb35y7JL4fq6kE73bY3s2Ryp6G6.jpg" alt="">
          <h3>Black Coffee</h3>
          <p>Black coffee is a popular hot coffee drink consisting of ground coffee and water and can be prepared using different brewing methods.</p>
        </div>
        <div class="card">
          <img src="https://png.pngtree.com/thumb_back/fw800/background/20240401/pngtree-caramel-macchiato-coffee-in-glass-image_15644513.jpg" alt="">
          <h3>Macchiato Coffee</h3>
          <p>This coffee drink features a shot of espresso topped with a layer of frothy foam.</p>
        </div>
      </div>
    </section>

    
<section>
  <div class="contactform">
        <div class=" form">
          <form>
            <input type="text" placeholder="Name*" required>
            <input type="email" placeholder="Email*" required>
            <textarea placeholder="Message*" required></textarea>
            <button id="submit" type="submit">Send Message</button>
          </form>
        </div>
      </div>
    </section>

    <footer>
      <div>
        <span>Copyright © Mansi Vaghasiya 2024</span>
        <span class="footer">
           
            <div class="footericon">
                <a href="tel:+91-6352722836" target="_blank"><img src="https://www.freepnglogos.com/uploads/logo-telefone-png/telefone-png-fundo-transparente-gratis-27.png" width="50px" height="60px"></a>
                <a href="" target="_blank"><img src="https://www.freepnglogos.com/uploads/logo-gmail-png/logo-gmail-png-for-gmail-email-client-mac-app-store-16.png" width="50px" height="50px"></a>
                <a href="https://www.facebook.com/profile.php?id=61560512470643&mibextid=ZbWKwL" target="_blank"><img src="https://www.freepnglogos.com/uploads/facebook-logo-icon/facebook-logo-icon-facebook-icon-png-images-icons-and-png-backgrounds-1.png" width="50px" height="50px"></a>
                <a href=""target="_blank"><img src="https://www.freepnglogos.com/uploads/logo-ig-png/logo-ig-stunning-instagram-logo-vector-download-for-new-7.png" width="50px" height="50px"></a>
                
            </div>
            <div class="footer1">
              <div class="footer-item"> 
                  <span>Buy at coffee</span>
                  <a href="faq">Coffee At Home</a>
                  <a href="faq">Coffee Gifts</a>
                  <a href="faq">Office Coffee</a>
                  <a href="faq">Brewing Equietment</a>
                  </div>
  
              <div class="footer-item"> 
                  <span>Brew Guidelines</span>
                  <a href="faq">How to make Coffee</a>
                  <a href="faq">How to Grind Coffee</a>
                  
              </div>
              <div class="footer-item">
                  <span>The Company</span>
                  <a href="faq">About us</a>
                  <a href="faq"> Coffee Blog</a>
                  <a href="faq">Careers</a> 
                  <a href="faq">Press</a>
              </div>
  
              <div class="footer-item">
                  <span>Support</span>
                  <a href="faq">FAq</a>
                  <a href="faq">Contact us</a> 
                  <a href="faq">Terms</a> 
                  <a href="faq">Privacy</a>
              </div>
  
              
          </div>
        </span>
      </div>
    </footer>
   
  </body>
</html>
        
