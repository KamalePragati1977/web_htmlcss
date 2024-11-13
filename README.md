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
