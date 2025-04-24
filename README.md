# basketball-site
 my site advocating for load management
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Load Management Advocacy</title>
  <style>
    /* Global Styles */
    body {
      margin: 0;
      font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
      color: #fff;
      background: #121212;
    }
    a {
      text-decoration: none;
      color: inherit;
    }

    /* Header Styles */
    header {
      background: #222;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 1.8em;
      font-weight: bold;
      color: #f57c00; /* basketball orange */
    }
    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
    }
    nav ul li {
      margin-left: 20px;
    }
    nav ul li a {
      color: #ddd;
      font-weight: 600;
      text-transform: uppercase;
    }

    /* Hero Section */
    .hero {
      position: relative;
      /* Use a fallback gradient background so the preview works even if external images are blocked */
      background: linear-gradient(135deg, #ff8f00 0%, #ff6f00 100%);
      height: 60vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    .hero-content {
      position: relative;
      z-index: 1;
    }
    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.1em;
      margin-bottom: 20px;
    }

    /* Button Style */
    .btn {
      padding: 10px 20px;
      background: #f57c00;
      border: none;
      color: #fff;
      font-weight: bold;
      text-transform: uppercase;
      cursor: pointer;
      border-radius: 4px;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background: #e65100;
    }

    /* Content Sections */
    .section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }
    .section h2 {
      text-align: center;
      margin-bottom: 40px;
      font-size: 2.2em;
      color: #f57c00;
    }
    .section .description {
      max-width: 800px;
      margin: 0 auto 40px auto;
      text-align: center;
      color: #ccc;
    }

    /* Videos Section */
    .videos {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .video {
      background: #1c1c1c;
      padding: 20px;
      border-radius: 5px;
      width: 480px;
      box-sizing: border-box;
    }
    .video iframe {
      width: 100%;
      height: 270px;
    }

    /* Blog Section */
    .blog-posts {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .post {
      background: #1c1c1c;
      padding: 20px;
      border-radius: 5px;
      width: 350px;
      box-sizing: border-box;
    }
    .post h3 {
      color: #f57c00;
      margin-top: 0;
    }
    .post p {
      color: #ccc;
    }

    /* Footer Styles */
    footer {
      background: #222;
      color: #aaa;
      padding: 20px;
      text-align: center;
    }
    .social {
      margin-top: 10px;
    }
    .social a {
      margin: 0 10px;
      color: #aaa;
      font-size: 1.2em;
    }

    /* Responsive Adjustments */
    @media (max-width: 768px) {
      .hero {
        height: 50vh;
      }
      .hero h1 {
        font-size: 1.8em;
      }
      .hero p {
        font-size: 0.95em;
      }
      .videos {
        flex-direction: column;
        align-items: center;
      }
      .video {
        width: 100%;
      }
      .blog-posts {
        flex-direction: column;
        align-items: center;
      }
      .post {
        width: 100%;
      }
    }

  </style>
</head>
<body>
  <!-- Header / Navigation -->
  <header>
    <div class="logo">Load Management Advocate</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#videos">Videos</a></li>
        <li><a href="#blog">Blog</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <div class="hero-content">
      <h1>Why the NBA Must Embrace Load Management</h1>
      <p>Championing player health, career longevity, and better basketball</p>
      <a href="#videos" class="btn">Watch the Evidence</a>
    </div>
  </section>

  <!-- Videos Section -->
  <section class="section" id="videos">
    <h2>Video Evidence</h2>
    <div class="description">
      <p>Below are two concise videos explaining the importance of structured rest in today’s NBA. Replace the placeholder IDs with your actual uploads.</p>
    </div>
    <div class="videos">
      <div class="video">
        <h3>Video 1: The Basics of Load Management</h3>
        <!-- Replace VIDEO_ID_1 with your YouTube video ID -->
        <iframe src="https://www.youtube.com/embed/VIDEO_ID_1" title="Load Management Basics" frameborder="0" allowfullscreen></iframe>
      </div>
      <div class="video">
        <h3>Video 2: Advanced Strategies &amp; Data</h3>
        <!-- Replace VIDEO_ID_2 with your YouTube video ID -->
        <iframe src="https://www.youtube.com/embed/VIDEO_ID_2" title="Advanced Load Management" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>
  </section>

  <!-- Blog Section -->
  <section class="section" id="blog">
    <h2>Read the Full Argument</h2>
    <div class="description">
      <p>Dive deeper into the stats, sports‑science research, and policy proposals behind the movement.</p>
    </div>
    <div class="blog-posts">
      <div class="post">
        <h3>The Science of Recovery</h3>
        <p>How modern sports medicine shows that strategic rest reduces injury rates by up to 40%.</p>
        <p><a class="btn" href="#">Read More</a></p>
      </div>
      <div class="post">
        <h3>Fan Perspective: Short‑Term Pain, Long‑Term Gain</h3>
        <p>Why occasional rest nights lead to higher‑quality games and healthier superstars come playoff time.</p>
        <p><a class="btn" href="#">Read More</a></p>
      </div>
      <div class="post">
        <h3>Policy Blueprint for the League</h3>
        <p>Concrete steps the NBA can take to incentivize science‑backed rest periods without hurting ticket sales.</p>
        <p><a class="btn" href="#">Read More</a></p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Load Management Advocate. All rights reserved.</p>
    <div class="social">
      <a href="https://www.youtube.com/channel/yourchannel" target="_blank">YouTube</a>
      <a href="https://www.tiktok.com/@yourprofile" target="_blank">TikTok</a>
    </div>
  </footer>
</body>
</html>
