<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
      color: #004aad;
      border-left: 6px solid #ffcc00;
      padding-left: 12px;
      margin-bottom: 15px;
      font-size: 1.4rem;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }
    /* ===== GALLERY ===== */
    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
      gap: 15px;
      margin-top: 15px;
    }
    .gallery-grid img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .gallery-grid img:hover { transform: scale(1.05); }
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
    }
  </style>
</head>
<body>

  <header>
    <img src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/logo/logo.png?raw=true">
    <h1>Father Silvio Pre and Primary English Medium School</h1>
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
      <h2>About Our School</h2>
      <p>Father Silvio Pasquali School, located in Mafinga, Iringa Region, Tanzania, continues the legacy of Father Silvio Pasquali — a devoted missionary who believed that true education combines wisdom and service. Our school provides a strong academic foundation and a nurturing environment guided by the values of Love, Joy, and Service.</p>
    </section>
    <section id="academics">
      <h2>Academics</h2>
      <p>We offer a balanced curriculum including English, Mathematics, Science, Social Studies, Kiswahili, and Creative Arts. Our teachers are committed to guiding learners in developing their talents, curiosity, and confidence.</p>
    </section>
    <section id="gallery">
      <h2>Photo Gallery</h2>
      <div class="gallery-grid">
        <img src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/img1.jpg?raw=true">
        <img src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/img3.JPG?raw=true">
        <img src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/img4.jpg?raw=true">
        <img src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/img2.jpg?raw=true">
        <img src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/img9.jpg?raw=true">
        <img src="https://github.com/1FATHER-SILVIO-PASQUALI-SCHOOLS/FATHER-SILVIO-PASQUALI-SCHOOL/blob/main/gallery/images/img7.jpg?raw=true">
      </div>
      <img src="">
      </div>
    </section>
    <section id="contact">
      <h2>Contact Us</h2>
      <p><strong>Address:</strong> Mafinga, Iringa Region, Tanzania</p>
      <p><strong>Phone:</strong> +255 788 890 96</p>
      <p><strong>Email:</strong> frsilviopasquali22@gmail.com</p>
      <p><strong>Working Hours:</strong> Monday – Friday, 8:00 AM –
