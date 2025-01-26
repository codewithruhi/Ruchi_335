<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Education Website</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }
    header {
      background: palevioletred;
      color:rgb(225, 188, 202);
      padding: 10px;
      text-align: center;
    }
    nav {
      display: flex;
      background: #333 ; height: 100px;
      padding-bottom: 20px;
      justify-content: center;
      
    }
    #img1{
      height: 150px;
      width: 150px;
      position: relative;
      right: 300px;
    }
    nav a {
      color: white;
      text-shadow:2px 3px 4px ;
      padding: 20px;
      margin: 20px;
      text-decoration: none;
      font-size: larger;
      
    }
    nav a:hover {
      background: #575757;
    }
    
    }
    .hero h1 {
      font-size: 3rem;
      margin: 0;
    }
    .container {
      padding: 2rem;
    }
    #sec_2{
      background-image:url("https://image.slidesdocs.com/responsive-images/background/education-at-your-fingertips-3d-illustration-of-digital-learning-on-mobile-website-powerpoint-background_9f13514525__960_540.jpg") ;
      height: 1000px;
      width: 1500px;
      background-size: cover;
    }
    #sec_2 h1{
      text-align: center;
      font-size:50px;
      color: #ede6e8;
    }
    .section {
      margin: 2rem 0;
    }
    .section h2 {
      text-align: center;
      margin-bottom: 1rem;
      color: #4CAF50;
    }
    .courses {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }
    .course {
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 1px;
      text-align: center;
    }
    .course h3 {
      color: #333;
    }
    .course p {
      color: #666;
    }
    footer {
      background: #474646;
      color: rgb(237, 149, 149);
      text-align: center;
      padding: 1rem 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to EduLearn</h1>
    <p>Unlock Your Potential with Quality Education</p>
  </header>

  <nav>
    <img src="https://marketplace.canva.com/EAFn4Tt4VXg/1/0/1600w/canva-green-and-black-minimalist-education-logo-i1idlPnJILs.jpg" id="img1">
    <a href="#courses">Courses</a>
    <a href="#features">Features</a>
    <a href="#contact">Contact</a>
  </nav>

  

  <div class="container">
    <section id="sec_2">
      <h1>Learn Anywhere Any Time</h1>
    </section>
    <section id="courses" class="section">
      <h2>Our Popular Courses</h2>
      <div class="courses">
        <div class="course">
          <h3>Web Development</h3>
          <p>Master the art of building websites.</p>
        </div>
        <div class="course">
          <h3>Data Science</h3>
          <p>Learn data analysis and machine learning.</p>
        </div>
        <div class="course">
          <h3>Graphic Design</h3>
          <p>Create stunning visuals and designs.</p>
        </div>
      </div>
    </section>

    <section id="features" class="section">
      <h2>Why Choose Us</h2>
      <p style="text-align: center;">We offer top-notch instructors, flexible schedules, and hands-on projects to ensure you excel in your learning journey.</p>
      <p style="text-align: center;">Education is the key to unlocking potential, and we provide the tools to help you succeed.</p>
    </section>

    <section id="contact" class="section">
      <h2>Contact Us</h2>
      <p style="text-align: center;">Email: edu@learn.com | Phone: 9876543210</p>
    </section>
  </div>

  <footer>
    <p>"We aim to make learning accessible to everyone, fostering knowledge and innovation."</p>
  </footer>
</body>
</html>
