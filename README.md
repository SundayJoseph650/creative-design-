# creative-design-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Creative Designer Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0f172a;
      color: white;
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 80px 20px;
      background: linear-gradient(135deg, #1e293b, #334155);
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header p {
      color: #cbd5e1;
      font-size: 1.1rem;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 24px;
      background: #38bdf8;
      color: #000;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }

    .portfolio {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .portfolio h2 {
      text-align: center;
      margin-bottom: 40px;
      font-size: 2rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: #1e293b;
      border-radius: 12px;
      overflow: hidden;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }

    .card-content {
      padding: 15px;
    }

    .card-content h3 {
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      padding: 30px;
      color: #94a3b8;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sunday Joseph</h1>
    <p>Creative Designer | Brand Identity | Social Media Design | UI Inspiration</p>
    <a href="#portfolio" class="btn">View My Work</a>
  </header>

  <section class="portfolio" id="portfolio">
    <h2>My Creative Work</h2>

    <div class="grid">

      <div class="card">
        <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085" alt="Design Work">
        <div class="card-content">
          <h3>Brand Design</h3>
          <p>Modern branding and visual identity concepts for businesses.</p>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3" alt="Creative Work">
        <div class="card-content">
          <h3>Social Media Design</h3>
          <p>Engaging social media creatives designed for audience growth.</p>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1522542550221-31fd19575a2d" alt="UI Design">
        <div class="card-content">
          <h3>Creative Concepts</h3>
          <p>Creative layouts, typography, and modern design direction.</p>
        </div>
      </div>

    </div>
  </section>

  <footer>
    <p>© 2026 Creative Designer Portfolio</p>
  </footer>

</body>
</html>
