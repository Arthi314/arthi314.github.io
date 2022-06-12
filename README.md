
<!-- Colorlib Jackson template
https://colorlib.com/wp/template/jackson/ -->
<!-- W3 Schools / W3CSS / Nature Portfolio Template
https://www.w3schools.com/w3css/tryw3css_templates_portfolio.htm
https://www.w3schools.com/w3css/tryit.asp?filename=tryw3css_templates_portfolio&stacked=h -->

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Arthi S - Homepage</title>
    <link rel="stylesheet" href="res/styles/w3.css">
    <link rel="stylesheet" href="res/styles/common.css">
    <link rel="stylesheet" href="res/styles/navigation.css">
    <script src='https://kit.fontawesome.com/a076d05399.js'></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
    <script src="res/scripts/navigation.js"></script>

    <link rel="stylesheet" href="home/res/styles/home.css">
    <script src="home/res/scripts/home.js"></script>

    <meta charset="UTF-8">
    <meta name="description" content="Homepage of Arthi S">
    <meta name="keywords" content="Arthi, Webpage, Homepage, Personal">
    <meta name="author" content="Arthi S">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<!-- Navigation Sidebar - Start-->
<nav class="w3-sidebar w3-collapse w3-light-grey w3-animate-left" style="z-index:3;width:260px" id="nav_panel">
    <div class="w3-container">
        <i onclick="w3_close()" class="w3-hide-large w3-right w3-xlarge w3-padding w3-hover-grey" title="close menu">
            <i class="fas fa-times"></i>
        </i>
        <h4><b>Arthi S</b></h4>
    </div>
    <div class="w3-bar-block">
        <a href="index.html" class="w3-bar-item w3-button selected-page">
            <i class="fa fa-home" style="width: 25px"></i> Home
        </a>
        <a href="research.html" class="w3-bar-item w3-button">
            <i class="fa fa-flask" style="width: 25px"></i> Research
        </a>
        <a href="work-experience.html" class="w3-bar-item w3-button">
            <i class="fa fa-briefcase" style="width: 25px"></i> Work Experience
        </a>
        <a href="res/documents/SNB_CV.pdf" target="_blank" class="w3-bar-item w3-button" title="Download CV">
            CV
        </a>
            </div>
    <div class="w3-panel w3-large">
        <a href="https://www.linkedin.com/in/arthi-s-0b836779" target="_blank"><i
                class="fab fa-linkedin color-linkedin w3-hover-opacity"></i></a> &ensp;
        <a href="https://github.com/Arthi314" target="_blank"><i
                class="fab fa-github w3-hover-opacity"></i></a> &ensp;
         </div>
    </nav>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large w3-animate-opacity" onclick="w3_close()" style="cursor:pointer"
     title="close side menu" id="content_overlay"></div>
<!-- Navigation Sidebar - End-->

<!-- Page content - Start -->
<div class="w3-main" style="margin-left:260px">
    <span class="w3-button w3-hide-large w3-xxlarge w3-hover-text-grey" onclick="w3_open()"><i
            class="fa fa-bars"></i></span>
    <div class="w3-container" style="padding-top: 25px">
        <h1 class="page-title">Arthi S's Homepage</h1>
    </div>
    <div class="w3-cell-row" style="width: 80%; margin-left: 10%; margin-right: 10%; margin-top: 50px">
        <div class="w3-container w3-cell w3-mobile" style="width: 35%">
            <img src="blob/main/IMG-20200929-WA0002-01.jpeg" alt="Profile Photo" width="250" height="275">
        </div>

        <div class="w3-container w3-cell w3-mobile" style="width: 65%">
            <h3 style="margin-bottom: 0">PhD Scholar</h3>
            <a href="http://ece.iisc.ac.in/" target="_blank">Department of Electrical Communication Engineering</a>
            <br/>
            <a href="http://www.iisc.ac.in/" target="_blank">Indian Institute of Science (IISc), Bengaluru</a> <br/>
            <br/>
            Email:
            <button id="email" onclick="displayEmail()">Click here to reveal email id</button>
            <br>
            Lab: Signal Processing Lab (SP 203) <br> <br>

            I have done my undergraduate in Electronics and Communication Engineering at College of Engineering Guindy, Anna University, Chennai in 2015.
            I completed my masters in Communication systems from IIT Madras in 2017.
            I worked as a RF Engineer in Qualcomm India Pvt. Ltd. for 3 years (2017-2020).
            In 2020, I joined IISc and I am currently pursuing Ph.D. in ECE Dept with
            <a href="https://ece.iisc.ac.in/~nextgenwrl/Neelesh.html" target="_blank">Dr. Neelesh B Mehta</a>.
            My current interests are in next generation wireless networks <br>
        </div>
    </div>
    <hr class="w3-dark-gray" style="height: 1px; margin-left: 5%; width: 90%">

</div>
<!-- Page content - End -->

</body>
</html>
