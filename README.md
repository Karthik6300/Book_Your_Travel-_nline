# Book_Your_Travel-_nline


* {
  margin: 0;
  padding: 0;
}
svg {
  height: 20%;
}

#nav {
  flex-wrap: wrap;
  display: flex;
  gap: 40px;
  margin: auto;
  background-color: rgba(146, 146, 221, 0.874);
  justify-content: center;
  padding: 20px 4px;
  width: 99%;
  position: sticky;
  top: 0px;
  /* border: 1px solid red; */
}
#nav li {
  font-size: larger;
  flex-wrap: wrap;
  justify-content: space-around;
  list-style-type: none;
}
.buy1 button{
  padding: 10px;
  border-radius: 10px;
  margin-top: -20px;
  background-color: yellow;
}
.buy1 button:hover{
  background-color: green;
  color: white;
}
.n1 {
  justify-content: end;
  font-size: xx-large;
}
.m2 {
  margin: auto;
}
#nav li a {
  text-decoration: none;
  color: black;
}

/* Coursel start */
.main-coursel h1 {
  text-align: center;
  width: 30%;
  margin: auto;
  /* border: 2px solid red; */
}
.main-coursel {
  /* border: 1px solid red; */
  width: 99.4%;
  height: 89vh;
  margin: auto;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  /* ----  animation style------- */
  animation-name: animi1;
  animation-duration: 15s;
  animation-iteration-count: infinite;
  animation-direction: normal;
  background-image: url(https://img.freepik.com/premium-photo/vacation-business-trip-travel-concept-with-graphic-passport-cover-light-suitcase-taking-off-plane-vector-illustration-blue-blank-background_551826-34288.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
/* ----animation keyframe starts---- */
@keyframes animi1 {
  10% {
    background-image: url(https://www.newdelhiairport.in/media/2618/kids-friendly-international-summer-destinations-to-visit-from-delhi-airport.jpg);
    background-repeat: no-repeat;
    background-size: cover;
  }
  20% {
    background-image: url(https://images.pexels.com/photos/1268855/pexels-photo-1268855.jpeg);
    background-repeat: no-repeat;
    background-size: cover;
    color: black;
  }
  30% {
    background-image: url(https://wallpapers.com/images/featured/tropical-w8d390to2znzlusb.jpg);
    background-repeat: no-repeat;
    background-size: cover;
  }
  40% {
    background-image: url(https://w0.peakpx.com/wallpaper/636/414/HD-wallpaper-travel-agency.jpg);
    background-repeat: no-repeat;
    background-size: cover;
  }
  60% {
    background-image: url(https://wallpapercave.com/wp/wp4069415.jpg);
    background-repeat: no-repeat;
    background-size: cover;
  }
  80% {
    background-image: url(https://images7.alphacoders.com/661/thumb-1920-661783.jpg);
    background-repeat: no-repeat;
    background-size: cover;
  }
  100% {
    background-image: url(https://png.pngtree.com/thumb_back/fw800/background/20240722/pngtree-travel-the-world-by-bus-tourism-day-concept-colored-flat-cartoon-image_15995248.jpg);
    background-repeat: no-repeat;
    background-size: cover;
  }
}

.heading1 {
  font-size: 3rem;
  width: 99.3%;
  text-align: center;
  /* border: 2px solid red; */
}
.dd {
  /* border: 1px solid red; */
  display: flex;
  /* flex-wrap: wrap; */
  justify-content: space-around;
  align-content: space-around;
  gap: 20px;
  width: 99.8%;
  height: 40%;
  /* margin-top: 25vh; */
  font-size: large;
  /* border: 1px solid red; */
  color: white;
}
.dd1 {
  text-align: center;
  /* border: 2px solid black; */
  /* height: 40%; */
  width: 40%;
  color: black;
}
.dd2 {
  text-align: center;
  /* border: 2px solid black; */
  /* height: 40%; */
  width: 40%;
  color: black;
}
.but1 button {
  font-style: italic;
  border-radius: 5px;
  margin: auto;
  display: flex;
  padding: 5px 5px;
  justify-content: center;
  align-content: center;
  background-color: yellow;
  /* background-color: yellow; */
}
.but1 button:hover {
  background-color: chartreuse;
  color:black;
  transform: scale(1.2);
}
.but1 a{
  text-decoration: none;
}

/* gallary-section */
#gallary-main {
  text-align: center;
}

/* gallary frames section start */
.main-frame {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding: 2rem 0.8rem;
  gap: 1rem;
  /* border: 1px solid red; */
  /* margin: auto; */
}

.frame-name {
  text-align: center;
  font-size: larger;
}
.frames-button {
  display: flex;
  gap: 10px;
  justify-content: space-around;
}
.frame1 a img {
  border-radius: 10px;
  width: 28.7rem;
}
.frame1:hover a{
  transform: scale(1.03);
}
.frame1 {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-content: space-around;
  /* border: 1px solid red; */
  border-radius: 10px;
  width: 28.7rem;
  height: 25rem;
  padding: 0.5rem;
  box-shadow: 2px 2px 10px black;
}
.button1 {
  padding: 0.8rem;
  background-color: rgb(238, 19, 55);
  color: white;
  border-radius: 10px;
}
.button1:hover{
  background-color: rgb(178, 178, 245);
  color: black;
}


.button2 {
  padding: 0.8rem;
  background-color: rgb(95, 95, 241);
  color: white;
  border-radius: 10px;
}
.button2:hover{
  background-color: rgb(178, 178, 245);
  
}

/* ------monitor section ------- */

#main-monitor {
  /* border: 2px solid red; */
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  background-color: rgb(82, 82, 200);
}
.monitor1 {
  /* border: 2px solid black; */
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  width: 50%;
  justify-content: center;
  align-content: center;
  padding: 20px;
  gap: 2rem;
}
#heading-1 {
  /* border: 2px solid red; */
  width: 40%;
  margin: auto;
  text-align: center;
  transform: scale(1.5);
}
.heading-2 {
  /* border: 2px solid red; */
  width: 50%;
  text-align: center;
  font-size: 1.5rem;
}
#monitor-list {
  /* border: 2px solid red; */
  display: flex;
  flex-direction: row;
  height: 2rem;
  gap: 30px;
  font-size: 1.3rem;
}
#monitor2 {
  /* border: 2px solid yellow; */
  width: 40%;
  padding: 20px;
}

/* Design layout section */

.design-layout {
  background-color: rgb(238, 233, 225);
  /* border: 2px solid red; */
  padding: 30px;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-around;
  align-content: space-around;
  gap: 5rem;
}
.design-dis {
  text-align: start;
  /* border: 2px solid red; */
  padding: 50px;
  line-height: 70px;
}
.design-dis h1 {
  font-size: 3rem;
}
.design-dis p {
  font-size: medium;
}

/* key features section */

.key-features {
  background-color: rgb(231, 198, 137);
  /* border: 2px solid red; */
  padding: 70px;
  text-align: center;
  line-height: 3rem;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
}
.key-dis {
  /* border: 2px solid red; */
  width: 60%;
  text-align: center;
  font-size: 1.3rem;
}

/* features divisions */

.features-divisions {
  /* border: 2px solid red; */
  padding: 40px;
  background-color: rgb(231, 198, 137);
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  gap: 40px;
}
.feature1 {
  padding: 0px;
  /* border: 2px solid green; */
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  height: 15rem;
  width: 30%;
  background-color: white;
  text-align: center;
  border-radius: 30px;
}

.feature-heading {
  font-size: 1.5rem;
}

.feature-dis {
  /* border: 1px solid red; */
  font-size: 1.5rem;
  width: 70%;
}

/* ---------period section------------- */

.period-section {
  padding: 50px;
  /* border: 2px solid red; */
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  text-align: center;
  gap: 20px;
  line-height: 3rem;
}
.period-dis1 {
  /* border: 1px solid green; */
  /* width: 80%; */
  font-size: 1.5rem;
}
.period-dis2 {
  /* border: 2px solid black; */
  /* width: 65%; */
  font-size: 1.3rem;
}
.period-dis3 {
  /* border: 2px solid gray; */
  /* width: 55%;   */
  font-size: 1.3rem;
}

/* ----------footer section ---------------*/

.footer-section {
  text-align: center;
  /* border: 2px solid red; */
  color: white;
  background-color: black;
  padding: 50px;
  line-height: 3rem;
}

.footer-section a {
  text-decoration: none;
  color: white;
}
.footer-opt {
  /* border: 2px solid white; */
  display: flex;
  flex-direction: column;
  font-size: 1.5rem;
}
.footer-opt1:hover {
  color: yellow;
  transform: scale(1.02);
}
.footer-opt2:hover {
  color: yellow;
  transform: scale(1.02);
}
.footer-opt3:hover {
  color: yellow;
  transform: scale(1.02);
}
.footer-button {
  padding: 10px;
  border-radius: 10px;
  background-color: yellow;
}
.footer-button:hover {
  background-color: rgb(113, 113, 222);
  color: white;
}

/* Media Quirees */
/* Extra Small Devices (Phones) */
@media (max-width: 480px) {
  /* nav bar */
#nav{
  padding: 10px 5px;
  gap: 20px;
}
 
  /* main screen  */
  .dd1 {
    width: 100%;
    font-size: smaller;
  }
  .dd2 {
    width: 100%;
    font-size: smaller;
  }
  .heading1 {
    font-size: 1rem;
  }

  /*gallary frames section */
  .main-frame {
    gap: 1rem;
  }
  .frame1 {
    width: 15rem;
  }
  .frame1 a img {
    width: 15rem;
  }
  .button1{
    padding: 0rem;
  }
  .button2{
    padding: 0rem;
  }
  /* monitor section */

  #heading-1 {
    font-size: 1rem;
    /* border: 2px solid black; */
    width: 70%;
    text-align: center;
  }
  .heading-2 {
    /* border: 2px solid black; */
    font-size: 1rem;
    margin: auto;
    width: 70%;
    padding: 0.5rem;
  }
  #main-monitor{  
    display: block;
    padding: 1px;
    text-align: center;
    /* border: 2px solid black; */
  }
  #monitor-list {
    /* border: 2px solid black; */
    font-size: 1rem;
    gap: 20px;
    display: block;
    padding: 0.5rem;

  }
  
  #monitor2 {
    padding: 3rem;
    width: 50%;
    height: 10rem;
    margin: auto;
  }
  .monitor1{
    width: 90%;
  }

  /* Design layout section */

  .design-layout {
    gap: 0.5rem;
    display: block;
  }

  .design-img {
    width: 100%;
    height: 20rem;
    border: 2px solid white;
  }
  .design-dis {
    width: 100%;
    line-height: 20px;
    padding: 10px;
  }
  .design-dis h1 {
    font-size: 1.5rem;
  }

  /* Key features section  */

  .key-features {
    padding: 20px;
    line-height: 1rem;
  }
  .key-dis {
    width: 90%;
    font-size: 0.8rem;
  }
  .key-heading1 {
    font-size: 1rem;
  }

  /* features divisions  */

  .feature1 {
    width: 80%;
  }
  .feature-heading {
    font-size: 1.5rem;
  }
  .feature-dis {
    width: 80%;
    font-size: 1rem;
  }

  /* ---------period section------------- */

  .period-dis1 {
    font-size: 1rem;
  }
  .period-dis2 {
    font-size: 0.8rem;
  }
  .period-dis3 {
    font-size: 0.8rem;
  }
  .period-section {
    line-height: 1.5rem;
  }
}

/* Small Devices (Tablets) */
@media (min-width: 481px) and (max-width: 768px) {

  /* nav bar */

  #nav{
    padding: 10px 5px;
    gap: 20px;
  }
  /* main screen  */
  .dd1 {
    width: 100%;
    font-size: 1rem;
  }
  .dd2 {
    width: 100%;
    font-size: 1rem;
  }
  .heading1 {
    font-size: 1.5rem;
  }

  /*gallary frames section */
  .main-frame {
    gap: 1rem;
  }
  .frame1 {
    width: 20rem;
  }
  .frame1 a img {
    width: 20rem;
  }

  /* monitor section */

  #heading-1 {
    font-size: 1rem;
  }
  .heading-2 {
    font-size: 1rem;
    margin: auto;
  }
  #monitor2 {
    padding: 40px;
    width: 30%;
    height: 20rem;
  }
  #monitor-list {
    font-size: 1rem;
    gap: 20px;
  }
  #monitor2 {
    padding: 20px;
    width: 20%;
    height: 15rem;
    margin: auto;
  }

  /* Design layout section */

  .design-layout {
    gap: 1rem;
  }

  .design-img {
    width: 20%;
    height: 20rem;
  }
  .design-dis {
    width: 35%;
    line-height: 50px;
  }
  .design-dis h1 {
    font-size: 1.5rem;
  }

  /* Key features section  */

  .key-features {
    line-height: 2rem;
  }
  .key-dis {
    width: 90%;
    font-size: 1.2rem;
  }
  .key-heading1 {
    font-size: 2rem;
  }

  /* features divisions  */

  .feature-heading {
    font-size: 1.2rem;
  }
  .feature-dis {
    width: 80%;
    font-size: 1rem;
  }
  .feature1 {
    width: 40%;
  }

  /* ---------period section------------- */

  .period-dis1 {
    font-size: 1.3rem;
  }
  .period-dis2 {
    font-size: 1rem;
  }
  .period-dis3 {
    font-size: 1rem;
  }
  .period-section {
    line-height: 1.7rem;
  }
}

/* Medium Devices (Small Laptops) */
@media (min-width: 769px) and (max-width: 1024px) {
  /* main screen  */
  .dd1 {
    width: 50%;
  }
  .dd2 {
    width: 50%;
  }
  /*gallary frames section */
  .main-frame {
    gap: 1rem;
  }
  .frame1 {
    width: 20rem;
  }
  .frame1 a img {
    width: 20rem;
  }

  /* monitor section */

  #heading-1 {
    transform: scale(1);
  }
  .heading-2 {
    font-size: 1.3rem;
    margin: auto;
  }
  #monitor2 {
    padding: 40px;
    width: 30%;
    height: 20rem;
  }
  /* Design layout section */

  .design-img {
    width: 25%;
    height: 30rem;
  }
  .design-dis {
    width: 40%;
    line-height: 50px;
  }

  /* Key features section  */

  .key-features {
    line-height: 2rem;
  }
  .key-dis {
    width: 70%;
  }

  /* features divisions  */

  .feature-heading {
    font-size: 1.2rem;
  }
  .feature-dis {
    width: 80%;
    font-size: 1rem;
  }

  .feature1 {
    width: 40%;
  }

  /* ---------period section------------- */

  .period-dis1 {
    font-size: 1.4rem;
  }
  .period-dis2 {
    font-size: 1.2rem;
  }
  .period-dis3 {
    font-size: 1.2rem;
  }
  .period-section {
    line-height: 1.7rem;
  }
}

/* Large Devices (Desktops) */
@media (min-width: 1025px) and (max-width: 1440px) {
  /* main screen  */
  .dd1 {
    width: 50%;
  }
  .dd2 {
    width: 50%;
  }

  /*gallary frames section */
  .main-frame {
    gap: 5rem;
  }
  .frame1 {
    width: 28rem;
  }
  .frame1 a img {
    width: 28rem;
  }

  /* monitor section */

  #heading-1 {
    transform: scale(1);
  }
  .heading-2 {
    font-size: 1.3rem;
    margin: auto;
  }

  /* Design layout section */

  .design-img {
    width: 30%;
  }
  .design-dis {
    width: 50%;
  }

  /* Key features section  */

  .key-dis {
    width: 70%;
  }
}

/* Extra Large Devices (Large Desktops) */
@media (min-width: 1441px) {
  /*gallary frames section */
  .main-frame {
    gap: 1.8rem;
  }
  /* Design layout section */

  .design-img {
    width: 30%;
  }
  .design-dis {
    width: 50%;
  }
}
