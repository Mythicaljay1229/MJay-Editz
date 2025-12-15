<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-N33W40SVZT');
</script>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="MJay Editz.">
  <meta name="keywords" content="videos">

  <title>MJay Editz - Video Showcase</title>
  <style>
    body { font-family: Arial, sans-serif; background: #111; color: #eee; margin: 0; }
    header { background: #222; padding: 20px; text-align: center; }
    header h1 { margin: 0; color: #6ea8ff; }
    nav a { color: #eee; margin: 0 10px; text-decoration: none; }
    nav a:hover { color: #6ea8ff; }
    .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 20px; padding: 20px; }
    .card { background: #1a1a1a; border-radius: 8px; overflow: hidden; box-shadow: 0 0 10px rgba(0,0,0,0.5); }
    .card video { width: 100%; display: block; }
    .card-body { padding: 10px; }
    .card-body h3 { margin: 0; color: #6ea8ff; }
    .actions { display: flex; gap: 10px; margin-top: 8px; }
    .btn { padding: 6px 10px; border: 1px solid #444; border-radius: 6px; cursor: pointer; background: transparent; color: #eee; }
    .btn:hover { border-color: #6ea8ff; color: #6ea8ff; }
    .stats { font-size: 13px; color: #aaa; margin-top: 6px; }
    .comments { margin-top: 10px; }
    .comment { background: #222; padding: 6px; border-radius: 6px; margin-bottom: 6px; font-size: 13px; }
    .comment-form { margin-top: 8px; display: flex; flex-direction: column; gap: 6px; }
    .comment-form input, .comment-form textarea { padding: 6px; border-radius: 6px; border: 1px solid #444; background: #111; color: #eee; }
    .comment-form button { align-self: flex-start; }
    footer { background: #222; text-align: center; padding: 15px; margin-top: 20px; font-size: 14px; color: #aaa; }
  </style>
</head>
<body>
  <header>
    <h1>MJay Editz</h1>
    <nav>
      <a href="#gallery">Videos</a>
      <a href="https://wa.me/08030471077?">Contact</a>
       <a href="#leaderboard">Leaderboard</a>
    </nav>
  </header>

<button onclick="toggleTheme()">🌙 Toggle Theme</button>

<style>
  body.light { background: #f4f4f4; color: #000; }
  body.dark { background: #121212; color: #fff; }
  .leaderboard { transition: background 0.3s, color 0.3s; }
</style>

<script>
  function toggleTheme() {
    document.body.classList.toggle("dark");
    document.body.classList.toggle("light");
  }
  // Default theme
  document.body.classList.add("light");
</script>

  
  <section id="gallery" class="gallery">
    <!-- Video Card -->
    <div class="card" data-id="video1">
      <video controls>
        <source src="videos/edit1.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h3>houston rockets edit</h3>
<p>by mjay</p>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
    </div>

    <!-- Another Video Card -->
    <div class="card" data-id="video2">
      <video controls>
        <source src="videos/tonyparkeredit.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h3>Tony parker Edit</h3>
        <p>by mjay</p>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
    </div>
  </section>

<!-- Another Video Card -->
    <div class="card" data-id="video2">
      <video controls>
        <source src="videos/edit2.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h4>nba players</h4>
<p>by posher</p>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
    </div>
  </section>

<!-- Another Video Card -->
    <div class="card" data-id="video2">
      <video controls>
        <source src="videos/dunk1.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h5>nba2k20 dunks</h5>
<p>by k4mbingggmeh</p>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
    </div>
  </section>


<!-- Another Video Card -->
    <div class="card" data-id="video2">
      <video controls>
        <source src="videos/dunk2.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h6>nba2k20 dunks</h6>
<p>by unclej064</p>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
    </div>
  </section>

<!-- Another Video Card -->
    <div class="card" data-id="video2">
      <video controls>
        <source src="videos/edit3.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h7>kuroku no basket</h7>
<p>by Imani</p>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
    </div>
  </section>

  
    <!-- Another Video Card -->
    <div class="card" data-id="video2">
      <video controls>
        <source src="videos/1.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h9>Minecraft</h9>
        <p>by posher</p>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
    </div>
  </section>

  
<!-- Another Video Card -->
    <div class="card" data-id="video2">
      <video controls>
        <source src="videos/edit4.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h8>stephen curry</h8>
<p>by MJay</p>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
        </form>
    </div>
  </section>

   <!-- Video Card -->
    <div class="card" data-id="video1">
      <video controls>
        <source src="videos/2.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h9>Minecraft</h9>
<p>by posher</p>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
    </div>

   <!-- Video Card -->
    <div class="card" data-id="video1">
      <video controls>
        <source src="videos/3.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h10>LeBron James</h10>
<p>by posher</p>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
    </div>

  
    <!-- Another Video Card -->
    <div class="card" data-id="video2">
      <video controls>
        <source src="videos/5.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h3>facts</h3>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
    </div>
  </section>

  
    <!-- Another Video Card -->
    <div class="card" data-id="video2">
      <video controls>
        <source src="videos/6.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h3>Facts</h3>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>

 <!-- Another Video Card -->
    <div class="card" data-id="video2">
      <video controls>
        <source src="videos/7.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="card-body">
        <h3>Mythicaljay</h3>
        <p>by mjay</p>
        <div class="actions">
          <button class="btn like-btn">👍 Like</button>
        </div>
        <div class="share-buttons">
  <!-- Twitter -->
  <a href="https://twitter.com/intent/tweet?url=https://mythicaljay1229.github.io/MJay-Editz&text=Check+out+this+edit!" target="_blank" class="share-btn twitter">
    Twitter
  </a>

  <!-- Facebook -->
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn facebook">
    Facebook
  </a>

  <!-- WhatsApp -->
  <a href="https://api.whatsapp.com/send?text=Check+out+this+edit! https://mythicaljay1229.github.io/MJay-Editz" target="_blank" class="share-btn whatsapp">
    WhatsApp
  </a>
</div>

<style>
.share-buttons {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.share-btn {
  padding: 10px 15px;
  border-radius: 5px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.share-btn.twitter { background: #1DA1F2; }
.share-btn.facebook { background: #4267B2; }
.share-btn.whatsapp { background: #25D366; }
</style>
        <div class="stats">
          <span class="likes">0 Likes</span> • 
          <span class="views">0 Views</span>
        </div>
    </div>
  </section>

          
        </div> <script src="https://giscus.app/client.js"
        data-repo="Mythicaljay1229/MJay-Editz"
        data-repo-id="R_kgDOQja4Og"
        data-category="General"
        data-category-id="DIC_kwDOQja4Os4CzyIx"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="bottom"
        data-theme="preferred_color_scheme"
        data-lang="en"
        crossorigin="anonymous"
        async>
</script>
    </div>
  </section>

 <section id="leaderboard">
    <div class="leaderboard">
      <h11>🏆 Most Visits Leaderboard countries</h11>
      <ol id="leaderboard-list">
        <!-- Dynamic data will be injected here -->
      </ol>
    </div>
 </section>

  <script>
    // Example static data (replace with real analytics later)
    const leaderboardData = [
      { username: "🥇 Nigeria", visits:   22 },
      { username: "🥈 USA", visits:   2 },
      { username: "🥉 Israel", visits:   1 },
      { username: "Russia", visits:  1 },
     

    ];

    const list = document.getElementById("leaderboard-list");
    leaderboardData.forEach(user => {
      const li = document.createElement("li");
      li.innerHTML = `<span>${user.username}</span><span>${user.visits} visits</span>`;
      list.appendChild(li);
    });
  </script>

<div class="progress-container">
  <div class="progress-bar" id="progress-bar">0%</div>
</div>

<script>
  const currentVisits = 42;  // replace with your actual visits
  const goal = 100;
  const target = Math.min((currentVisits / goal) * 100, 100);

  let width = 0;
  const bar = document.getElementById("progress-bar");
  const interval = setInterval(() => {
    if (width >= target) {
      clearInterval(interval);
    } else {
      width++;
      bar.style.width = width + "%";
      bar.textContent = width + "%";
    }
  }, 30); // speed of animation
</script>

  
  <footer>
    © 2025 Rocketstar3 — All rights reserved.
  </footer>

  <script>
    // Local storage for likes, views
    const data = JSON.parse(localStorage.getItem("mjayData") || "{}");

    document.querySelectorAll(".card").forEach(card => {
      const id = card.dataset.id;
      if (!data[id]) data[id] = { likes: 0, views: 0  };

      const likesEl = card.querySelector(".likes");
      const viewsEl = card.querySelector(".views");

      // Update UI
      function update() {
        likesEl.textContent = data[id].likes + " Likes";
        viewsEl.textContent = data[id].views + " Views";
        commentsEl.innerHTML = "";
        data[id].comments.forEach(c => {
          const div = document.createElement("div");
          div.className = "comment";
          div.innerHTML = `<strong>${c.name}</strong>: ${c.text}`;
          commentsEl.appendChild(div);
        });
        localStorage.setItem("mjayData", JSON.stringify(data));
      }
      update();

      // Like button
      card.querySelector(".like-btn").addEventListener("click", () => {
        data[id].likes++;
        update();
      });

      // View counter
      card.querySelector("video").addEventListener("play", () => {
        data[id].views++;
        update();
      });
    });
  </script>
</body>
</html>

































