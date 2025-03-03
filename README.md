<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sustainable-Transportation-Race</title>
  <link href="https://fonts.googleapis.com/css2?family=Germona&display=swap" rel="stylesheet">
  <style>
    /* Base Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
      overflow-x: hidden;
    }
    header {
      background: #ff4500;
      color: white;
      text-align: center;
      padding: 30px 20px;
      position: relative;
      overflow: hidden;
    }
    header h1 {
      font-family: 'Germona', serif;
      font-size: 3rem;
      text-transform: uppercase;
      margin: 0;
      animation: fadeInDown 1s ease-out;
    }
    header p {
      font-size: 1.3rem;
      margin: 10px 0 0;
      animation: fadeInDown 1.2s ease-out;
    }
    nav {
      background: #333;
      text-align: center;
      padding: 10px 0;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1rem;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffcc00;
    }
    section {
      margin: 50px auto;
      width: 85%;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 0.8s ease-out forwards;
    }
    section:nth-of-type(1) { animation-delay: 0.2s; }
    section:nth-of-type(2) { animation-delay: 0.4s; }
    section:nth-of-type(3) { animation-delay: 0.6s; }
    section:nth-of-type(4) { animation-delay: 0.8s; }
    section:nth-of-type(5) { animation-delay: 1s; }
    section h2 {
      color: #ff4500;
      font-size: 2rem;
      margin-top: 0;
      font-family: 'Germona', serif;
    }
    .highlight {
      color: #007acc;
      font-weight: bold;
    }
    .btn {
      display: inline-block;
      background: #007acc;
      color: #fff;
      padding: 10px 15px;
      margin-top: 10px;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #005f99;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li {
      background: #f4f4f4;
      margin: 10px 0;
      padding: 10px;
      border-radius: 5px;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #333;
      color: #fff;
      font-size: 0.9rem;
    }
    /* Keyframe Animations */
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>🏁 Sustainable Transportation: A Race 🏁</h1>
    <p>Solar Cars vs. Electric Vehicles – Racing Toward a Greener Future!</p>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#survey">Survey</a>
    <a href="#research">Research</a>
    <a href="#tinkercad">3D Model</a>
    <a href="#presentation">Presentation</a>
  </<>
  <section id="about">
    <h2>🏎️ About Our Project</h2>
    <p>
      We’re <span class="highlight">Fatima</span> and <span class="highlight">Hessa</span> from <span class="highlight">Taryam American Private School</span>. Our mission is to explore how sustainable transportation through solar-powered and electric vehicles can reduce pollution and the carbon footprint. We’re putting our innovative race models to the test in a head-to-head battle for the future of eco-friendly mobility!
    </p>
    <p>
      Through creative design, thorough research, and real-world surveys, our project dives deep into the challenges and solutions of transforming urban mobility.
    </p>
  </section>
  
  <section id="survey">
    <h2>📊 Survey Analysis: Sustainability Perception</h2>
    <p><strong>About:</strong> Sustainability in general</p>
    <p><strong>Volunteers:</strong> 156 | <strong>Ages:</strong> 16-18 | <strong>Questions:</strong> 11</p>
    <h3>Motivation After the Questionnaire</h3>
    <ul>
      <li><strong>Interested:</strong> 53%</li>
      <li><strong>Not Interested:</strong> 47%</li>
    </ul>
    
    <p>Want to share your opinion? click the button to take our survey!</p>
    <a href="https://docs.google.com/forms/d/e/1FAIpQLSdN3UBv5UIqCAezHNf0zs2AIa0fR-TD9GohW0y2nDFatfUxtw/viewform?usp=header" target="_blank" class="btn">📝 Take the Survey</a>
  </section>
  <section id="research">
    <h2>📘 In-Depth Research</h2>
    <p>
      You can access the full research document on sustainable transportation at the following link:
    </p>
    <a href="https://d3ey0ivtc68uxj.cloudfront.net/public/0214b4d2a682d0ba6016b7c82ee83aca.pdf" target="_blank" class="btn">
      📄 View Research Document
    </a>
  </section>

  <section id="tinkercad">
    <h2>🛠️ 3D Model Showcase</h2>
    <p>
      Check out our innovative 3D design of a solar-powered race car on Tinkercad! This model represents our vision for sustainable speed and cutting-edge engineering.
    </p>
    <a href="https://www.tinkercad.com/things/a4MpFhlm1be-sustainable-car-working-on-solar-energy?sharecode=9OXtgcv23MfkvCB26sae7Zj6M1YTnmX0mrAjhv168-Y" target="_blank" class="btn">
      🚗 View the Tinkercad Model
    </a>
  </section>
  
  <section id="presentation">
    <h2>🎥 Project Presentation</h2>
    <p>
      Explore our comprehensive presentation that outlines our research, design process, and survey analysis. You can also take the survey to share your views!
    </p>
    <a href="https://docs.google.com/file/d/1LTh_IWseABaRdhmXjetAA7fEKiDRUdyR/edit?usp=docslist_api&filetype=mspresentation" target="_blank" class="btn">
      📊 View the Presentation
    </a>
    <a href="https://docs.google.com/forms/d/e/1FAIpQLSdN3UBv5UIqCAezHNf0zs2AIa0fR-TD9GohW0y2nDFatfUxtw/viewform?usp=header" target="_blank" class="btn" style="margin-left:10px;">
      📝 Take the Survey
    </a>
  </section>
  
  <footer>
    <p>Created by Fatima &amp; Hessa | Taryam American Private School | 2025</p>
  </footer>
</body>
</html>
