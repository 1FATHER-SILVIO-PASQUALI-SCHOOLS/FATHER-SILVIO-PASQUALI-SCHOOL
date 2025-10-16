<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Father Silvio Pre and Primary English Medium School</title>
  <style>
    /* ===== RESET & BASE ===== */
    * { box-sizing: border-box; margin: 0; padding: 0; scroll-behavior: smooth; }
    body { font-family: "Segoe UI", Roboto, Arial, sans-serif; color: #222; background: #f5f9ff; line-height: 1.6; }
    img { display: block; max-width: 100%; }
    /* ===== HEADER ===== */
    header {
      text-align: center;
      padding: 30px 20px 15px;
      background: linear-gradient(135deg, #004aad, #0073e6);
      color: #fff;
      border-bottom: 5px solid #003577;
    }
    header img {
      width: 90px;
      height: 90px;
      object-fit: contain;
      border-radius: 50%;
      margin-bottom: 12px;
    }
    header h1 { font-size: 1.8rem; margin-bottom: 6px; font-weight: 700; }
    header p.motto { font-style: italic; font-size: 1rem; color: #f3f7ff; }
    /* ===== HERO ===== */
    .hero {
      background: url('https://images.unsplash.com/photo-1600195077909-46cf9b1b9b7d?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 120px 20px;
      position: relative;
    }
    .hero::before {
      content: "";
      position: absolute;
      inset: 0;
      background: rgba(0, 64, 128, 0.6);
    }
    .hero-content { position: relative; z-index: 2; max-width: 800px; margin: 0 auto; }
    .hero-content h2 { font-size: 2.2rem; margin-bottom: 10px; text-transform: uppercase; letter-spacing: 1px; }
    .hero-content p { font-size: 1.1rem; color: #f0f5ff; }
    /* ===== NAVIGATION ===== */
    nav {
      background: #003577;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    nav ul { list-style: none; display: flex; justify-content: center; flex-wrap: wrap; margin: 0; padding: 0; }
    nav li { margin: 5px 10px; }
    nav a {
      display: block;
      color: #fff;
      text-decoration: none;
      padding: 12px 18px;
      font-weight: 600;
      border-radius: 6px;
      transition: background 0.3s;
    }
    nav a:hover { background: rgba(255,255,255,0.15); }
    /* ===== MAIN ===== */
    main { width: 92%; max-width: 1100px; margin: 50px auto; }
    section {
      background: #fff;
      border-radius: 10px;
      padding: 25px 30px;
      margin-bottom: 35px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.04);
    }
    section h2 {
      color: red;
      border-left: 6px solid #ffcc00;
      padding-left: 12px;
      margin-bottom: 15px;
      font-size: 1.4rem;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }
    section h3 {
      color: red;
      margin-top: 30px;
      font-size: 1.2rem;
      letter-spacing: 0.5px;
      border-left: 4px solid #ffcc00;
      padding-left: 10px;
    }
    /* ===== GALLERY SLIDESHOW ===== */
    .slideshow-container {
      position: relative;
      max-width: 700px;
      margin: auto;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
    }
    .slides {
      display: none;
      width: 100%;
      height: 400px;
      object-fit: cover;
      border-radius: 10px;
    }
    /* Next & previous buttons */
    .prev, .next {
      cursor: pointer;
      position: absolute;
      top: 50%;
      width: auto;
      margin-top: -22px;
      padding: 16px;
      color: white;
      font-weight: bold;
      font-size: 18px;
      border-radius: 0 3px 3px 0;
      user-select: none;
      background-color: rgba(0,0,0,0.5);
      transition: background-color 0.3s;
    }
    .next {
      right: 0;
      border-radius: 3px 0 0 3px;
    }
    .prev:hover, .next:hover {
      background-color: rgba(0,0,0,0.8);
    }
    /* Caption text */
    .caption {
      text-align: center;
      padding: 8px 12px;
      color: #333;
      font-weight: 600;
      font-size: 1rem;
    }
    /* ===== FOOTER ===== */
    footer {
      background: #003577;
      color: #fff;
      text-align: center;
      padding: 25px 15px;
      font-size: 0.9rem;
      margin-top: 50px;
    }
    footer p { margin: 5px 0; opacity: 0.9; }
    /* ===== RESPONSIVE ===== */
    @media (max-width: 700px) {
      header h1 { font-size: 1.4rem; }
      .hero-content h2 { font-size: 1.5rem; }
      section { padding: 20px; }
      nav ul { flex-direction: column; align-items: center; }
      nav a { padding: 10px 12px; }
      .slides {
        height: 250px;
      }
    }
  </style>
</head>
<body>

<header>
  <img src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/logo.jpg?raw=true" alt="School Logo" />
  <h1>FATHER SILVIO PASQUALI PRE AND PRIMARY ENGLISH MEDIUM SCHOOL</h1>
  <p class="motto">Love • Joy • Service</p>
</header>

<div class="hero" id="home">
  <div class="hero-content">
    <h2>Welcome to Father Silvio School</h2>
    <p>Where knowledge, discipline, and service build the leaders of tomorrow.</p>
  </div>
</div>

<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About Us</a></li>
    <li><a href="#academics">Academics</a></li>
    <li><a href="#gallery">Gallery</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<main>
  <section id="about">
    <h2>ABOUT OUR SCHOOL</h2>
    <h3>WHO WE ARE</h3>
    <p>Father Silvio Pasquali School, located in Mafinga, Iringa Region, Tanzania, continues the legacy of Father Silvio Pasquali — a devoted missionary who believed that true education combines wisdom and service. Our school provides a strong academic foundation and a nurturing environment guided by the values of Love, Joy, and Service. The school is on spacious compound and affords beautiful scenery of the green countryside. The location is served by electricity, clean piped water internet access and cellular services. We welcome parents and students to visit our school and talk to our Management and committed Staff. Also to observe our cool beautiful environment that make Fr. Silvio school of its own kind.</p>
    <h3>OUR VISION AND MISSION</h3>
    <p>Fr. Silvio Pasquali Pre & Primary School is committed to helping all students realize their full potential, to build a strong nation of intellectuals with moral strength and social responsibility through holistic education. We endeavor to provide a healthy atmosphere for mental, social, emotional and spiritual development. We also aim at enhancing a sense of morality, social obligations and responsibilities. The statement of our mission comes from Our school motto: “Love, Joy and Service.” This commits us to model and nurture qualities such as patriotism, curiosity, honesty, adaptability, sense of hard work, resourcefulness, creativity, hope, justice and self-discipline; which will adequately prepare younger to cope with the challenges of a rapidly changing world.</p>
    <h3>HEALTH AND MEDICAL WELFARE</h3>
    <p>The health and general welfare of our students has always been given the highest and special priority at all times. We have a qualified nurse within the school who will offer first aid to sick students before they are taken to hospital for check-up and treatment.</p>
    <h3>MANAGEMENT</h3>
    <p>Fr. Silvio Pasquali Pre & Primary school is a catholic institution established in the year 2013 and administered by the congregation of Catechist Sisters of St. Ann. The school has a team of committed, dynamic, efficient and qualified teachers, who lay strong foundation for a strong Nation. Besides academic excellence, the school gives importance to discipline and character and caters to the all development of the students in all aspects of life.</p>
  </section>

  <section id="academics">
    <h2>ACADEMICS</h2>
    <p>We offer a balanced curriculum including English, Mathematics, Science, Social Studies, Kiswahili, and Creative Arts. Our teachers are committed to guiding learners in developing their talents, curiosity, and confidence.</p>
  </section>

  <section id="gallery">
    <h2>Photo Gallery</h2>
    <h3>Sports and Games</h3>
    <div class="slideshow-container" id="sports-slideshow">
      <img class="slides" src="gallery/sports-and-games/sports1.jpg" alt="Sports 1" />
      <img class="slides" src="gallery/sports-and-games/sports2.jpg" alt="Sports 2" />
      <!-- Add more sport images as necessary -->
      <a class="prev" onclick="plusSlides('sports', -1)">&#10094;</a>
      <a class="next" onclick="plusSlides('sports', 1)">&#10095;</a>
      <div class="caption">Sports and Games Gallery</div>
    </div>
    <h3>Academic Gallery</h3>
    <div class="slideshow-container" id="academic-slideshow">
      <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/2023-03-10%2020230309_132711.jpg?raw=true" alt="Academic 1" />
      <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/D.jpg?raw=true" alt="Academic 2" />
        <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/IMG-20231015-WA0004.jpg?raw=true" alt="Academic 2" />
        <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/IMG-20231015-WA0005.jpg?raw=true" alt="Academic 2" />
      <!-- Add more academic images as necessary -->
      <a class="prev" onclick="plusSlides('academic', -1)">&#10094;</a>
      <a class="next" onclick="plusSlides('academic', 1)">&#10095;</a>
      <div class="caption">Academic Gallery</div>
    </div>
    <h3>Study Tour Gallery</h3>
    <div class="slideshow-container" id="study-tour-slideshow">
      <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/K.jpg?raw=true" alt="Study Tour 1" />
      <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/L.jpg?raw=true" alt="Study Tour 2" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/w.jpg?raw=true" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/580A0802.jpg?raw=true" alt="Study Tour 2" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/st.jpg?raw=true" alt="Study Tour 2" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/s4.jpg?raw=true" alt="Study Tour 2" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/N.jpg?raw=true" alt="Study Tour 2" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/M.jpg?raw=true" alt="Study Tour 2" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/J.jpg?raw=true" alt="Study Tour 2" />
      <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/I.jpg?raw=true" />
      <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/A.jpg?raw=true" alt="Study Tour 2" />
      <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/B.jpg?raw=true" alt="Study Tour 2" />
      <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/C.jpg?raw=true" alt="Study Tour2" />
      <!-- Add more study tour images as necessary -->
      <a class="prev" onclick="plusSlides('studyTour', -1)">&#10094;</a>
      <a class="next" onclick="plusSlides('studyTour', 1)">&#10095;</a>
      <div class="caption">Study Tour Gallery</div>
    </div>
    <h3>Celebrations</h3>
   <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/20250913_115515.jpg?raw=true" alt="Charity 1" />
      <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/20250913_123057.jpg?raw=true" alt="Charity 2" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/580A0802.jpg?raw=true" alt="Charity 2" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/IMG_20250725_125334_1.jpg?raw=true" alt="Charity 2" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/IMG_20250725_125443_1.jpg?raw=true" alt="Charity 2" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/DSC_0199.jpg?raw=true" alt="Charity 2" />
       <img class="slides" src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/DSC_0170.jpg?raw=true" alt="Charity 2" />
     <h3>charity</h3>
    <div class="slideshow-container" id="charity-slideshow">
      <img class="slides" src="gallery/charity-celebrations/charity1.jpg" alt="Charity 1" />
      <img class="slides" src="gallery/charity-celebrations/charity2.jpg" alt="Charity 2" />
      <!-- Add more charity images -->
      <a class="prev" onclick="plusSlides('charity', -1)">&#10094;</a>
      <a class="next" onclick="plusSlides('charity', 1)">&#10095;</a>
      <div class="caption">Charity Celebrations Gallery</div>
    </div>
    <h3>Seminary Gallery</h3>
    <div class="slideshow-container" id="seminary-slideshow">
      <img class="slides" src="gallery/seminary/seminary1.jpg" alt="Seminary 1" />
      <img class="slides" src="gallery/seminary/seminary2.jpg" alt="Seminary 2" />
      <!-- Add more seminary images -->
      <a class="prev" onclick="plusSlides('seminary', -1)">&#10094;</a>
      <a class="next" onclick="plusSlides('seminary', 1)">&#10095;</a>
      <div class="caption">Seminary Gallery</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Address:</strong> Mafinga, Iringa Region, Tanzania</p>
    <p><strong>Phone:</strong> +255 788 890 96</p>
    <p><strong>Email:</strong> frsilviopasquali22@gmail.com</p>
    <p><strong>Working Hours:</strong> Monday – Friday, 8:00 AM –</p>
  </section>
</main>

<footer>
  <p>© 2025 Father Silvio Pre and Primary English Medium School. All rights reserved.</p>
</footer>

<script>
  const slideIndices = {
    sports: 1,
    academic: 1,
    studyTour: 1,
    charity: 1,
    seminary: 1
  };

  function showSlides(galleryName) {
    const slides = document.querySelectorAll(`#${galleryName}-slideshow .slides`);
    if (slides.length === 0) return;
    let n = slideIndices[galleryName];
    if (n > slides.length) slideIndices[galleryName] = 1;
    if (n < 1) slideIndices[galleryName] = slides.length;

    slides.forEach(slide => slide.style.display = "none");
    slides[slideIndices[galleryName] - 1].style.display = "block";
  }

  function plusSlides(galleryName, n) {
    slideIndices[galleryName] += n;
    showSlides(galleryName);
  }

  // Initialize all galleries to show their first slide
  Object.keys(slideIndices).forEach(name => showSlides(name));

  // Automatically change slides every 5 seconds
  setInterval(() => {
    Object.keys(slideIndices).forEach(name => {
      plusSlides(name, 1);
    });
  }, 5000);
</script>

</body>
</html>
