<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frame</title>
    <link rel="stylesheet" href="css/form.css">
</head>

<body>
    <div class="navbar">
        <div class="container">
            <nav>
                <ul class="primary-nav">
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </div>

    <section class="profile">
        <div class="container">   
            <div class="profile-data">
                <img src="images/pranaypic.jpeg" class="profile-img" alt="ProfilePic">
                <div class="left-col">
                    <h1>Pranay Waghmare</h1>
                    <p>I'm a Web developer </p>
                    <div class="profile-cta">
                        <a class="icon-img" href="https://www.linkedin.com/in/pranay-waghmare-a576a59a/"><img src="images/Linkedin.png" alt="Linkedin"></a>
                        <a class="icon-img"> <img src="images/twitter.png" alt="Twitter"> </a>
                    </div>
                </div>
            </div>


            <div class="skills-section">
                <h2>
                    <span class="different">Technical Skills</span>
                </h2>
                <ul>
                    <li>
                        <img src="images/JavaScript.png" alt="Person">
                        <h3>JavaScript</h4>
                    </li>
                    <li>
                        <img src="images/Html.png" alt="Person">
                        <h3>HTML</h4>
                    </li>
                    <li>
                        <img src="images/CSS.png" alt="Person">
                        <h3>CSS</h4>
                    </li>
                </ul>
            </div>
        </div>
    </section>




    <section id="about" class="aboutme-section">
        <div class="container">

            <h2>About me</h2>
            <p>I am Computer Science Graduate and hails from Nagpur.I am a self-taught web
                developer who is passionate about learning new technologies & creating things.</p>

            <p>The power of Information and cloud technology has brought several positive outcomes in human life and
                make our life easier. I am cloud technology and web design enthusiast, so I truly love bringing ideas to
                life in the form of beautiful and responsive websites.
            </p>

            <p>I believe we never stop learning, so I work hard to expand my skill set and stay updated.
                I'm also very familiar with the importance of accessibility.</p>

        </div>
    </section>


    <section id="projects" class="projects-section">
        <div class="container">
            <h2>Projects</h2>
            <ul>
                <li>
                    <img src="images/Project.jpg" class="project-img" alt="Person">
                    
                    <h4>Data and Product Search Website / APP</h4>
                    <h5>Admin Panel (Website)</h5>
                    <div class="project-details">
                        <h4>The website and the app allow the customer to search
                            the products and easily get connected with the vendor
                            to make a deal.
                        </h4>
                        <h5>Built in Angular Framework</h5>
                    </div>
                </li>
            </ul>   
        </div>
    </section>


    <section id="contact" class="contact-section">
        <div class="container">
            <div class="contact-left">
                <h2>Contact</h2>
                <form action="">
                    <!-- <input type='hidden' name='form-name' value='form1'/> -->
                    <label for="name">Name
                    <input type="text" name="name" id="name" placeholder="" required></label>
                    <label for="email">Email
                    <input type="email" name="email" id="email" placeholder="" required></label>
                    <label for="message">Message
                    <textarea class="text-area" name="message" id="message" cols="50" rows="10" placeholder="" required></textarea></label>
                    <input class="submit-btn" type="submit" value="Send">
                </form>
            </div>
            <div class="contact-right">
                <a class="contact-info"><img src="images/email.png" class="contact-img" alt="Email">
                   pranaywg@gmail.com </a> <br> <br>
                <a class="contact-info"> <img src="images/location.png" class="contact-img" alt="Location">
                  Currently based in: Nagpur, India 
                </a>
            </div>
        </div>
    </section>

    <footer>
        <h5>Made by Pranay Waghmare &copy; 2021</h5>
    </footer>
</body>
</html>
