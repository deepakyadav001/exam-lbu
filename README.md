# exam-lbu
html code
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ratventures — Nibbles and Lurks</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <img src="logo.svg" alt="Ratventures logo" class="logo">
      <nav class="site-nav" aria-label="Main navigation">
        <a href="#ratventures">Ratventures</a>
        <a href="#nibbles">Nibbles & Lurks</a>
        <a href="#contact">Contact Us</a>
      </nav>
    </div>
    <div class="hero container">
      <h1>Talk Rat Talk</h1>
      <p class="lead">Rattus Adventures — Nibbles and Lurks — Tail End Stories — Cat Napped</p>
    </div>
  </header>

  <main class="container">
    <section class="intro">
      <h2>Head of the Gang</h2>
      <h3>Rats dig life, but they dig each other too!</h3>
      <p>Social life is the best life for us Rats!</p>
    </section>

    <section id="cards" class="grid">
      <!-- Card: Rattus Adventures -->
      <article class="card" id="ratventures">
        <img src="rat1.png" alt="Rats exploring tunnels" class="card-img">
        <div class="card-body">
          <h3>Rattus Adventures</h3>
          <p>Exploring tunnels and climbing obstacles. Team adventures and playful bonding. Discovering new hiding places and treasures.</p>
          <a class="btn" href="#">Read more</a>
        </div>
      </article>

      <!-- Card: Nibbles and Lurks -->
      <article class="card" id="nibbles">
        <img src="rat2.png" alt="Snack time" class="card-img">
        <div class="card-body">
          <h3>Nibbles and Lurks</h3>
          <p>Creative recipes for nibble-worthy snacks: cheese platter perfection and healthy treats — best munchies for late-night exploring.</p>
          <a class="btn" href="#">Recipes</a>
        </div>
      </article>

      <!-- Card: Tail End Stories -->
      <article class="card">
        <img src="rat3.png" alt="Story time" class="card-img">
        <div class="card-body">
          <h3>Tail End Stories</h3>
          <p>Friendship tales, funny or heroic — heartwarming rescues and lessons learned. Sharing the love of the Rat community.</p>
          <a class="btn" href="#">Stories</a>
        </div>
      </article>

      <!-- Card: Cat Napped -->
      <article class="card">
        <img src="kitten.png" alt="Cat napping" class="card-img">
        <div class="card-body">
          <h3>Cat Napped</h3>
          <p>Latest strategy tips to avoid the Cat: safe zones, quick escapes, and unforgettable near misses. Rat-Fried means 1 squeak of approval!</p>
          <a class="btn" href="#">Survival tips</a>
        </div>
      </article>
    </section>

    <section class="gallery">
      <h2>Gallery & Projector Image</h2>
      <div class="thumbs">
        <img src="rat4.png" alt="rat team" class="thumb">
        <img src="rat1.png" alt="rat exploring" class="thumb">
        <img src="projector.png" alt="Image shown on projector" class="thumb">
      </div>
      <p class="small">Download the session handout: <a href="handout-3.pdf" target="_blank" rel="noopener">handout-3.pdf</a></p>
    </section>

    <section id="contact" class="contact">
      <h2>Contact Us</h2>
      <p>Have questions or want to join a Ratventure? Drop us a note.</p>
      <form class="contact-form" action="#" method="post" novalidate>
        <label>
          Name
          <input type="text" name="name" required>
        </label>
        <label>
          Email
          <input type="email" name="email" required>
        </label>
        <label>
          Message
          <textarea name="message" rows="4" required></textarea>
        </label>
        <button type="submit" class="btn btn-primary">Send</button>
      </form>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>Ratventures | Nibbles and Lurks | <a href="#contact">Contact Us</a></p>
      <p class="muted">© Ratventures — All tails reserved.</p>
    </div>
  </footer>
</body>
</html>




css

body {
  margin: 0;
  font-family: "Freckle Face", cursive;
  background: linear-gradient(#f5e96e, #c0a92e);
  color: #2e2e2e;
}

header {
  background-color: #c0a92e;
  text-align: center;
  padding: 15px;
}

header h1 {
  font-size: 36px;
  margin: 0;
}

nav {
  background-color: #b2911e;
  text-align: center;
  padding: 10px 0;
}

nav button {
  background-color: #b2911e;
  color: white;
  border: none;
  padding: 10px 15px;
  margin: 0 5px;
  cursor: pointer;
  font-size: 16px;
}

nav button:hover {
  background-color: #8d7412;
}

main {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 30px auto;
  width: 80%;
}

.intro {
  text-align: center;
  margin-bottom: 30px;
}

.intro img {
  border-radius: 50%;
  width: 120px;
  height: 120px;
}

.intro h2 {
  margin-top: 10px;
  font-size: 24px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  width: 100%;
  max-width: 900px;
}

.card {
  background-color: #f4f4f4;
  border-radius: 10px;
  padding: 15px;
  text-align: center;
  box-shadow: 0px 2px 5px rgba(0,0,0,0.1);
}

.card img {
  border-radius: 50%;
  width: 80px;
  height: 80px;
}

.card h3 {
  margin-top: 10px;
  font-size: 20px;
}

.card ul {
  list-style-type: none;
  padding: 0;
  margin-top: 10px;
  text-align: left;
}

footer {
  text-align: center;
  padding: 15px;
  background-color: #b2911e;
  color: white;
  margin-top: 40px;
}
