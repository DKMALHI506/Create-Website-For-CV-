# Create-Website-For-CV-


Usinig Html, Css, php, Js.

<!doctype html>
<html lang="en">
<head>
    <!-- META -->
    <meta charset="utf-8">
    <meta name="robots" content="noodp">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
   
    <!-- PAGE TITLE -->
    <title>Dileep_Kumar - CV</title>
   
    <!-- FAVICON -->
    <link rel="shortcut icon" href="assets/img/favicon.png">
   
    <!-- FONTS -->
    <link href="https://fonts.googleapis.com/css?family=Abril+Fatface%7CArapey&amp;subset=latin-ext" rel="stylesheet">
   
    <!-- STYLESHEETS -->
    <link rel="stylesheet" type="text/css" href="assets/css/plugins.css">
    <link rel="stylesheet" type="text/css" href="assets/css/main.css">
</head>
<body>
    <!-- PRELOADER -->
    <div class="preloader">
        <div class="spinner"></div>
    </div>
    <!-- /PRELOADER -->

    <!-- IMAGE CONTAINER -->
    <div class="image-container">
        <div class="background-img"></div>
    </div>
    <!-- /IMAGE CONTAINER -->

    <!-- CONTENT AREA -->
    <div class="content-area">
        <!-- CONTENT AREA INNER --> 
        <div class="content-area-inner">

            <!-- INTRO -->
            <section id="intro">
                <!-- CONTAINER MID -->
                <div class="container-mid">
                    <!-- ANIMATION CONTAINER -->
                    <div class="animation-container animation-fade-down" data-animation-delay="0">
                        <h1>I’m Dileep Kumar,</h1>
                    </div>
                    <!-- /ANIMATION CONTAINER -->
                    
                    <!-- ANIMATION CONTAINER -->
                    <div class="animation-container animation-fade-left" data-animation-delay="300">
                        <p class="subline">Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
                    </div>
                    <!-- /ANIMATION CONTAINER -->
                    
                    <!-- ANIMATION CONTAINER -->
                    <div class="animation-container animation-fade-up" data-animation-delay="600">
                        <a href="#about" class="smooth-scroll">Learn More<i class="fa fa-angle-down" aria-hidden="true"></i></a>
                    </div>
                    <!-- /ANIMATION CONTAINER -->
                </div>
                <!-- /CONTAINER MID -->
            </section>
            <!-- /INTRO -->

            <!-- ABOUT -->
            <section id="about">
                <h3 class="headline scroll-animated-from-right">Why I can help you.</h3>
                <p class="scroll-animated-from-right">Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
                <p class="scroll-animated-from-right">Duis consectetur massa sit amet nibh rhoncus, at pharetra ligula aliquet...</p>
            </section>
            <!-- /ABOUT -->

            <!-- SERVICE -->
            <section id="service">
                <h3 class="headline scroll-animated-from-right">What I can do for you.</h3>
                <!-- SERVICE LIST -->
                <ul class="services-list">
                    <li class="scroll-animated-from-right"><i class="fa fa-robot-o" aria-hidden="true"></i>Machine Learning</li>
                    <li class="scroll-animated-from-right"><i class="fa fa-database" aria-hidden="true"></i>Data Science</li>
                    <li class="scroll-animated-from-right"><i class="fa fa-chart-bar" aria-hidden="true"></i>Data Analysis</li>
                    <li class="scroll-animated-from-right"><i class="fa fa-code" aria-hidden="true"></i>Python Programming</li>
                    <li class="scroll-animated-from-right"><i class="fa fa-bar-chart" aria-hidden="true"></i>Statistical Modeling</li>
                </ul>
                <!-- /SERVICE LIST -->
            </section>
            <!-- /SERVICE -->

            <!-- WORK -->
            <section id="work">
                <h3 class="headline scroll-animated-from-right">My latest Work.</h3>
                <!-- SHOWCASE -->
                <div class="showcase">
                    <!-- ITEM 1 -->
                    <div class="item scroll-animated-from-right">
                        <a href="#" data-featherlight="#item-1-lightbox">
                            <!-- INFO -->
                            <div class="info">
                                <!-- CONTAINER MID -->
                                <div class="container-mid">
                                    <h5>Fashion Inc.</h5>
                                    <p>Data Analysis</p>
                                </div>
                                <!-- /CONTAINER MID -->
                            </div>
                            <!-- /INFO -->
                            <div class="background-image" style="background-image: url(assets/img/work/item-1.jpg)"></div>
                        </a>
                        <!-- LIGHTBOX 1 -->
                        <div id="item-1-lightbox" class="work-lightbox">
                            <img class="img-responsive" src="assets/img/work/item-1.jpg" alt="image">
                            <h3>Fashion Inc.</h3>
                            <p class="subline">Data Analysis</p>
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
                        </div>
                        <!-- /LIGHTBOX 1 -->
                    </div>
                    <!-- /ITEM 1 -->
                    <!-- ... (similar structure for other items) ... -->
                </div>
                <!-- /SHOWCASE -->
            </section>
            <!-- /WORK -->

            <!-- CONTACT -->
            <section id="contact">
                <h3 class="headline scroll-animated-from-right">Contact Me.</h3>
                <!-- CONTACT LIST -->
                <ul class="contact-list">
                    <li class="scroll-animated-from-right"><i class="fa fa-mobile" aria-hidden="true"></i>01572 115522</li>
                    <li class="scroll-animated-from-right"><i class="fa fa-envelope-o" aria-hidden="true"></i>johnmiller@mail.com</li>
                </ul>
                <!-- /CONTACT LIST -->
                <!-- CONTACT FORM --> 
                <form id="contact-form" action="assets/php/contact.php" method="post">
                    <!-- ... (form input fields and submit button) ... -->
                </form>
                <!-- /CONTACT FORM --> 
            </section>
            <!-- /CONTACT -->

            <!-- FOOTER -->
            <section id="footer">
                <!-- SOCIAL ICONS -->
                <ul class="social-icons scroll-animated-from-right">
                    <li><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
                    <li><a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
                    <li><a href="#"><i class="fa fa-google-plus" aria-hidden="true"></i></a></li>
                    <li><a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
                </ul>
                <!-- /SOCIAL ICONS -->
                <p class="scroll-animated-from-right">© 2017 Your Brand | Design by <a href="https://templatefoundation.com">Template Foundation</a></p>
            </section>
            <!-- /FOOTER -->
        </div>
        <!-- /CONTENT AREA INNER -->
    </div>
    <!-- /CONTENT AREA -->
    
    <!-- JAVASCRIPTS -->
    <script type="text/javascript" src="assets/js/plugins.js"></script>
    <script type="text/javascript" src="assets/js/main.js"></script>
</body>
</html>
