<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Feona & Beveymae's Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f8f9fa;
      color: #333;
      padding: 0 20px;
    }

    header {
      background-color: #222;
      padding: 15px 0;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      color: #fff;
      font-size: 2rem;
      margin-bottom: 10px;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 30px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-size: 1.1rem;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: #00d1b2;
    }

    section, footer {
      background-color: #fff;
      margin: 30px 0;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #444;
    }

    .blog-posts {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      gap: 30px;
    }

    .post {
      flex: 1 1 300px;
      max-width: 450px;
      padding: 20px;
      border: 1px solid #e0e0e0;
      border-radius: 10px;
      text-align: center;
      background: #fafafa;
    }

    .post img {
      width: 200px;
      height: 200px;
      object-fit: cover;
      border-radius: 50%;
      margin-bottom: 15px;
      border: 3px solid #00d1b2;
    }

    .image-map {
      text-align: center;
    }

    .image-map img {
      width: 300px;
      height: 300px;
      object-fit: cover;
      margin: 10px;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }

    .image-map img:hover {
      transform: scale(1.05);
    }

    footer {
      text-align: center;
      font-size: 0.9rem;
      background-color: #222;
      color: #fff;
      padding: 15px;
      border-radius: 0;
    }

    @media (max-width: 768px) {
      .blog-posts {
        flex-direction: column;
        align-items: center;
      }

      nav ul {
        flex-direction: column;
        gap: 15px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Our Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#Aboutus">About Us</a></li>
        <li><a href="index1.html">Blog</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="Aboutus">
      <h2>About Us</h2>
      <div class="blog-posts">
        <article class="post">
          <img src="feona.jpg" alt="Feona Lovitos">
          <h3>Feona Lovitos</h3>
          <p class="date">March 17, 2025</p>
          <p>Hello! I’m Feona Lovitos, an IT student passionate about technology and problem-solving.
          My journey in IT has allowed me to explore various areas like software development, web design, and data analysis.</p>
        </article>
        <article class="post">
          <img src="mina.jpg" alt="Beveymae Mina">
          <h3>Beveymae Mina</h3>
          <p class="date">March 17, 2025</p>
          <p>I’m Beveymae Mina, an IT student with a strong interest in technology and innovation.
          I'm passionate about learning new programming languages, building software, and solving complex problems.
          I've worked on projects that helped me develop my skills in coding, databases, and system administration.</p>
        </article>
      </div>
    </section>

    <section class="image-map">
      <h2>Explore More</h2>
      <a href="https://www.facebook.com/CEC1915EASTERNIANS/">
        <img src="CEC.png" alt="CEC Logo">
      </a>
      <a href="https://www.facebook.com/CEC1915EASTERNIANS/">
        <img src="CEC1.jpg" alt="CEC Campus">
      </a>
    </section>

    <section class="image-map" id="contact">
      <h2>Contact Us</h2>
      <p><strong>Facebook:</strong> Feona Lovitos | Beveymae Mina</p>
      <p><strong>Instagram:</strong> @f-nx_l | @beveymae</p>
      <p><strong>Email:</strong> feonalovitos123@gmail.com | BeveymaeMina@gmail.com</p>
      <p><strong>Contact #:</strong> 09297813747 | 09125789542</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Feona Lovitos | Beveymae Mina | BSIT 1 SEC 4</p>
  </footer>

</body>
</html>
