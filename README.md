<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Father Silvio Pasquali School</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f2f2f2;
    }
    header {
      background-color: #0057b7;
      color: white;
      text-align: center;
      padding: 20px;
    }
    header img {
      width: 100px;
      height: auto;
    }
    nav {
      background-color: #003d80;
      overflow: hidden;
    }
    nav a {
      float: left;
      color: white;
      text-align: center;
      padding: 14px 20px;
      text-decoration: none;
    }
    nav a:hover, .dropdown:hover .dropbtn {
      background-color: #00204d;
    }
    .dropdown {
      float: left;
      overflow: hidden;
    }
    .dropdown .dropbtn {
      border: none;
      outline: none;
      color: white;
      padding: 14px 20px;
      background-color: inherit;
      font: inherit;
      margin: 0;
    }
    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #003d80;
      min-width: 160px;
      z-index: 1;
    }
    .dropdown-content a {
      float: none;
      color: white;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
      text-align: left;
    }
    .dropdown-content a:hover {
      background-color: #00204d;
    }
    .dropdown:hover .dropdown-content {
      display: block;
    }
    .hero {
      background: url("https://username.github.io/father-silvio-website/school-building.png") no-repeat center center/cover;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2em;
      font-weight: bold;
    }
    .container {
      display: flex;
      max-width: 1200px;
      margin: 20px auto;
      gap: 20px;
    }
    .sidebar {
      flex: 1;
      background: white;
      padding: 15px;
      border-radius: 8px;
    }
    .main-content {
      flex: 3;
      background: white;
      padding: 20px;
      border-radius: 8px;
    }
    section {
      margin-bottom: 30px;
    }
    h2 {
      color: #0057b7;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #003d80;
      color: white;
    }
    /* Slideshow */
    .slideshow-container {
      max-width: 100%;
      position: relative;
      margin: auto;
    }
    .mySlides {
      display: none;
    }
    .mySlides img {
      width: 100%;
      border-radius: 6px;
    }
    .prev, .next {
      cursor: pointer;
      position: absolute;
      top: 50%;
      width: auto;
      padding: 16px;
      margin-top: -22px;
      color: white;
      font-weight: bold;
      font-size: 18px;
      transition: 0.6s ease;
      border-radius: 0 3px 3px 0;
      user-select: none;
    }
    .next {
      right: 0;
      border-radius: 3px 0 0 3px;
    }
    .prev:hover, .next:hover {
      background-color: rgba(0,0,0,0.8);
    }
    /* Table */
    table {
      width: 100%;
      border-collapse: collapse;
    }
    th, td {
      border: 1px solid #0057b7;
      padding: 10px;
      text-align: center;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://username.github.io/father-silvio-website/image.png" alt="School Logo">
    <h1>Father Silvio Pasquali School</h1>
    <p>Motto: Love, Joy, and Service</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#admissions">Admissions</a>
    <div class="dropdown">
      <button class="dropbtn">More ▾</button>
      <div class="dropdown-content">
        <a href="#gallery">Gallery</a>
        <a href="#timetable">Timetable</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
  </nav>

  <div class="hero">
    Welcome to Our School
  </div>

  <div class="container">
    <aside class="sidebar">
      <h2>Quick Links</h2>
      <ul>
        <li><a href="#about">About Us</a></li>
        <li><a href="#admissions">Admissions</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#timetable">Timetable</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </aside>

    <div class="main-content">
      <section id="about">
        <h2>About Us</h2>
        <p>Father Silvio Pasquali School is located in Mafinga, Iringa Region. We provide quality education focusing on love, joy, and service.</p>
      </section>

      <section id="admissions">
        <h2>Admissions</h2>
        <p>We welcome students from all backgrounds. For more information on enrollment and requirements, please contact our administration office.</p>
      </section>

      <section id="gallery">
        <h2>Gallery</h2>
        <div class="slideshow-container">
          <div class="mySlides">
            <img src="https://username.github.io/father-silvio-website/image1.png" alt="Gallery 1">
          </div>
          <div class="mySlides">
            <img src="https://username.github.io/father-silvio-website/image2.png" alt="Gallery 2">
          </div>
          <div class="mySlides">
            <img src="https://username.github.io/father-silvio-website/image3.png" alt="Gallery 3">
          </div>
          <a class="prev" onclick="plusSlides(-1)">❮</a>
          <a class="next" onclick="plusSlides(1)">❯</a>
        </div>
      </section>

      <section id="timetable">
        <h2>Timetable</h2>
        <table>
          <tr>
            <th>Day</th>
            <th>8:00-10:00</th>
            <th>10:15-12:15</th>
            <th>1:00-3:00</th>
          </tr>
          <tr>
            <td>Monday</td>
            <td>Math</td>
            <td>English</td>
            <td>Science</td>
          </tr>
          <tr>
            <td>Tuesday</td>
            <td>Swahili</td>
            <td>History</td>
            <td>PE</td>
          </tr>
          <tr>
            <td>Wednesday</td>
            <td>Math</td>
            <td>Geography</td>
            <td>Arts</td>
          </tr>
        </table>
      </section>

      <section id="contact">
        <h2>Contact</h2>
        <p>Email: frsilviopasquali22@gmail.com</p>
        <p>Phone: +255 788898096</p>
        <p>Address: Mafinga, Iringa Region, Tanzania</p>
      </section>
    </div>
  </div>

  <footer>
    &copy; 2025 Father Silvio Pasquali School. All rights reserved.
  </footer>

  <script>
    let slideIndex = 0;
    showSlides();
    function showSlides() {
      let i;
      let slides = document.getElementsByClassName("mySlides");
      for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
      }
      slideIndex++;
      if (slideIndex > slides.length) {slideIndex = 1}
      slides[slideIndex-1].style.display = "block";
      setTimeout(showSlides, 3000); // Change image every 3 seconds
    }
    function plusSlides(n) {
      slideIndex += n-1;
      showSlides();
    }
  </script>
</body>
</html>
