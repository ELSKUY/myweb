<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
        <div class="container">
            <a href="#" class="logo">Mario Simanjuntak</a>
            <nav>
                <ul>
                    <li><a href="#home" class="active">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#education">Education</a></li>
                    <li><a href="#whatsapp">WhatsApp</a></li>
                    <li><a href="#instagram">Instagram</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="home">
            <video autoplay muted loop>
                <source src="vu.webm" type="video/webm">
            </video>  
        <div class="container">
            <div class="home-img">
                <img src="ma.jpeg" alt="Mario Simanjuntak">
            </div>
            <div class="home-content">
                <h1>Mario Simanjuntak</h1>
                <h3>I'm a <span>Web Developer</span></h3>
                <p>Hi, I am Mario Daniel Justin Simanjuntak, usually called Rio. I am 17 years old and currently a student majoring in computer engineering.</p>
                <div class="social-icons">
                    <a href="https://twitter.com/yourprofile"><img src="x.png" alt="Twitter"></a>
                    <a href="https://facebook.com/yourprofile"><img src="fb.png" alt="Facebook"></a>
                    <a href="https://instagram.com/yourprofile"><img src="ig.png" alt="instagram"></a>
                    <a href="https://facebook.com/yourprofile"><img src="fb.png" alt="Facebook"></a>
                </div>
                <a href="file:///home/daniel/Downloads/Putih%20Simple%20CV%20Lamaran%20Desain%20Grafis_20241112_113904_0000-1.pdf" class="btn" download>Download CV</a>
            </div>
        </div>
    </section>

    <section id="services" class="services">
        <div class="container">
            <h2>Services</h2>
            <div class="service-items">
                <div class="service-item">
                    <h3>WEB DEVELOPMENT</h3>
                    <p>I create modern and responsive websites using the latest technologies like HTML, CSS, and JavaScript.But i'm still begginer lol</p>
                </div>
                <div class="service-item">
                    <h3>MUSIC</h3>
                    <p>I can play music, especially piano. If you need a pianist, you can use me</p>
                </div>
                <div class="service-item">
                    <h3>SOFTWARE DEVELOPMENT</h3>
                    <p>Building custom software solutions tailored to meet your business needs.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>
                    <span>HTML</span>
                    <div class="progress-bar">
                        <div class="progress" style="width: 90%;"></div>
                    </div>
                    <span class="percentage" data-target="90">90%</span>
                </li>
                <li>
                    <span>CSS</span>
                    <div class="progress-bar">
                        <div class="progress" style="width: 85%;"></div>
                    </div>
                    <span class="percentage" data-target="80">80%</span>
                </li>
                <li>
                    <span>JavaScript</span>
                    <div class="progress-bar">
                        <div class="progress" style="width: 55%;"></div>
                    </div>
                    <span class="percentage" data-target="50">50%</span>
                </li>
                <li>
                    <span>Piano</span>
                    <div class="progress-bar">
                        <div class="progress" style="width: 90%;"></div>
                    </div>
                    <span class="percentage" data-target="90">90%</span>
                </li>
            </ul>
        </div>
    </section>
    <section id="education" class="education">
        <div class="container">
            <h2>Education</h2>
            <p>I am currently studying at a school in Jakarta and I am pursuing my major, namely TKJ.</p>
            <p>Here are my academic achievements:</p>
            <ul>
                <li>HIGH SCHOOL TERATAI PUTIH JAKARTA</li>
            </ul>
        </div>
    </section>

    <section id="whatsapp" class="whatsapp">
      <div class="container">
          <h2>WhatsApp</h2>
          <p>You can contact me on WhatsApp: 
              <a href="https://web.whatsapp.com/2" class="btn-whatsapp">Click here to message me</a>
          </p>
      </div>
  </section>
  <section id="instagram" class="instagram">
    <div class="container">
        <h2>Instagram</h2>
        <p>Follow me on Instagram: 
            <a href="https://www.instagram.com/?next=%2F" class="btn-instagram">Instagram Profile</a>
        </p>
    </div>
</section>
<script src="scipt.js"></script>
</body>
</html>
