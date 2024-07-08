---
title: Elements
feature_text: |
  A demo of Markdown and HTML includes
feature_image: "https://picsum.photos/2560/600?image=873"
description: "A demo of Markdown and HTML includes"
permalink : /about
---
 <style>
   
    
    .hero .title, .hero .subtitle {
      color: white;
    }
    .section {
      padding: 3rem 1.5rem;
    }
    .icon-box {
      text-align: center;
      padding: 2rem;
      background-color: #f5f5f5;
      border-radius: 8px;
      transition: background-color 0.3s, transform 0.3s;
    }
    .icon-box:hover {
      background-color: #eaeaea;
      transform: translateY(-5px);
    }
    .icon-box .icon {
      margin-bottom: 1rem;
    }
    .timeline-item::before {
      background-color: #3273dc;
    }
    .stats-box {
      text-align: center;
      padding: 2rem;
      background-color: #3273dc;
      color: white;
      border-radius: 8px;
      margin-bottom: 1rem;
    }
    .stats-box h3 {
      font-size: 2rem;
      margin: 0;
      animation: fadeInUp 1s;
    }
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    .section-content {
      margin-bottom: 2rem;
    }
    .timeline {
      margin-top: 2rem;
    }
    .timeline-item {
      animation: fadeInUp 1s;
    }
    @media (max-width: 768px) {
      .timeline::before {
        left: 10%;
      }
      .timeline-header {
        text-align: left;
      }
    }
  </style>
</head>
<body>
  <!-- Hero Section -->
  <section class="hero is-small is-light is-bold">
    <div class="hero-body">
      <div class="container">
        <h1 class="title">About Me</h1>
        <h2 class="subtitle">Hello, I am Swarnil</h2>
      </div>
    </div>
  </section>

  <div class="ad-container">
    <ins class="adsbygoogle"
         style="display:block; height: 90px;"
         data-ad-client="ca-pub-1291242080282540"
         data-ad-slot="8939839370"
         data-ad-format="auto"
         data-full-width-responsive="true"></ins>
    <script>
         (adsbygoogle = window.adsbygoogle || []).push({});
    </script>
  </div>
  
  <style>
    .ad-container {
      width: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 2rem 0;
    }
    .adsbygoogle {
      width: 100%;
      max-height: 90px;
      text-align: center;
    }
    @media (max-width: 768px) {
      .adsbygoogle {
        max-height: 60px;
      }
    }
  </style>
  

  <!-- Introduction Section -->
  <section class="section">
    <div class="container">
      <div class="columns is-vcentered">
        <div class="column is-4 has-text-centered">
          <figure class="image is-128x128 is-inline-block">
            <img class="is-rounded" src="https://namastesalesforce.com/wp-content/uploads/2024/05/370395952_681942893953621_8097790202950337428_n.jpg" alt="Swarnil">
          </figure>
        </div>
        <div class="column is-8">
          <div class="content section-content">
            <h2 class="title is-4">Welcome to Namaste Salesforce</h2>
            <p>Welcome to Namaste Salesforce, your go-to destination for mastering Salesforce and CRM analytics. My name is Swarnil Singhai, and I'm a Salesforce CRM Analytics Engineer based in Bangalore. I embarked on my journey with Salesforce during my tenure at Accenture, where I received comprehensive training in Salesforce Development. It was at Accenture that I got the opportunity to work extensively with Einstein Analytics, delving deep into CRM analytics and discovering my passion for leveraging data-driven insights to drive business growth.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Purpose, Mission, Goal, and Values Section -->
  <section class="section">
    <div class="container">
      <div class="columns is-multiline">
        <div class="column is-one-quarter">
          <div class="icon-box">
            <div class="icon">
              <i class="fas fa-map-marked-alt fa-2x"></i>
            </div>
            <h3 class="title is-5">Purpose</h3>
            <p>Making Salesforce education accessible for all learners.</p>
          </div>
        </div>
        <div class="column is-one-quarter">
          <div class="icon-box">
            <div class="icon">
              <i class="fas fa-hands-helping fa-2x"></i>
            </div>
            <h3 class="title is-5">Mission</h3>
            <p>Support, educate, and guide individuals in their journey towards Salesforce career success.</p>
          </div>
        </div>
        <div class="column is-one-quarter">
          <div class="icon-box">
            <div class="icon">
              <i class="fas fa-trophy fa-2x"></i>
            </div>
            <h3 class="title is-5">Goal</h3>
            <p>Be recognized as the go-to platform for Salesforce learning.</p>
          </div>
        </div>
        <div class="column is-one-quarter">
          <div class="icon-box">
            <div class="icon">
              <i class="fas fa-universal-access fa-2x"></i>
            </div>
            <h3 class="title is-5">Values</h3>
            <ul>
              <li><i class="fas fa-check-circle"></i> Accessible</li>
              <li><i class="fas fa-check-circle"></i> Affordability</li>
              <li><i class="fas fa-check-circle"></i> Community</li>
              <li><i class="fas fa-check-circle"></i> Integrity</li>
              <li><i class="fas fa-check-circle"></i> Transparency</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Story Section -->
  <section class="section">
    <div class="container">
      <div class="content section-content">
        <h2 class="title is-4">Story</h2>
        <p>I founded Namaste Salesforce with a singular vision: to bridge the gap between aspiring Salesforce professionals and the lucrative opportunities emerging within the Salesforce ecosystem. Having personally navigated the complexities of entering the tech industry, I recognized the need for accessible and affordable resources tailored to the unique demands of mastering Salesforce. Drawing from my own journey and fueled by a passion for empowering others, Namaste Salesforce aims to democratize Salesforce education, offering comprehensive tutorials, courses, and digital products that equip individuals with the skills and confidence to thrive in this dynamic field. Whether you're a recent graduate embarking on your career journey or a seasoned professional seeking to expand your skill set, Namaste Salesforce is here to support you every step of the way, ensuring that no aspiring Salesforce enthusiast is left behind in their pursuit of success.</p>
      </div>
    </div>
  </section>

  <!-- Timeline Section -->
  <section class="section">
    <div class="container">
      <h2 class="title is-4">My Journey</h2>
      <div class="timeline is-centered">
        <header class="timeline-header">
          <span class="tag is-medium is-primary">2013</span>
        </header>
        <div class="timeline-item">
          <div class="timeline-marker"></div>
          <div class="timeline-content">
            <p class="heading">Started Engineering</p>
            <p>Joined LNCT Bhopal for Computer Science Engineering.</p>
          </div>
        </div>
        <header class="timeline-header">
          <span class="tag is-primary">2017</span>
        </header>
        <div class="timeline-item">
          <div class="timeline-marker"></div>
          <div class="timeline-content">
            <p class="heading">Graduation</p>
            <p>Graduated from LNCT Bhopal with a degree in Computer Science Engineering.</p>
          </div>
        </div>
        <header class="timeline-header">
          <span class="tag is-primary">2018</span>
        </header>
        <div class="timeline-item">
          <div class="timeline-marker"></div>
          <div class="timeline-content">
            <p class="heading">Joined Accenture</p>
            <p>Began my journey at Accenture, receiving comprehensive training in Salesforce Development.</p>
          </div>
        </div>
        <header class="timeline-header">
          <span class="tag is-primary">2020</span>
        </header>
        <div class="timeline-item">
          <div class="timeline-marker"></div>
          <div class="timeline-content">
            <p class="heading">Specialized in Einstein Analytics</p>
            <p>Delved deep into CRM analytics and discovered a passion for leveraging data-driven insights to drive business growth.</p>
          </div>
        </div>
        <header class="timeline-header">
          <span class="tag is-primary">2024</span>
        </header>
        <div class="timeline-item">
          <div class="timeline-marker is-primary"></div>
          <div class="timeline-content">
            <p class="heading">Founded Namaste Salesforce</p>
            <p>Launched Namaste Salesforce to democratize Salesforce education and support aspiring professionals.</p>
          </div>
        </div>
        <header class="timeline-header">
          <span class="tag is-primary">Present</span>
        </header>
        <div class="timeline-item">
          <div class="timeline-marker is-primary"></div>
          <div class="timeline-content">
            <p class="heading">Continuing the Journey</p>
            <p>Continuing to support, educate, and guide individuals in their journey towards Salesforce career success.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Stats Section -->
  <section class="section">
    <div class="container">
      <div class="columns is-multiline">
        <div class="column is-one-quarter">
          <div class="stats-box">
            <h3 class="title">5,000+</h3>
            <p>Students Taught</p>
          </div>
        </div>
        <div class="column is-one-quarter">
          <div class="stats-box">
            <h3 class="title">50+</h3>
            <p>Courses Available</p>
          </div>
        </div>
        <div class="column is-one-quarter">
          <div class="stats-box">
            <h3 class="title">10</h3>
            <p>Years of Experience</p>
          </div>
        </div>
        <div class="column is-one-quarter">
          <div class="stats-box">
            <h3 class="title">100%</h3>
            <p>Success Rate</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Social Media Section -->
  <section class="section">
    <div class="container has-text-centered">
      <div class="content">
        <h2 class="title is-4">Follow Me</h2>
        <div class="buttons is-centered">
          <a class="button is-medium is-link" href="https://facebook.com" target="_blank">
            <span class="icon">
              <i class="fab fa-facebook-f"></i>
            </span>
            <span>Facebook</span>
          </a>
          <a class="button is-medium is-info" href="https://twitter.com" target="_blank">
            <span class="icon">
              <i class="fab fa-twitter"></i>
            </span>
            <span>Twitter</span>
          </a>
          <a class="button is-medium is-danger" href="https://instagram.com" target="_blank">
            <span class="icon">
              <i class="fab fa-instagram"></i>
            </span>
            <span>Instagram</span>
          </a>
        </div>
      </div>
    </div>
  </section>