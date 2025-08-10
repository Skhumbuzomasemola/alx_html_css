# alx_html_css

# 🎧 Headphones Landing Page

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Headphones</title>
  <link rel="stylesheet" href="styles.css">
<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Source Sans Pro', sans-serif;
  line-height: 1.5;
  color: #fff;
  background: #091d36;
}

.btn {
  display: inline-block;
  background: #ff6565;
  color: #fff;
  padding: 12px 25px;
  border-radius: 25px;
  text-decoration: none;
  margin-top: 15px;
}
.btn:hover, .btn:active {
  opacity: 0.9;
}

.header {
  padding: 15px;
  display: flex;
  justify-content: center;
  background: transparent;
}
.logo {
  display: flex;
  align-items: center;
  gap: 5px;
}

.hero {
  padding: 20px;
  text-align: center;
}
.hero h1 {
  font-size: 1.4rem;
}
.hero p {
  margin-top: 10px;
}
.hero-text {
  margin-top: 20px;
  font-size: 0.9rem;
  color: #ccc;
}


.what-we-do {
  background: #fff;
  color: #000;
  padding: 30px 15px;
  text-align: center;
}
.icons {
  margin-top: 20px;
}
.icon-box {
  margin-bottom: 20px;
}
.icon-box img {
  max-width: 50px;
}
.icon-box h3 {
  margin-top: 10px;
}


.results {
  padding: 30px 15px;
  text-align: center;
}
.stats {
  display: flex;
  flex-direction: column;
  gap: 15px;
  margin-top: 20px;
}
.stat {
  background: #ff6565;
  padding: 20px;
  clip-path: polygon(50% 0, 100% 25%, 100% 75%, 50% 100%, 0 75%, 0 25%);
}

.contact {
  padding: 30px 15px;
  background: #fff;
  color: #000;
  text-align: center;
}
.contact input,
.contact textarea {
  width: 100%;
  margin: 10px 0;
  padding: 10px;
  border: none;
  border-bottom: 1px solid #ccc;
}
.contact button {
  margin-top: 15px;
}

.footer {
  padding: 20px;
  text-align: center;
}
.footer-logo {
  display: flex;
  justify-content: center;
  gap: 5px;
  margin-bottom: 10px;
}
.socials {
  margin: 10px 0;
}
.socials img {
  width: 20px;
  margin: 0 5px;
}

@media (min-width: 481px) {
  body {
    background: #fff; 
    color: #000;
  }

  
  main, header, section, footer {
    max-width: 1000px;
    margin: 0 auto;
  }

  
  .hero {
    text-align: left;
    padding: 40px 20px;
    background: url('images/hero-bg.jpg') no-repeat center/cover;
    color: #fff;
  }
  .hero h1 {
    font-size: 2rem;
  }
  .hero-text {
    max-width: 500px;
  }

  
  .icons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    margin-top: 30px;
  }

 
  .stats {
    flex-direction: row;
    justify-content: center;
    gap: 30px;
  }
  .stat {
    width: 120px;
    height: 120px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.2rem;
    color: #fff;
  }

  
  .contact form {
    max-width: 500px;
    margin: 0 auto;
  }

 
  .footer {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>
</head>
<body>
<img src="archive 2/01_headphones_mobile@2x.png" alt="headphones">


  <header class="header">
    <div class="logo">
      <img src="images/logo.png" alt="Headphones logo">
      <span>HEADPHONES</span>
    </div>
  </header>

  
  <section class="hero">
    <h1>Lorem ipsum dolor set amet lorem ipsum</h1>
    <p>Lorem ipsum dolor set amet lorem ipsum dolor set</p>
    <a href="#" class="btn">CALL TO ACTION</a>
    <p class="hero-text">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore...
    </p>
<img src="alx_html_css/Untitled.svg" alt="headphones image">
  </section>


  <section class="what-we-do">
    <h2>What we do…</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
    <div class="icons">
      <div class="icon-box">
        <img src="images/icon1.png" alt="">
        <h3>Lorem ipsum</h3>
        <p>Lorem ipsum dolor sit amet...</p>
      </div>
      <div class="icon-box">
        <img src="images/icon2.png" alt="">
        <h3>Lorem ipsum</h3>
        <p>Lorem ipsum dolor sit amet...</p>
      </div>
      <div class="icon-box">
        <img src="images/icon3.png" alt="">
        <h3>Lorem ipsum</h3>
        <p>Lorem ipsum dolor sit amet...</p>
      </div>
      <div class="icon-box">
        <img src="images/icon4.png" alt="">
        <h3>Lorem ipsum</h3>
        <p>Lorem ipsum dolor sit amet...</p>
      </div>
    </div>
  </section>

  
  <section class="results">
    <h2>Our results speak for themselves</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
    <div class="stats">
      <div class="stat">+2%</div>
      <div class="stat">+2%</div>
      <div class="stat">+2%</div>
      <div class="stat">+2%</div>
    </div>
  </section>


  <section class="contact">
    <h2>Contact us</h2>
    <form>
      <input type="text" placeholder="Name">
      <input type="email" placeholder="Email">
      <textarea placeholder="Your message"></textarea>
      <button type="submit" class="btn">CALL TO ACTION</button>
    </form>
  </section>

  <footer class="footer">
    <div class="footer-logo">
      <img src="images/logo.png" alt="Headphones logo">
      <span>HEADPHONES</span>
    </div>
    <div class="socials">
      <a href="#"><img src="images/facebook.png" alt="Facebook"></a>
      <a href="#"><img src="images/twitter.png" alt="Twitter"></a>
      <a href="#"><img src="images/instagram.png" alt="Instagram"></a>
    </div>
    <p>© headphones 2024</p>
  </footer>

</body>
</html>
