<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Refani Aulia - Portofolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f7f9fc;
      color: #2c3e50;
      line-height: 1.6;
    }
    .landing {
      position: relative;
      height: 100vh;
      background: #34495e; /* Warna biru gelap */
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
    }
    .landing img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid white;
      margin-bottom: 20px;
    }
    .landing h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
      color: #f8f9fa;
    }
    .landing p {
      font-size: 1.2em;
      color: #e0f7fa;
      margin-bottom: 20px;
    }
    .landing a {
      display: inline-block;
      padding: 10px 20px;
      font-size: 1em;
      color: #2c3e50;
      background: #ffffff;
      text-decoration: none;
      border-radius: 25px;
      transition: background 0.3s, color 0.3s;
    }
    .landing a:hover {
      background: #c2e9fb;
      color: #2c3e50;
    }
    .sidebar {
      position: fixed;
      top: 0;
      left: 0;
      width: 200px;
      height: 100%;
      background-color: #34495e;
      color: white;
      padding: 20px;
      box-shadow: 2px 0 5px rgba(0, 0, 0, 0.1);
    }
    .sidebar h2 {
      font-size: 1.2em;
      margin-bottom: 20px;
      text-align: center;
    }
    .sidebar ul {
      list-style-type: none;
      padding: 0;
    }
    .sidebar ul li {
      margin: 15px 0;
    }
    .sidebar ul li a {
      color: white;
      text-decoration: none;
      padding: 10px;
      display: block;
      border-radius: 25px;
      transition: background 0.3s;
    }
    .sidebar ul li a:hover {
      background-color: #1abc9c;
    }
    .content {
      margin-left: 220px;
      padding: 20px;
    }
    .section {
      margin-bottom: 20px;
      border-radius: 10px;
      background: #dfe6e9;
      color: #2c3e50;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
    .section h2 {
      margin-bottom: 10px;
      font-size: 1.8em;
      color: #34495e;
    }
    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .skill-box {
      background-color: #eafaf1;
      color: #34495e;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    .skill-box i {
      font-size: 2.5em;
      color: #2c3e50;
      margin-bottom: 10px;
    }
    .contact ul {
      list-style-type: none;
      padding: 0;
    }
    .contact ul li {
      margin-bottom: 15px;
      display: flex;
      align-items: center;
      font-size: 1em;
    }
    .contact ul li i {
      margin-right: 10px;
      font-size: 1.5em;
      color: #3498db;
    }
    .contact ul li a {
      color: #3498db;
      text-decoration: none;
    }
    .contact ul li a:hover {
      text-decoration: underline;
    }
    .data-diri {
      display: flex;
      flex-direction: column;
      gap: 10px;
      background-color: #dfe6e9; /* Warna abu-abu */
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      margin-top: 20px;
    }
    @media (max-width: 768px) {
      .sidebar {
        width: 100%;
        height: auto;
        position: relative;
      }
      .content {
        margin-left: 0;
      }
      .landing {
        height: auto;
        padding: 40px 20px;
      }
    }
  </style>
</head>
<body>
  <div id="landing" class="landing">
    <div>
      <img src="foto-profil.jpg (2).jpeg" alt="Refani Aulia" />
      <h1 style="font-size: 2em; font-weight: 600; color: #ffffff;">Hello, It's Me</h1>
      <h2 style="font-size: 4em; font-family: 'Poppins', sans-serif; font-weight: 900; color: #f2f7f6; text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);">
        Refani Aulia
      </h2>
      <p style="font-size: 1.5em; color: #e0f7fa;">And I am an information systems student</p>
      <a href="#about" style="background-color: #030303; color: #ffffff; padding: 10px 20px; font-size: 1.2em; text-decoration: none; border-radius: 25px; transition: background 0.3s;">
        More About Me
      </a>
    </div>
  </div>
  <div class="sidebar">
    <h2></h2>
    <ul>
      <li><a href="#landing">Home</a></li>
      <li><a href="#about">About me</a></li>
      <li><a href="#personal data">Personal data</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </div>
  <div class="content">
    <div id="about" class="section">
      <h2>Tentang Saya</h2>
      <p style="margin-top: 20px; font-size: 1.2em; line-height: 1.8; color: #34495e;">
        Saya adalah seorang pemula yang sedang mempelajari UI/UX Design dan saya tertarik dalam mempelajari bagaimana cara membuat situs web yang responsif dan menarik. Saya percaya bahwa teknologi dan seni dapat menghadirkan pengalaman pengguna yang mengesankan.
      </p>
    </div>
    <div id="personal data" class="section data-diri">
      <h2>Data Diri</h2>
      <p><strong>Nama:</strong> Refani Aulia</p>
      <p><strong>Tempat, Tanggal Lahir:</strong> Padang Brahrang, 15 September 2005</p>
      <p><strong>Alamat:</strong> Padang Brahrang, Cinta Dapat Dusun Tanjung</p>
      <p><strong>Hobi:</strong></p>
      <div>
        Hiking<br>
        Watching Movies<br>
        Gaming
      </div>
    </div>
    <div id="skills" class="section">
      <h2>Skill</h2>
      <div class="skills">
        <div class="skill-box">
          <i class="fas fa-camera-retro"></i>
          <h3>Photography</h3>
          <p>Photography</p>
        </div>
        <div class="skill-box">
          <i class="fas fa-pen-nib"></i>
          <h3>Editing</h3>
          <p>Adobe Lightroom</p>
        </div>
        <div class="skill-box">
          <i class="fas fa-cube"></i>
          <h3>3D Modeling</h3>
          <p>Blender</p>
        </div>
        <div class="skill-box">
          <i class="fas fa-database"></i>
          <h3>Database</h3>
          <p>PHPMyAdmin</p>
        </div>
      </div>
    </div>
    <div id="contact" class="section contact">
      <h2>Kontak</h2>
      <ul>
        <li><i class="fas fa-envelope"></i> <a href="mailto:refaniaulia03@gmail.com">refaniaulia03@gmail.com</a></li>
        <li><i class="fab fa-instagram"></i> <a href="https://www.instagram.com/rfniaull_" target="_blank">@rfniaull</a></li>
        <li><i class="fab fa-github"></i> <a href="https://github.com/refaniaulia" target="_blank">github.com/refaniaulia</a></li>
        <li><i class="fab fa-whatsapp"></i> <a href="https://wa.me/081376850139" target="_blank">081376850139</a></li>
      </ul>
    </div>
  </div>
</body>
</html>
