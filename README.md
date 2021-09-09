# university_website
University website sample interface using html and css 

<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width,intial-scale=1.0">
        <title> University website design</title>  
        <link rel="stylesheet" href="style.css">
        <link rel="preconnect" href="https://fonts.gstatic.com">   
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;600;700&display=swap" rel="stylesheet">   
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.3/css/fontawesome.min.css">
    </head>
    <body>
        <section class="header">
            <nav>
                <a href="index.html"><img src="eduford_img/logo.png"></a>
              <div class="nav-links" id="navLinks"> 
                    
                    <i class="fa fa-times" "></i>
                    <ul>
                        <li><a href="index.html">HOME</a></li>
                        <li><a href="about.html">ABOUT</a></li>
                        <li><a href="course.html">COURSE</a></li>
                        <li><a href="blog.html">BLOG</a></li>
                        <li><a href="contact.html">CONTACT</a></li>
                    </ul>
                </div>
                <i class="fa fa-bars" "></i>
            </nav>


<div class = "text-box">
    <h1>World's Biggest University</h1>
    <pre><h1>University of London</h1> </pre>
    
    
    <a href="about.html"class="hero-btn">visit us to know more</a>
</div>            
        </section>

        <!--course-->
        <section class="course">
            <h1>Courses We Offer</h1>
            <p> We offers everything you need to become what you want to be.</p>

            <div class="row">
                <div class="course-col">
                    <h3>Intermediate</h3>
                    
                </div>  
                <div class="course-col">
                    <h3>Degree</h3>
                    
                </div>  
                <div class="course-col">
                    <h3>Post Graduation</h3>
                   
                      
                </div>    
                
            </div>

        </section>
<!---            campus       -->
<section class="campus">
    <h1>Expand your horizons and gain international <br>experience at our Institutes </h1>
    <p>Live and study in one of the greatest capital cities in the world.</p>
    <div class="row">
        <div class="campus-col">
            <img src="eduford_img/london.png">
            <div class="layer">
                <h3>LONDON</h3>
            </div>  
        </div>

        <div class="campus-col">
            <img src="eduford_img/newyork.png">
            <div class="layer">
                <h3>NEW YORK</h3>
            </div>  
        </div>

        <div class="campus-col">
            <img src="eduford_img/washington.png">
            <div class="layer">
                <h3>WASHINGTON</h3>
            </div>  
        </div>
    </div>
</section>


<!------text----->
<div class = "text-box1">
<h1>Where real skill meets the real world.<br> Where challenge meets opportunity.<br> Where it all comes together!</h1></div>
<!------------facilities-->


<section class="facilities">
    <h1>Our facilities</h1>
    <p>Benefit from access to a wide range of study resources and facilities.</p>
    
    <div class="row">
        <div class="facilities-col">
            <img src="eduford_img/library.png">
            <h3>World Class Library</h3>
            
        </div>

        <div class="facilities-col">
            <img src="eduford_img/basketball.png">
            <h3>Largest playground</h3>
            
        </div>

        <div class="facilities-col">
            <img src="eduford_img/cafeteria.png">
            <h3>Tasty and Healthy Food</h3>
            
        </div>
        
    </div>
<h1>Study resources and facilities</h1>
<p>You will benefit from access to a wide range of study resources and facilities,<br>
   including several libraries, electronic information services, and computing facilities.<br>
   The ULIP Library is the primary source of support and research material for students and<br>
   staff, offering subject-specific resources and access to dozens of electronic databases.<br> 
   It also offers a comfortable, welcoming and secure space for study, research, work and interaction.<br> 
   Our Head of Library is on-hand to introduce you to the facilities and services available,<br>and to 
   point you in the right direction towards any off-site provision.</p>
</section>
<!---testimonials-->
<section class="testimonials">
    <h1>What our students says</h1>
    <p>Lorem ipsum dolor</p>
    <div class="row">
        <div class="testimonial-col">
            <img src="eduford_img/user1.jpg">
            <div>
                <p>
                    ---Lorem ipsum dolor---  
                </p>
                <h3>Christine Berkley</h3>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
            </div>

        </div>

        <div class="testimonial-col">
            <img src="eduford_img/user2.jpg">
            <div>
                <p>
                    ---Lorem ipsum dolor---  
                </p>
                <h3>David Byer</h3>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-o"></i>
            </div>

        </div>
    </div>

</section>
<!------call to action-->
<section class="cta">
    <h1>
        Enroll for our various online Courses <br>anywhere from the world
    </h1>
    <a href="contact.html" class="hero-btn">CONTACT US</a>
</section>

<!-----footer-->
<section class="footer">
    <h3>About us</h3>
    <p>We are one of the largest, most diverse universities in the UK 
        with over 120,000 students in London,<br> and a further 50,000
        studying across 190 countries for a University of London degree.
    </p>
    <div class="icons">
        <i class="fa fa-facebook"></i>
        <i class="fa fa-instagram"></i>
        <i class="fa fa-twitter"></i>
        <i class="fa fa-linkdin"></i>

    </div>
    <p>Made with <i class="fa fa-heart-o"></i> easy totorials</p>
</section>

 <!---java script for toggle menu    --->
        <script>
            var navLinks = document.getElementById("navLinks");

            function showMenu(){
                navLinks.style.right="0";
            }
            function hideMenu(){
                navLinks.style.right="-200px";
            }
        </script>
    </body>
</html>
