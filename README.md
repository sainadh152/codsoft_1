<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />

  <link rel="stylesheet" href="portfolio.css">

  <title>Portfolio</title>
</head>
<body>
  <!-- NAVBAR -->
  <nav>
    <div class="left">
      <a href="/">Pooja Sree</a>
    </div>

    <div class="right">
      <a href="http://github.com" target="_blank" rel="noopener noreferrer">
        <i class="fa-brands fa-github"></i>
        <span>Github</span>
      </a>
      
      <a href="http://linkedin.com" target="_blank" rel="noopener noreferrer">
        <i class="fa-brands fa-linkedin"></i>
        <span>Linkedin</span>
      </a>
      
      <a href="mailto:poojasree.y1@gmail.com">
        <i class="fa-solid fa-envelope"></i>
        <span>Email</span>
      </a>
    </div>
  </nav>

  <main>
    <!-- SECTION 1: Hero -->
    <section class="hero-section">
      <div class="text">
        <h2>Hi, I'm Pooja 👋</h2>
        <p>Myself Pooja Sree. I'm studying 2nd year B.Tech from R.V.R & J.C College of Engineering and Technology.</p>

        <div class="links">
          <a href="#skills">
            <i class="fa-solid fa-code"></i>
            <span>Skills</span>
          </a>
          
          <a href="#contact">
            <i class="fa-solid fa-envelope"></i>
            <span>Contact</span>
          </a>
        </div>
      </div>

      <div class="headshot">
        <img src="images/passport.jpg" alt="pooja sree">
      </div>
    </section>

    <!-- SECTION 2: Skills -->
    <section id="skills" class="skills-section">
      <h2>Skills</h2>
      <div class="text">
        I'm so much interested in coding and building web applications. I love coding. So, I'm experienced in html, css, javascript, react and node.
        </div>

      <div class="cells">
        <div class="cell">
          <img src="images/html-logo.webp" alt="html logo">
          <span>HTML</span>
        </div>
        
        <div class="cell">
          <img src="images/css-logo.webp" alt="css logo">
          <span>CSS</span>
        </div>
        
        <div class="cell">
          <img src="images/javascript-logo.webp" alt="javascript logo">
          <span>JavaScript</span>
        </div>
        
        <div class="cell">
          <img src="images/node-logo.webp" alt="node logo">
          <span>Node.js</span>
        </div>
        
        <div class="cell">
          <img src="images/react-logo.webp" alt="react logo">
          <span>React.js</span>
        </div>
      </div>
    </section>

    
    <!-- SECTION 4: Contact -->
    <section id="contact" class="contact-section">
      <h2>Contact</h2>

      <div class="group">
        <div class="text">
          For contact, enter your details in the below given form.
        </div>

        <form>
          <label for="name">Name</label>
          <input type="text" id="name">

          <label for="email">Email</label>
          <input type="email" id="email">

          <label for="message">Message</label>
          <textarea id="message" cols="30" rows="10"></textarea>

          <button type="submit">Send Message</button>
        </form>
      </div>
    </section>
  </main>
</body>
</html>
