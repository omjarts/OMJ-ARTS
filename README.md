<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>OMJ ARTS</title>

  <!-- Lightbox2 CSS -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.5/css/lightbox.min.css" />

  <!-- Custom CSS -->
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }

    main {
      padding: 2rem;
    }

    h1, h2 {
      text-align: center;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 15px;
      padding: 20px 0;
    }

    .gallery-grid a {
      text-align: center;
      text-decoration: none;
      color: inherit;
    }

    .gallery-grid img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      transition: transform 0.2s ease;
    }

    .gallery-grid img:hover {
      transform: scale(1.05);
    }

    .caption {
      margin-top: 8px;
      font-size: 0.9rem;
    }

    @media (max-width: 768px) {
      .gallery-grid {
        grid-template-columns: repeat(2, 1fr);
      }
    }

    @media (max-width: 480px) {
      .gallery-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>OMJ ARTS</h1>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>
        I am a London based Nigerian artist whose work is deeply rooted in the beauty, resilience, and richness of African culture and heritage. My journey into painting began as a personal escape, a hobby that brought me joy and solace. But in 2020, when I was laid off during the COVID-19 pandemic, art became my full-time passion, transforming my life in ways I never anticipated.
      </p>
      <p>
        Five years in, I have exhibited my work extensively across the UK, sharing visual narratives that celebrate identity, tradition, and the stories of my people. My paintings, often created with oil on linen, blend portraiture and abstraction, capturing the spirit of African heritage with expressive textures and bold colors. I use an underpainting technique with white oil to bring depth and light to my compositions.
      </p>
      <p>
        Beyond exhibitions, I am committed to using art as a tool for cultural preservation and dialogue. Through my work, I hope to inspire conversations, bridge histories, and connect people to the richness of African traditions. I continue to refine my craft, drawing inspiration from workshops, exhibitions, and the encouragement of fellow artists like Gabriel, whose support marked a turning point in my artistic journey.
      </p>
      <p>
        This is more than just art for me, it is a mission to honor the past, celebrate the present, and shape the future through creativity.
      </p>
    </section>

    <section id="gallery">
      <h2>Gallery</h2>
      <div class="gallery-grid">
        <!-- Example Images -->
        <a href="images/art1.jpg" data-lightbox="art-gallery" data-title="Title of Art 1">
          <img src="images/art1.jpg" alt="Art 1" />
          <p class="caption">Title of Art 1</p>
        </a>

        <a href="images/art2.jpg" data-lightbox="art-gallery" data-title="Title of Art 2">
          <img src="images/art2.jpg" alt="Art 2" />
          <p class="caption">Title of Art 2</p>
        </a>

        <!-- Add more images as needed -->
      </div>
    </section>
  </main>

  <!-- Lightbox2 JS -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.5/js/lightbox.min.js"></script>
</body>
</html>
