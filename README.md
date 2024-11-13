# web_htmlcss
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AyurnitiBot</title>
  <style>
    /* CSS Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #e6efeb;
    }

    /* Header */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 50px;
      background-color: #ffffff;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    header img {
      height: 60px;
    }

    nav {
      display: flex;
      gap: 15px;
    }

    nav a {
      padding: 10px 20px;
      background-color: #a8d5af;
      border-radius: 20px;
      text-decoration: none;
      color: #2e593f;
      font-weight: bold;
      transition: background-color 0.3s;
    }

    nav a:hover {
      background-color: #83c296;
    }

    nav a.active {
      background-color: #83c296;
      color: #ffffff;
    }

    /* Main Section */
    .main-section {
      display: flex;
      justify-content: space-around;
      align-items: center;
      padding: 50px;
      gap: 50px;
    }

    .text-content {
      max-width: 500px;
    }

    .text-content h2 {
      color: #2e593f;
      font-size: 2.5em; /* Increased font size */
      margin-bottom: 50px;
    }

    .text-content p {
      margin-bottom: 20px;
      color: #3a4b3e;
      line-height: 1.6;
      display: flex;
      align-items: center;
      margin-top: 5px; /* Reduced margin-top for spacing adjustment */
    }

    /* Small image styling for "Health Comes First" */
    .text-content p img {
      width: 27px; /* Adjust size of the small image */
      height: 27px;
      margin-right: 8px;
      vertical-align: middle;
      border-radius: 50%;
    }

    .text-content .button {
      display: inline-flex;
      align-items: center;
      gap: 8px; /* Space between icon and text */
      padding: 8px 25px;
      background-color: #6f66ee;
      color: #ffffff;
      border: none;
      border-radius: 8px;
      font-size: 0.9em;
      text-decoration: none;
      transition: background-color 0.3s;
    }

    .text-content .button:hover {
      background-color: #7fa2b6;
    }

    .text-content .button img {
      width: 30px; /* Adjust size of the icon as needed */
      height: 30px;
      vertical-align: middle;
    }

    .chakra-image img {
      height: 500px; /* Increased height of home.jpg */
      width: auto;
      border-radius: 5px;
    }

    /* Floating Chatbot Button */
    .chatbot-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      padding: 15px;
      background-color: #6f66ee;
      color: #ffffff;
      border-radius: 50%;
      font-size: 1.5em;
      display: flex;
      justify-content: center;
      align-items: center;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .chatbot-button:hover {
      background-color: #7fa2b6;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <img src="./assets/logo.png" alt="Ayurniti Logo">
    <nav>
      <a href="home_page.html" class="active">Home</a>
      <a href="service_page.html">Services</a>
      <a href="about_page.html">About</a>
    </nav>
  </header>

  <!-- Main Section -->
  <section class="main-section">
    <div class="text-content">
      <p>
        <img src="./assets/hearticon.png" alt="Icon"> <!-- Add your small image here -->
        <span style="color: rgb(37, 36, 36);">Health Comes First</span>
      </p>
      <h2>AyurnitiBot : Personalized Ayurvedic Wellness Chatbot</h2>
      <p>Discover Your Ayurvedic Balance. Experience Our AI-driven Chatbot that determines your Prakriti and offers personalized dietary guidance for holistic well-being.</p>
      <a href="#" class="button">
        <img src="./assets/chatbot.png" alt="ChatBot Icon"> <!-- Add the icon here -->
        Open ChatBot
      </a>
    </div>
    <div class="chakra-image">
      <img src="./assets/home.jpg" alt="Chakra Illustration">
    </div>
  </section>

  <!-- Floating Chatbot Button -->
  <div class="chatbot-button">💬</div>

</body>
</html>


service page :
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ayurniti - What We Do</title>
  <style>
    /* CSS Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #ffffff;
    }

    /* Header */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 50px;
      background-color: #ffffff;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    header img {
      height: 60px;
    }

    nav {
      display: flex;
      gap: 15px;
    }

    nav a {
      padding: 10px 20px;
      background-color: #a8d5af;
      border-radius: 20px;
      text-decoration: none;
      color: #2e593f;
      font-weight: bold;
      transition: background-color 0.3s;
    }

    nav a:hover {
      background-color: #83c296;
    }

    nav a.active {
      background-color: #83c296;
      color: #ffffff;
    }

    /* Main Section */
    .main-section {
      text-align: center;
      padding: 40px 20px;
    }

    .main-section h2 {
      font-size: 2.5em;
      color: #000000;
      margin-bottom: 20px;
    }

    .main-section p {
      color: #3a4b3e;
      font-size: 1em;
      max-width: 1000px;
      margin: 0 auto 50px;
    }

    /* Service Cards */
    .services {
      display: flex;
      justify-content: space-around;
      gap: 20px;
      flex-wrap: wrap;
    }

    .service-card {
        background-color: #c1e1ca;
        padding: 20px;
        border-radius: 10px;
        width: 300px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        text-align: center; /* Center-align content */
        position: relative; /* For positioning icon */
    }

    .service-card h3 {
        font-size: 1.5em;
        color: #2e593f;
        margin: 20px 0 10px;
        display: inline-block;
        align-items: center;
        text-align: center;
    }

    .service-card h3 img {
        width: 50px;
        height: 50px;
        position: absolute;
        top: -25px; /* Position image halfway outside the card */
        left: 50%; /* Center image horizontally */
        transform: translateX(-50%);
    }

    .service-card p {
      font-size: 0.9em;
      color: #3a4b3e;
      line-height: 1.6;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <img src="./assets/logo.png" alt="Ayurniti Logo">
    <nav>
      <a href="home_page.html">Home</a>
      <a href="service_page.html" class="active">Services</a>
      <a href="about_page.html">About</a>
    </nav>
  </header>

  <!-- Main Section -->
  <section class="main-section">
    <h2>What We Do</h2>
    <p>We combine ancient Ayurvedic Wisdom with cutting-edge Technology to provide personalized wellness guidance. Our chatbot assesses your Prakriti, or constitution, and offers tailored diet and lifestyle recommendations to help you achieve balance and harmony in your life.</p>

    <!-- Services Cards -->
    <div class="services">
      <!-- Vata Card -->
      <div class="service-card">
        <h3>
          <img src="./assets/vata.png" alt="Vata Icon">
          Vata
        </h3>
        <p>Vata combines air and space, also called ether. It has links to change, mobility, and movement. According to Ayurvedic medicine, it relates to the nervous system and controls breathing, thinking, and circulation.</p>
        <p>People with a Vata constitution are typically energetic, creative, and flexible, but they may have insufficient or moderate weight, dry skin, and fine hair.</p>
      </div>

      <!-- Pitta Card -->
      <div class="service-card">
        <h3>
          <img src="./assets/pitta.png" alt="Pitta Icon">
          Pitta
        </h3>
        <p>Pitta’s elemental makeup consists of fire and water. It governs digestion, body temperature, and metabolism. Those with a Pitta constitution are often focused and driven, with a strong build.</p>
        <p>Pitta-dominant people may have oily skin, a warm body temperature, and a sharp intellect.</p>
      </div>

      <!-- Kapha Card -->
      <div class="service-card">
        <h3>
          <img src="./assets/kapha.png" alt="Kapha Icon">
          Kapha
        </h3>
        <p>Kapha is based on earth and water. It can be described as steady, stable, heavy, and grounded. This dosha governs structure, stability, and lubrication within the body.</p>
        <p>People with a Kapha constitution often have a calm temperament, well-built bodies, and smooth, radiant skin.</p>
      </div>
    </div>
  </section>

</body>
</html>


About Page:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AyurnitiBot - About Us</title>
  <style>
    /* CSS Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #e6efeb;
    }

    /* Header */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 50px;
      background-color: #ffffff;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    header img {
      height: 60px;
    }

    nav {
      display: flex;
      gap: 15px;
    }

    nav a {
      padding: 10px 20px;
      background-color: #a8d5af;
      border-radius: 20px;
      text-decoration: none;
      color: #2e593f;
      font-weight: bold;
      transition: background-color 0.3s;
    }

    nav a:hover {
      background-color: #83c296;
    }

    nav a.active {
      background-color: #83c296;
      color: #ffffff;
    }

    /* About Section */
    .about-section {
      display: flex;
      padding: 50px;
      gap: 50px;
      background-color: #d7efdd;
    }

    .about-image {
      flex: 1;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .about-image img {
      max-width: 80%;
      border-radius: 10px;
    }

    .about-content {
      flex: 1;
      background-color: #ffffff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .about-content h2 {
      font-size: 2em;
      color: #2e593f;
      margin-bottom: 20px;
    }

    .about-content p {
      font-size: 0.9em;
      color: #3a4b3e;
      line-height: 1.6;
    }

    /* Our Values Section */
    .values-section {
      padding: 50px;
      background-color: #f3f9f5;
      text-align: center;
    }

    .values-section h3 {
      font-size: 2em;
      color: #2e593f;
      margin-bottom: 30px;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    .values-grid {
      display: flex;
      justify-content: space-around;
      gap: 30px;
      flex-wrap: wrap;
    }

    .value-item {
      flex: 1;
      max-width: 330px;
      background-color: #ffffff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
      text-align: center;
      transition: transform 0.3s, box-shadow 0.3s;
      cursor: pointer;
    }

    .value-item:hover {
      transform: translateY(-10px);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    }

    .value-item h4 {
      font-size: 1.4em;
      color: #2e593f;
      margin-bottom: 15px;
      position: relative;
    }

    .value-item h4::after {
      content: "";
      display: block;
      width: 40px;
      height: 2px;
      background-color: #83c296;
      margin: 10px auto 0;
      border-radius: 2px;
    }

    .value-item p {
      font-size: 0.9em;
      color: #3a4b3e;
      line-height: 1.6;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <img src="./assets/logo.png" alt="Ayurniti Logo">
    <nav>
      <a href="home_page.html">Home</a>
      <a href="service_page.html">Services</a>
      <a href="about_page.html" class="active">About</a>
    </nav>
  </header>

  <!-- About Section -->
  <section class="about-section">
    <div class="about-image">
      <img src="./assets/about.jpg" alt="Ayurveda Elements">
    </div>
    <div class="about-content">
      <h2>About Us</h2>
      <p>Welcome to Ayurniti, your gateway to the harmonious fusion of ancient Ayurvedic wisdom and modern technology. At Ayurniti, we're dedicated to empowering individuals with profound insights into their well-being, health, and constitution.</p>
      <p>Our journey began with a simple yet powerful belief: to blend the timeless principles of Ayurveda with the precision of modern machine learning to enhance lives.</p>
    </div>
  </section>

  <!-- Our Values Section -->
  <section class="values-section">
    <h3>Our Core Values</h3>
    <div class="values-grid">
      <div class="value-item">
        <h4>Holistic Well-being</h4>
        <p>We believe in nurturing the mind, body, and spirit to achieve a balanced and healthy life.</p>
      </div>
      <div class="value-item">
        <h4>Innovation</h4>
        <p>We are dedicated to advancing Ayurveda through the integration of modern technology and research.</p>
      </div>
      <div class="value-item">
        <h4>Compassion</h4>
        <p>We approach each individual with empathy, respect, and a commitment to improving lives.</p>
      </div>
      <div class="value-item">
        <h4>Sustainability</h4>
        <p>Our practices are aligned with environmental responsibility and the preservation of natural resources.</p>
      </div>
    </div>
  </section>

</body>
</html>



