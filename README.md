<!DOCTYPE html>
<html style="height:100%";>
<head style="height:100%";>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
*{
  border-size:box-sizing;
}
body{
  overflow-x:hidden;
}
#navbar{
  width:100%;
  background-color:tomato;
  text-align:right;
  position:fixed;
  top:0;
  left:0;
  overflow:hidden;
}
#navbar a{
  display:inline-block;
  padding:30px 20px;
  text-decoration:none;
  color:white;
  text-weight:900;
}
#navbar a:hover{
  background-color:blue;
}
#welcome-section,#footer{
  height:100vh;
  width:100vw;
  position:relative;
  z-index:-1;
  right:25px;
}
#projects{
  width:100vw;
  position:relative;
  z-index:-1;
  right:25px;
}

#welcome-section{
  background-color:black;
}
#projects{
  background-color:SlateBlue;
  text-align:center;
  padding-top:20px;  
  padding-bottom:100px;
}
#title{
  color:white;
  font-size:40px;
  text-decoration:underline;
}
#footer{
  background-color:black;
}
#header, #designer{
  position:absolute;
  top:50%;
  left:50%;
  transform:translate(-50%,-50%);
}
#header{
  color:white;
  font-size:40px;
}
#designer{
  color:orange;
  top:60%; 
  font-size:20px;
}
#CSS-grid{
  display:grid;
  grid-template-columns:25% 25% 25%;
  grid-template-rows:auto auto;
  width:95vw;
  margin:auto;
  justify-content: center;
  grid-gap: 5%;
  
}
.project-title1{
  background-color:rgba(60, 60, 60, 0.8);
}
.project-title2{
  background-color:rgb(60, 60, 60, 0.8);
}
.project-title3{
  background-color:rgb(60, 60, 60, 0.8);
}
.project-title4{
  background-color:rgb(60, 60, 60, 0.8);
}
.project-title5{
  background-color:rgb(60, 60, 60, 0.8);
}
.project-title6{
  background-color:rgb(60, 60, 60, 0.8);
}
#description{
  padding:5px 0;
  color:#ddd;
  font-weight:1000;
  margin:0;

}
</style>
</head>
<body>
<nav id="navbar">
  <a href="#">About</a>
  <a href="#">Work</a>
  <a href="#">Contact</a>
</nav>
<section id="welcome-section">
  <h1 id="header">Hi I'm Su</h1>
  <p id="designer">a web designer</p>
</section>
<section id="projects">
  <p id="title"><b>These are some of my projects</b></p>
  <div id="CSS-grid">
    <div class="project-title1">
      <a href="" id="profile-link" target="_blank";>
        <img src="survey_demo.jpg" alt="survey_demo" style="width:100%;">
        <p id="description">survey</p>
      </a>
    </div>
    <div class="project-title2">
      <a href="" id="profile-link" target="_blank";>
        <img src="tribute_demo.jpg" alt="tribute_demo" style="width:100%;">
        <p id="description">tribute</p>
      </a>
    </div>
    <div class="project-title3">
       <a href="" id="profile-link" target="_blank";>
        <img src="documentation_demo.jpg" alt="documentation_demo" style="width:100%;">
        <p id="description">documentation</p>
       </a>
    </div>
    <div class="project-title4">
       <a href="" id="profile-link" target="_blank";>
          <img src="product_demo.jpg" alt="product_demo" style="width:100%;">
          <p id="description">documentation</p>
       </a>
    </div>
    <div class="project-title5"></div>
    <div class="project-title6"></div>
  </div>
</section>
<section id="footer">
</section>
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
</body>
</html>

