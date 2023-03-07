
<!doctype html>
<html lang="en">
  <head>
    <title>Title</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <!--my css file-->
   <style>

*{
  box-sizing: border-box;
}
body{
    background-color: #1E1E1E;
    color: #ffffff;
}
#navbar{
    width: 100%;
    height: 65px;
    justify-content: center;
    background: transparent;
    font-size: 20px;
    font-family: Tahoma;
    text-align: center;
    padding-top: 15px;

}
#navbar a{
    margin-left: 40px;
    text-decoration: none;
}
#navbar a:first-child{
    margin-right: 0;
}
#navbar .nav-link{
    color: #ffffff;
    margin-top: 20px;
    margin-right: 7px;
} 
.image{
    width: 100vw;
    height: 100vh;
    max-width: 100%;
    opacity: 0.4;
}

.container h1{
  color:#1E1E1E;
}
.container label{
  color: #1E1E1E;
}
.container{
  max-width: 400px;
  padding: 16px;
  background-color: #ffffff;
  justify-content: center;
  opacity: 1;
  right: 35%;
  top: 50%;
  max-height: 400px;
  margin-left: 800px;
  margin-bottom: -99;
  transform: translateY(-500px);
  border-color: #ffffff;

}
input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  border: none;
  background: #f1f1f1;
}
input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}
.btn {
  background-color: #1E1E1E;
  color: white;
  padding: 16px 20px;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}
.btn:hover {
  opacity: 1;
}
.bg-img{
  max-height: 1px;
  background-position: right;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
  border-color: white;
  display: grid;
}
.product-section{
  margin-bottom: 15px;
  margin-top: 0;
}
.card1{
    transition: 0.3s;
    width: 40vw;
    box-shadow: 0 2px 4px 0;
}
.card1:hover{
    box-shadow: 0 8px 16px 0;
}
.card1 img{
    opacity: 0.6;
}
.container1{
    padding: 2px 16px;
    font-family: Times New Roman;
    text-align: center;
    font-size: 25px;
    margin-bottom: 10%;
}
.centered {
    position: absolute;
    top: 50%;
    left: 35%;
    transform: translate(-50%, -50%);
    font-size: 50px;
    font-style: bold;

}
.centered h1{
    font-size: 100px;
    font-weight: 2000;
    font-style: bold;
    margin-bottom: 13px;
    margin-top: 10px;
}
.centered p{
    font-size: 30px;
}
.container1 a{
    text-decoration: none;
    color: #ffffff;
}
.card2{
    transition: 0.3s;
    width: 40vw;
    box-shadow: 0 2px 4px 0;
}
.card2:hover{
    box-shadow: 0 8px 16px 0;
}
.card2 img{
    opacity: 0.9;
}
.container3{
    padding: 2px 16px;
    font-family: Times New Roman;
    text-align: center;
    font-size: 25px;
    margin-bottom: 10%;
    max-width: 100%;
}
.container3 a{
    text-decoration: none;
    color: #ffffff;
}
.column1 {
    float: left;
    width: 25%;
    padding: 0 10px;
    margin-left: 70px;
  }
.column2 {
    float: right;
    width: 25%;
    padding: 0 10px;
    margin-right: 300px;

}  
.row {
    margin: 10px -5px;
    background-color: rgba(92,188,224,0.4);
}
.row:after {
    content: "";
    display: table;
    clear: none;
}
@media screen and (max-width: 600px) {
    .column1 {
      width: 100%;
      display: block;
      margin-bottom: 20px;
    }
} 
@media screen and (max-width: 600px) {
    .column2 {
      width: 100%;
      display: block;
      margin-bottom: 20px;
    }
}       
.cardS{
    transition: 0.3s;
    width: 40vw;
    box-shadow: 0 2px 4px 0;
    border-radius: 30px;
}  

.cardS:hover{
    box-shadow: 0 8px 16px 0;
}
.cardS img{
  opacity: 0.7;
  padding-top: 2px;
  border-radius: 30px;
  height: 340px;

}
.containerS{
    padding: 2px 16px;
    font-family: Times New Roman;
    text-align: center;
    font-size: 18px;
    margin-bottom: 20px;
}
.column2a{
    float: left;
    width: 25%;
    padding: 0 10px;
    margin-left: 70px;
   
}
.row2{
    margin: 0 -5px;
}
.row2:after{
    content: "";
    display: table;
    clear: none;
}
@media screen and  (max-width: 600px) {
    .column2a {
        width: 100%;
        display: block;
        margin-bottom: 18px;
      }
}
.features{
    padding-top: 2px;
    text-align: left;
    padding: 0 auto;
    
}

.cardT{
    transition: 0.3s;
    width: 40vw;
    box-shadow: 0 2px 4px 0;
    border-radius: 30px;
}
.cardT img{
  opacity: 0.7;
  padding-top: 2px;
  border-radius: 30px;
}
.cardT:hover{
    box-shadow: 0 8px 16px 0;
}
.containerT{
    padding: 2px 16px;
    font-family: Times New Roman;
    text-align: center;
    font-size: 18px;
    margin-bottom: 20px;
}
.column2b{
    float: right;
    width: 25%;
    padding: 0 10px;
    margin-right: 300px;
}
@media screen and  (max-width: 600px) {
    .column2b {
        width: 100%;
        display: block;
        margin-bottom: 20px;
      }
}
.enquire{
  font-size: 25px;
  background-color: transparent;
  border-radius: auto;
  color: #ffffff;
  border-color: #ffffff;
  cursor: pointer;
}
.about_us{
  display: grid;
  width: 100%;
  background: #1E1E1E;
  color: rgba(255, 255, 255, 0.7);
  text-align: left;
  padding: 30px 10% 50px 10%;
  height: 100%;
  box-sizing: border-box;
  background-color: rgba(92,188,224,0.4);
  font-size: xx-large;

}

.about_us > h2{
  display: block;
  color: rgba(255, 255, 255, 1);
  font-size: 32px;
  line-height: 31px;
  letter-spacing: 1px;
  font-weight: 700;
  margin: 50px auto;
}

.about_us > span {
  display: block;
  color: rgba(255, 255, 255, 1);
  font-size: 20px;
  font-weight: bold;
  line-height: 1.75;
  margin: 20px auto 10px;
}

.about_us > p{
  display: flex;
  font-size: 16px;
  font-weight: 500;
  line-height: 1.75;
  margin: 0 auto 10px;
}

.about_us > .mission{
  color: rgba(255, 255, 255, 1);
  display: block;
  width: 60%;
  box-sizing: content-box;
  border-radius: 10px;
  background-color: rgba(92,188,224,0.4);
  margin-left: 20%;
  padding: 5px 10px;
  margin-bottom: 20px; 

}

.about_us > .mission > span{
  display: flex;
  margin: 0 auto 10px;
  font-size: x-large;
  text-align: center;
  font-weight: 500;
  line-height: 1.75;
}
.about_us > .mission > p{
  display: block;
  color: rgba(255, 255, 255, 1);
  margin: 0 auto 10px;
  text-align: center;
  font-weight: 500;
  line-height: 1.75;
  font-size: medium;
}
.about_us > .vision{
  color: rgba(255, 255, 255, 1);
  display: block;
  width: 60%;
  box-sizing: content-box;
  border-radius: 10px;
  background-color: rgba(92,188,224,0.4);
  margin-left: 20%;
  padding: 5px 10px;
  margin-bottom: 20px;
  text-align: center;

}
.about_us > .vision> span{
  display: flex;
  margin: 0 auto 10px;
  font-size: x-large;
  text-align: center;
  font-weight: 500;
  line-height: 1.75;
}
.about_us > .vision > p{
  display: block;
  color: rgba(255, 255, 255, 1);
  margin: 0 auto 10px;
  text-align: center;
  font-weight: 500;
  line-height: 1.75;
  font-size: medium;
}
.about_us > .why{
  color: rgba(255, 255, 255, 1);
  display: block;
  width: 60%;
  box-sizing: content-box;
  border-radius: 10px;
  background-color: rgba(92,188,224,0.4);
  margin-left: 20%;
  padding: 5px 10px; 
  margin-bottom: 20px; 
  text-align: center;
}
.about_us > .why> span{
  display: flex;
  margin: 0 auto 10px;
  font-size: x-large;
  text-align: center;
  font-weight: 500;
  line-height: 1.75;
}
.about_us > .why > p{
  display: block;
  color: rgba(255, 255, 255, 1);
  margin: 0 auto 10px;
  text-align: center;
  font-weight: 500;
  line-height: 1.75;
  font-size: medium;
}
.containerC {
  max-width: 1170px;
  margin-left: auto;
  margin-right: auto;
  padding: 1em;
}
.containerC ul{
  list-style: none;
  padding: 0;
}
.brand {
  text-align: center;
  font-weight: 300;
  text-transform: uppercase;
  letter-spacing: 0.1em;
}
.brand span {
  color: #ffffff;
}
.info {
  border-top-left-radius: 4px;
  border-top-right-radius: 4px;
}

.info ul {
  text-align: center;
  margin: 0 0 1rem 0;
}
.contact form {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 20px;
}
.contact form label {
  display: block;
}
.contact form .full {
  grid-column: 1 / 3;
}
.contact form button,
.contact form input,
.contact form textarea {
  width: 100%;
  padding: 1em;
  border: solid 1px #ffffff;
  border-radius: 4px;
}
.contact form textarea {
  resize: none;
}
.info ul, .brand {
    text-align: left;
  }
  .contact {
    border-radius: 0 4px 4px 0;
  }
  .wrapper > * {
    padding: 2em;
  }

  .company-info {
    border-radius: 4px 0 0 4px;
  }
  @media only screen and (min-width: 700px) {
  .wrapper {
    display: grid;
    grid-template-columns: 1fr 2fr;
  }
}
.contact form button {
  background:rgba(92,188,224,0.4);
  border: 0;
  color: #e4e4e4;
  text-transform: uppercase;
  font-size: 14px;
  font-weight: bold;
  cursor: pointer;
}

.contact form button:hover,
.contact form button:focus {
  background: rgba(47, 161, 203, 0.553);
  color: #ffffff;
  outline: 0;
  transition: background-color 2s ease-out;
}  



</style>
    
    
  </head>
  <body>
  <div>
    <nav id="navbar">
      <a class="nav-link" aria-disabled="false" href="#Home">Home</a>
        <a class="nav-link"  aria-disabled="false" href="#Our Products">Our Products</a>
        <a class="nav-link" aria-disabled="false" href="#About Us">About Us</a>
        <a class="nav-link"  aria-disabled="false" href="#Contact">Contact</a>
    </nav>
  </div>
  <main>
    <section class="home-section" id="Home">
      <div id="img-background">
        <div class="container2">
          <div class="centered">
            <h1>Electro E-bikes</h1>
            Make your next ride smarter with electro!
            <p>Select from across a wide variety of e-bikes and accessories.</p>
          </div>
        </div>
         <img class="image" src="https://bit.ly/3zFLm9p" alt="image of bike1">
         <div class="bg-img">
            <form action="/action_page.php" class="container">
              <h1>Login</h1>
              <label for="email"><b>Email</b></label>
              <input type="text" placeholder="Enter Email" name="email" required>
              <label for="psw"><b>Password</b></label>
              <input type="password" placeholder="Enter Password" name="psw" required>
              <button type="submit" class="btn">Login</button>
            </form>
          </div>  
      </div>       
    </section>  
      <br>
      <div></div>
      <div></div>
    <section class="product-section" id="Our Products">
        <!--first row of two cards-->
      <div class="row">
        <div class="column1">
          <div class="card1">
           <img src="https://bit.ly/3JdhEf6" alt="img-scooters" style="width:100%" >
            <div class="container1">
             <h4><b><a href="#column2a" id="link1">Electric bikes</a></b></h4>
             <p>Explore the latest collection of e-bikes from your favourite brands</p>
            </div>
          </div>  
        </div>
        <div class="column2">
          <div class="card2">
           <img src="https://bit.ly/3cK5uxU" alt="img-mountainbikes" style="width:100%" >
            <div class="container3">
              <h4><b><a href="#Our Products" id="link2">Limited Edition Sale</a></b></h4>
              <p>Grab exciting deals on the exclusive models of electric mountain-bikes</p>
            </div>
          </div>
        </div>  
      </div>
      <div></div>
      <div></div>
      <br>
      <div class="row2" id="row2">
        <div class="column2a" id="column2a">
          <div class="cardS">
            <img src="https://bit.ly/3OG7YdV" alt="hero-optima cx" style="width:100%">
            <div class="containerS">
              <h1><b>Hero Electric Optima CX(dual battery)</b></h1>
              <h5>₹ 77,490</h5>
              <h4>Key Features</h4>
              <ul class="features">
                <li>Telescopic Suspension: Ensures your ride is smooth and jerk-free</li>
                <li>Built-in USB port enables you to charge your phone</li>
                <li>Alloy wheel makes your vehical light and stable</li>
                <li>Top Speed: 45km/h</li>
                <li>Full Charge: 4-5h</li>
                <li>Range: 145km with each charge</li>
              </ul>
              <form action="" >
                <input type="submit" value="Know more" text="Submit" class="enquire">
              </form>
            </div>
          </div>  
        </div>
        <br>
        <div class="column2b" id="column2b">
          <div class="cardT">
            <img src="https://bit.ly/3JiXSyM" alt="tvs-iqube" style="width:100%">
            <div class="containerT">
              <h1><b>TVS-iQube S</b></h1>
              <h4>Key Features</h4>
              <h5>₹1.18 lakhs</h5>
              <ul class="features">
                <li>7" screen and joystick for better access and navigating all the features</li>
                <li>TVS smartXonnect app for better navigation and access.</li>
                <li>17 ltrs under-seat storage and a USB port</li>
                <li>Full-charge: 4h 30 min</li>
                <li>Top-speed: 78km/h</li>
                <li>Range: 100km with each charge.</li>
              </ul>
              <form action="">
                <input type="submit" value="Know more" text="Submit" class="enquire">
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>
    <br>
    <div></div>
      <div></div>
    <section class="about_us" id="About Us">
      <h2>About Us</h2>
      <div class="mission">
        <span>Our Mission</span>
        <p>To offer quality products at affordable prices.</p>
      </div>
      <div class="vision">
      <span>Our Vision</span>
      <p>To contribute to the development of the country by providing mobility to millions. </p>
      </div>
      <div class="why">
       <span>Why us?</span>
        <p>Each product sourced from the leading e-bike manufacturers undergoes a quality assurance test before reaching the customers. 
         We are determined to provide the customers premium products backed by  customer support.</p>
      </div>
    </section>
    <br>
    <section class="contact us" id="Contact">
      <div class="containerC">
        <h1 class="brand"><span>Electro e bikes</span></h1>
          <div class="wrapper">
            <div class="info">
              <h3>Contact Us</h3>
              <ul>
                <li></li><i class="fa fa-road"></i>HSR layout, Bengaluru</li>
                <li><i class="fa fa-phone"></i>Phone: +91 0098765431</li>
                <li><i class="fa fa-email"></i>contactus@electro.in</li>
              </ul>
            </div>
            <div class="contact">
              <form id="contact-form">
                <p>
                  <label>Name</label>
                  <input type="text", name="name", required id="name">
                </p>
                <p>
                  <label>Contact Number</label>
                  <input type="number", name="phone.no", required id="phone.no">
                </p>
                <p>
                  <label>Email ID</label>
                  <input type="email", name="email", required id="email">
                </p>
                <p>
                  <label>Message</label>
                  <textarea type="text", name="msg", id="msg" rows="5"></textarea>
                </p>
                <p class="full">
                  <button type="submit">Submit</button>
                </p>
              </form>
            </div>

            </div>
          </div>
      </div>
    </section>
  </main>  
</body>
</html>

