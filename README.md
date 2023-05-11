<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name - Software Engineer</title>
  <link rel="stylesheet" href="styles.css">
</head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.0.2/css/bootstrap.min.css">
  
<style>
  /* CSS styles for the website */

/* Reset default browser styles */
body, h1, h2, h3, p, ul, li {
  margin: 0;
  padding: 0;
}

/* Navbar styles */
nav {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: #333;
  color: #fff;
}

body {
  margin-top: 50px; /* Add margin to body to prevent content from overlapping with the fixed navbar */
}


nav ul {
  list-style-type: none;
  display: flex;
  justify-content: space-around;
  padding: 10px;
}

nav ul li {
  display: inline-block;
}

nav ul li a {
  text-decoration: none;
  color: #fff;
}

/* Header styles */
header {
  text-align: center;
  padding: 50px;
}

/* Home section styles */
.home {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #f2f2f2;
  padding: 50px;
}

.home-content {
  text-align: center;
}

.home-content h3 {
  font-size: 2rem;
  font-weight: 700;
  color: #333;
  margin-bottom: 2rem;
}

.home-content h1 {
  font-size: 4rem;
  font-weight: 700;
  color: #333;
  margin-bottom: 1rem;
}

.home-content p {
  font-size: 1.6rem;
  color: #666;
  margin-bottom: 2rem;
}
.social-media {
  display: flex;
  justify-content: center;
}

.social-media a {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 3rem;
  height: 3rem;
  background-color: #333;
  border-radius: 50%;
  margin-right: 1rem;
  transition: background-color 0.3s ease;
}

.social-media a img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 50%;
}

.social-media a:hover {
  background-color: #0ef;
}


.btn {
  display: inline-block;
  padding: 1rem 2.8rem;
  background-color: #0ef;
  border-radius: 4rem;
  font-size: 1.6rem;
  color: #fff;
  letter-spacing: 0.1rem;
  font-weight: 600;
  transition: background-color 0.3s ease;
  text-decoration: none;
}

.btn:hover {
  background-color: #0cf;
}

/* Footer styles */
footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px;
}
</style>

<body>
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="about.html">About Me</a></li>
      <li><a href="projects.html">Projects</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>

  <header>
    <h1>Welcome to My Website</h1>
    <p>A software engineer specializing in web development.</p>
  </header>

  <section class="home" id="home">
    <div class="home-content">
      <h3>Hello, it's Me</h3>
      <h1>Remedan Hyeredin</h1>
      <h3>And I'm a <span>frontend Developer</span></h3>
      <p> I am from Adama Science and Technology Universtiy, 
        <br> i am a 3rd year software engineering student and 
        <br> software programmer who has successfully complited
        <br>
        python,c++,html,java.
  
      </p>
  
      <div class="social-media">
        <a href="#"><img src="icones/facebook.png" alt="F"></a>
        <a href="#"><img src="icones/telegram.png" alt="T"></a>
        <a href="#"><img src="icones/instagram.png" alt="I"></a>
        <a href="#"><img src="icones/linkedin.png" alt="L"></a>
      </div>
      
      
        <a href="#" class="btn">Downlode CV</a>
      </div>
  
      <div class="home-img">
        <img src="image/me.jpg" alt="">
      </div>
  
  </section>

<br><br><br><br><br><br>


  <section class="about" id="about">
    <div class="about-img">
      <img src="image/me.jpg" alt="">
    </div>
    <div class="about-content">
      <h2 class="heading">About <span>Me</span></h2>
      <h3>Software Engineer</h3>
      <p>
        I am a software engineer proficient in Python, C++, HTML, and Java. I specialize in front-end development and have a strong passion for creating engaging and user-friendly websites. My skills include:
      </p>
      <ul>
        <li>Website development</li>
        <li>School projects for college students</li>
        <li>Personal portfolio websites</li>
        <li>Computer graphics</li>
        <li>Mobile application development</li>
        <li>Advanced programming</li>
      </ul>
    </div>
  </section>
  

<section>
  <div class="container">
    <h1>My Qualifications</h1>
    <ul class="qualification-list list-unstyled">
      <li>
        <img src="image/html-css.png" alt="HTML/CSS">
        <div>
          <h2>HTML/CSS</h2>
          <p>Proficient in creating structured and visually appealing web pages using HTML and CSS.</p>
        </div>
      </li>
      <li>
        <img src="image/js-logo.png" alt="JavaScript">
        <div>
          <h2>JavaScript</h2>
          <p>Experienced in building dynamic and interactive web applications using JavaScript.</p>
        </div>
      </li>
      <li>
        <img src="image/Java-Logo.png" alt="Java">
        <div>
          <h2>Java</h2>
          <p>Skilled in developing robust and scalable applications using the Java programming language.</p>
        </div>
      </li>
      <li>
        <img src="image/python.jpg" alt="Python">
        <div>
          <h2>Python</h2>
          <p>Proficient in Python programming and utilizing its versatility for various applications, including data analysis, web development, and automation.</p>
        </div>
      </li>
      <li>
        <img src="image/cpp.jpg" alt="C++">
        <div>
          <h2>C++</h2>
          <p>Strong understanding of C++ programming language, enabling efficient software development, system programming, and performance-critical applications.</p>
        </div>
      </li>
      <li>
        <img src="image/dart-flatter.jpg" alt="Dart/Flutter">
        <div>
          <h2>Dart/Flutter</h2>
          <p>Familiar with Dart and Flutter frameworks, enabling the development
 </div>
        </li>
    </ul>
    </div>
</section>

  
  <footer>
    <p>&copy; 2023 Your Name. All rights reserved.</p>
  </footer>
</body>
</html>

