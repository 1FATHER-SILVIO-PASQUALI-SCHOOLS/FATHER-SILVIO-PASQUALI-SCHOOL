<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FATHER SILVIO PRE AND PRIMARY ENGLISH MEDIUM SCHOOL</title>
  <style>
    /* ====== STYLES (Combined CSS) ====== */
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html,body { height: 100%; font-family: "Segoe UI", Roboto, Arial, sans-serif; color: #222; background: #f8fbff; line-height: 1.5; }
    .container { width: 92%; max-width: 1100px; margin: 0 auto; }
    .site-header { background: linear-gradient(180deg,#0057b8 0%,#004aad 100%); color: #fff; padding: 26px 0; box-shadow: 0 2px 8px rgba(0,0,0,.06); text-align: center; }
    .site-header h1 { font-size: 1.5rem; letter-spacing: 0.5px; }
    .motto { margin-top: 8px; font-style: italic; opacity: 0.9; }

    .site-nav { background: #003577; position: sticky; top: 0; z-index: 100; }
    .site-nav ul { list-style: none; display: flex; justify-content: center; flex-wrap: wrap; }
    .site-nav li { margin: 5px 10px; }
    .site-nav a { color: white; text-decoration: none; padding: 10px 14px; border-radius: 6px; font-weight: 600; }
    .site-nav a:hover { background: rgba(255,255,255,0.1); }

    main { padding: 30px 0; }
    section { background: white; border-radius: 8px; padding: 20px; margin-bottom: 25px; box-shadow: 0 6px 18px rgba(3, 26, 78, 0.04); }
    section h2 { color: #004aad; border-bottom: 3px solid rgba(0,74,173,0.08); padding-bottom: 6px; margin-bottom: 10px; }

    /* Gallery */
    .gallery-grid { display: grid; grid-template-columns: repeat(auto-fit,minmax(250px,1fr)); gap: 12px; margin-top: 15px; }
    .gallery-item img { width: 100%; height: 180px; object-fit: cover; border-radius: 6px; transition: transform 0.25s ease; }
    .gallery-item img:hover { transform: scale(1.04); }

    /* Footer */
    .site-footer { background: #f4f6fb; color: #333; text-align: center; padding: 25px 0; border-top: 1px solid #e6eefc; margin-top: 40px; }

    @media(max-width:700px){ .site-nav ul{flex-direction:column;align-items:center;} }
  </style>
</head>

<body>
  <header class="site-header">
    <h1>FATHER SILVIO PRE AND PRIMARY ENGLISH MEDIUM SCHOOL</h1>
    <p class="motto">Love • Joy • Service</p>
  </header>

  <nav class="site-nav">
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#academics">Academics</a></li>
      <li><a href="#gallery">Gallery</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <main class="container">
    <section id="home">
      <h2>Welcome Message</h2>
      <p>
        Welcome to <strong>Father Silvio Pre and Primary English Medium School</strong>,
        where education meets excellence and moral growth. We are dedicated to nurturing pupils with knowledge,
        discipline, and faith to prepare them for a bright future.
      </p>
    </section>

    <section id="about">
      <h2>About Our School</h2>
      <p>
        Father Silvio Pasquali School, located in Mafinga, Iringa Region, Tanzania, continues the legacy of
        Father Silvio Pasquali — a devoted missionary who believed that true education combines wisdom and service.
        Our school provides a strong academic foundation and a nurturing environment guided by the values of Love, Joy, and Service.
      </p>
    </section>

    <section id="academics">
      <h2>Academics</h2>
      <p>
        We offer a balanced curriculum including English, Mathematics, Science, Social Studies, Kiswahili,
        and Creative Arts. Our teachers are committed to guiding learners in developing their talents,
        curiosity, and confidence.
      </p>
    </section>

    <section id="gallery">
      <h2>Photo Gallery</h2>
      <div class="gallery-grid">
        <!-- Replace the sample image paths below with your actual uploaded images -->
        <div class="gallery-item"><img src="images/gallery/img1.jpg" alt="School view"></div>
        <div class="gallery-item"><img src="images/gallery/img2.jpg" alt="Pupils in class"></div>
        <div class="gallery-item"><img src="images/gallery/img3.jpg" alt="Playground"></div>
        <div class="gallery-item"><img src="images/gallery/img4.jpg" alt="Teachers and students"></div>
        <div class="gallery-item"><img src="images/gallery/img5.jpg" alt="Science class"></div>
        <div class="gallery-item"><img src="images/gallery/img6.jpg" alt="Library"></div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p><strong>Address:</strong> Mafinga, Iringa Region, Tanzania</p>
      <p><strong>Phone:</strong> +255 788 890 96</p>
      <p><strong>Email:</strong> frsilviopasquali22@gmail.com</p>
      <p><strong>Working Hours:</strong> Monday – Friday, 8:00 AM – 4:00 PM</p>
    </section>
  </main>

  <footer class="site-footer">
    <p>© 2025 Father Silvio Pre and Primary English Medium School. All rights reserved.</p>
    <p>Designed with ❤️ by the Father Silvio School Team</p>
  </footer>
</body>
</html>
