# photo-gallery
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Photo Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f8f8f8;
      margin: 0;
      padding: 0;
    }
    header {
      background: #333;
      color: #fff;
      padding: 1.5em 0;
      text-align: center;
      font-size: 2em;
      letter-spacing: 2px;
    }
    .container {
      max-width: 900px;
      margin: 2em auto;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.07);
      padding: 2em;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 1.5em;
      margin-top: 1em;
    }
    .gallery-item {
      background: #eee;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.07);
      transition: transform 0.2s;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .gallery-item img {
      width: 100%;
      display: block;
      border-bottom: 1px solid #ddd;
    }
    .caption {
      padding: 0.7em;
      background: #222;
      color: #fff;
      font-size: 1em;
      width: 100%;
      text-align: center;
      border-radius: 0 0 8px 8px;
    }
    @media (max-width: 600px) {
      .container {
        padding: 1em;
      }
      .gallery {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <header>
    Subject Photo Gallery
  </header>
  <div class="container">
    <p style="text-align:center; font-size:1.2em;">
      photo gallery
    </p>
    <div class="gallery">
      <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80" alt="Mountain View">
        <div class="caption">Mountain View</div>
      </div>
      <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1465101046530-73398c7f28ca?auto=format&fit=crop&w=400&q=80" alt="City Lights">
        <div class="caption">City Lights</div>
      </div>
      <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=400&q=80" alt="Forest Morning">
        <div class="caption">Forest Morning</div>
      </div>
      <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1470071459604-3b5ec3a7fe05?auto=format&fit=crop&w=400&q=80" alt="Sunset Over Lake">
        <div class="caption">Sunset Over Lake</div>
      </div>
      <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1441974231531-c6227db76b6e?auto=format&fit=crop&w=400&q=80" alt="Peaceful Forest">
        <div class="caption">Peaceful Forest</div>
      </div>
      <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1506905925346-21bda4d32df4?auto=format&fit=crop&w=400&q=80" alt="Mountain Peak">
        <div class="caption">Mountain Peak</div>
      </div>
      <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1439066615861-d1af74d74000?auto=format&fit=crop&w=400&q=80" alt="Tropical Beach">
        <div class="caption">Tropical Beach</div>
      </div>
      <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1501594907352-04cda38ebc29?auto=format&fit=crop&w=400&q=80" alt="Desert Landscape">
        <div class="caption">Desert Landscape</div>
      </div>
      <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1449824913935-59a10b8d2000?auto=format&fit=crop&w=400&q=80" alt="Autumn Leaves">
        <div class="caption">Autumn Leaves</div>
      </div>
      <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1518837695005-2083093ee35b?auto=format&fit=crop&w=400&q=80" alt="Ocean Waves">
        <div class="caption">Ocean Waves</div>
      </div>
    </div>
  </div>
</body>
</html>
