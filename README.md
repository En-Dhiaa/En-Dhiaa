<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>vCard - Personal Portfolio</title>
  <!--
    - favicon
  -->
  <link rel="shortcut icon" href="./assets/images/logo.ico" type="image/x-icon">
  <!--
    - custom css link
  -->
  <link rel="stylesheet" href="./assets/css/style.css">
  <!--
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
</head>
<body>
  <!--
    - #MAIN
  -->
  <main>
    <!--
      - #SIDEBAR
    -->
    <aside class="sidebar" data-sidebar>
      <div class="sidebar-info">
        <figure class="avatar-box">
          <img src="./assets/images/my-avatar.png" alt="Richard hanrick" width="80">
        </figure>
     <!--  name......................................................................................... -->
        <div class="info-content">
          <h1 class="name" title="Dhiaa Al-Hmiri">Dhiaa Al-Hmiri</h1>
          <p class="title">Flutter Full Stack</p>
        </div>
        <button class="info_more-btn" data-sidebar-btn>
          <span>Show Contacts</span>
          <ion-icon name="chevron-down"></ion-icon>
        </button>
      </div>
      <div class="sidebar-info_more">
        <div class="separator"></div>
        <ul class="contacts-list">
          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="mail-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">Email</p>
              <a href="mailto:richard@example.com" class="contact-link">dhiaa.org@gmail.com</a>
            </div>
          </li>
          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="phone-portrait-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">Phone</p>
              <a href="tel:+12133522795" class="contact-link" dir="ltr">+967 777117683</a>
            </div>
          </li>
          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="calendar-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">Birthday</p>
              <time datetime="1998-09-11">Sep 11, 1998</time>
            </div>
          </li>
          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="location-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">location</p>
              <address>Ring ST ,Sana'a , Yemen </address>
            </div>
          </li>
        </ul>
        <div class="separator"></div>
        <ul class="social-list">
          <li class="social-item">
            <a href="https://www.facebook.com/Dhiaa.AlHmiri?mibextid=ZbWKwL" class="social-link">
              <ion-icon name="logo-facebook"></ion-icon>
            </a>
          </li>
          <li class="social-item">
            <a href="https://wa.me/message/ZNWMGGMCVILTN1" class="social-link">
              <ion-icon name="logo-whatsapp"></ion-icon>
            </a>
          </li>
          <li class="social-item">
            <a href="https://t.me/Eng_Dhiaa_AlHmiri" class="social-link">
              <ion-icon name="logo-edge"></ion-icon>
            </a>
          </li>
          <li class="social-item">
            <a href="https://github.com/En-Dhiaa" class="social-link">
              <ion-icon name="logo-octocat"></ion-icon>
            </a>
          </li>
          <li class="social-item">
            <a href="https://yoursoft.tech" class="social-link">
              <ion-icon name="logo-chrome"></ion-icon>
            </a>
          </li>
        </ul>
      </div>
    </aside>
    <!--
      - #main-content
    -->
    <div class="main-content" dir="ltr" style="direction: ltr;">
      <!--
       ..................................................................................... - #NAVBAR
      -->
      <nav class="navbar" >
        <ul class="navbar-list">
          <li class="navbar-item">
            <button class="navbar-link  active" data-nav-link>About</button>
          </li>
          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Resume</button>
          </li>
          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Portfolio</button>
          </li>
          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Blog</button>
          </li>
          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Contact</button>
          </li>
        </ul>
      </nav>
     <!--
        - #ABOUT
      -->
      <article class="about  active" data-page="about" dir="ltr" style="direction: ltr;">
        <header>
          <h2 class="h2 article-title">About Me</h2>
        </header>
        <section class="about-text" dir="ltr" style="direction: ltr;">
          <p>
            A highly skilled Full-Stack Software Engineer with extensive experience in crafting exceptional mobile applications using Flutter. I possess advanced proficiency in designing intuitive and visually appealing user interfaces (UI/UX), ensuring seamless user experiences. With a strong foundation in working with diverse APIs and a keen ability to maintain both software and hardware systems, I deliver robust and reliable solutions.</p>
          <p>Leveraging my expertise in Livewire and Filament, I excel at developing dynamic and interactive user interfaces. My professional proficiency in English enables effective collaboration with international teams and clients. Additionally, I possess a strong grasp of graphic design tools, allowing me to create visually stunning and engaging designs. </p>       
            <p>
              I am passionate about staying up-to-date with the latest technologies and implementing best practices to deliver innovative, high-quality solutions for every project.*</p>
        </section>
        <!--
          - service
        -->
        <section class="service">
          <h3 class="h3 service-title">Experience</h3>
          <ul class="service-list">
            <li class="service-item">
              <div class="service-icon-box" dir="rtl">
                <img src="./assets/images/icon-design.svg
                " alt="design icon" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">Web design</h4>
                <p class="service-item-text" dir="ltr">
                  The most modern and high-quality design made at a professional level.
                </p>
              </div>
            </li>
            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/icon-app.svg" alt="mobile app icon" width="40">
              </div>
              <div class="service-content-box" dir="ltr">
                <h4 class="h4 service-item-title">Mobile apps</h4>
                <p class="service-item-text">
                  Professional development of applications for iOS and Android.
                </p>
              </div>
            </li>
            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/icon-photo.svg" alt="camera icon" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">Graphic Design</h4>
                <p class="service-item-text" dir="ltr">
                  I design great photos & videos of any category.
                </p>
              </div>
            </li>
            <li class="service-item">
              <div class="service-icon-box" dir="rtl">
                <img src="./assets/images/mark.png
                " alt="design icon" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">E-Commerce</h4>
                <p class="service-item-text" dir="ltr">
                  With the best way using great technics
                </p>
              </div>
            </li>
            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/icon-dev.svg" alt="Web development icon" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">Web development</h4>
                <p class="service-item-text" dir="ltr">
                  High-quality development of sites at the professional level
                </p>
              </div>
            </li>
            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/main.png" alt="camera icon" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">IT Support</h4>
                <p class="service-item-text" dir="ltr">
                  I develop software solutions ,and a professional maintenanceof computer (hard & soft).
                </p>
              </div>
            </li>
          </ul>
        </section>
     <!--
          - testimonials
        -->
        <section class="testimonials">  
        </section>
        <!--
          - testimonials modal
        -->
        <div class="modal-container" data-modal-container>
          <div class="overlay" data-overlay></div>
          <section class="testimonials-modal">
            <button class="modal-close-btn" data-modal-close-btn>
              <ion-icon name="close-outline"></ion-icon>
            </button>  
          </section>
        </div>
        <!-- <div style="margin: 20px;">
          <img alt='gift' width='400' align='right' style="border-radius: 10px" src='https://c.tenor.com/UttC4AITYR4AAAAd/full-stack-developer.gif'>
        </div> -->
      </article>
      <!--
        - #RESUME
      -->
      <article class="resume" data-page="resume">
        <header>
          <h2 class="h2 article-title">Resume</h2>
        </header>
        <section class="timeline"  dir="ltr" style="direction: ltr;">
          <div class="title-wrapper" dir="ltr" style="direction: ltr;">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>
            <h3 class="h3">Education</h3>
          </div>
          <br>
          <ol class="timeline-list">
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">Bachelor Degree of IT-Information Technology</h4>
              <span>-At Al-Hikma University - 2023-2024</span>
              <p class="timeline-text">
               faculty of engineering, IT section.
              </p>
            </li>
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">TOEFL iBT</h4>
              <span>2018-2019</span>
              <p class="timeline-text">
                Advanced Diploma of English Language with TOEFL iBT test - on Ets 
              </p>
            </li>
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">Sphere Project</h4>
              <span>2016 - 2017</span>
              <p class="timeline-text">
                Sphere Project - UNICEF - Taiz.
              </p>
            </li>
          </ol>
        </section>
        <section class="timeline">
          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="person-outline"></ion-icon>
            </div>
            <h3 class="h3">Experience</h3>
          </div>
          <ol class="timeline-list">
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">Flutter Dev</h4>
              <span>2022 — Present</span>
              <p class="timeline-text">
                - Yoursoft Company - 2024 till now
              </p>
            </li>
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title"> Flutter Freelancers</h4>
              <span>2023 — Present</span>
              <p class="timeline-text">
                13 applications only front-end  ,2 applications only full-stack-developer 
              </p>
            </li>
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title"> A Graphic Designer </h4>
              <span>2019 — Present</span>
              <p class="timeline-text">
                Freelancer and with some centers and institutes 
              </p>
            </li>
          </ol>
        </section>
        <section class="skill">
          <h3 class="h3 skills-title">My skills</h3>
          <ul class="skills-list content-card">
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">Web design</h5>
                <data value="80">80%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 80%;"></div>
              </div>
            </li>
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">Flutter</h5>
                <data value="90">90%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 90%;"></div>
              </div>
            </li>
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">Laravel</h5>
                <data value="70">70%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 70%;"></div>
              </div>
            </li>
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">Graphic design</h5>
                <data value="70">70%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 70%;"></div>
              </div>
            </li>
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">C#</h5>
                <data value="75">75%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 75%;"></div>
              </div>
            </li>
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">Marketing</h5>
                <data value="95">95%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 95%;"></div>
              </div>
            </li>
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">Computer Maintenance</h5>
                <data value="97">97%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 97%;"></div>
              </div>
            </li>
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">After Effect</h5>
                <data value="70">70%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 70%;"></div>
              </div>
            </li>
          </ul>
        </section>
      </article>
      <!--
        - #PORTFOLIO
      -->
      <article class="portfolio" data-page="portfolio">
        <header>
          <h2 class="h2 article-title">Portfolio</h2>
        </header>
        <section class="projects">
          <ul class="filter-list">
            <li class="filter-item">
              <button class="active" data-filter-btn>All</button>
            </li>
            <li class="filter-item">
              <button data-filter-btn>Web design</button>
            </li>
            <li class="filter-item">
              <button data-filter-btn>Applications</button>
            </li>
            <li class="filter-item">
              <button data-filter-btn>Web development</button>
            </li>
          </ul>
          <div class="filter-select-box">
            <button class="filter-select" data-select>
              <div class="select-value" data-selecct-value>Select category</div>
              <div class="select-icon">
                <ion-icon name="chevron-down"></ion-icon>
              </div>
            </button>
            <ul class="select-list">
              <li class="select-item">
                <button data-select-item>All</button>
              </li>
              <li class="select-item">
                <button data-select-item>Web design</button>
              </li>
              <li class="select-item">
                <button data-select-item>Applications</button>
              </li>
              <li class="select-item">
                <button data-select-item>Web development</button>
              </li>
            </ul>
          </div>
          <ul class="project-list">
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-1.jpg" alt="finance" loading="lazy">
                </figure>
                <h3 class="project-title">Finance</h3>
                <p class="project-category">Web development</p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-2.png" alt="orizon" loading="lazy">
                </figure>
                <h3 class="project-title">Orizon</h3>
                <p class="project-category">Web development</p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-3.jpg" alt="fundo" loading="lazy">
                </figure>
                <h3 class="project-title">Fundo</h3>
                <p class="project-category">Web design</p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="applications">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-4.png" alt="brawlhalla" loading="lazy">
                </figure>
                <h3 class="project-title">Brawlhalla</h3>
                <p class="project-category">Applications</p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-5.png" alt="dsm." loading="lazy">
                </figure>
                <h3 class="project-title">DSM.</h3>
                <p class="project-category">Web design</p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-6.png" alt="metaspark" loading="lazy">
                </figure>
                <h3 class="project-title">MetaSpark</h3>
                <p class="project-category">Web design</p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-7.png" alt="summary" loading="lazy">
                </figure>
                <h3 class="project-title">Dental</h3>
                <p class="project-category">Web development</p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="applications">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-8.jpg" alt="task manager" loading="lazy">
                </figure>
                <h3 class="project-title">Task Manager</h3>
                <p class="project-category">Applications</p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-9.png" alt="arrival" loading="lazy">
                </figure>
                <h3 class="project-title">Arrival</h3>
                <p class="project-category">Web development</p>
              </a>
            </li>
          </ul>
        </section>
      </article>
      <!--
        - #BLOG
      -->
      <article class="blog" data-page="blog">
        <header>
          <h2 class="h2 article-title">Blog</h2>
        </header>
        <section class="blog-posts">
          <ul class="blog-posts-list">
            <li class="blog-post-item">
              <a href="#">
               <figure class="blog-banner-box">
                  <img src="./assets/images/blog-1.jpg" alt="Design conferences in 2022" loading="lazy">
                </figure>
                <div class="blog-content">
                  <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>
                  <h3 class="h3 blog-item-title">Design conferences in 2022</h3>
                  <p class="blog-text">
                    Veritatis et quasi architecto beatae vitae dicta sunt, explicabo.
                  </p>
                </div>
              </a>
            </li>
            <li class="blog-post-item">
              <a href="#">
                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-2.jpg" alt="Best fonts every designer" loading="lazy">
                </figure>
                <div class="blog-content">
                 <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>
                  <h3 class="h3 blog-item-title">Best fonts every designer</h3>
                  <p class="blog-text">
                    Sed ut perspiciatis, nam libero tempore, cum soluta nobis est eligendi.
                  </p>
                </div>
              </a>
            </li>
            <li class="blog-post-item">
              <a href="#">
                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-3.jpg" alt="Design digest #80" loading="lazy">
                </figure>
                <div class="blog-content">
                  <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>
                  <h3 class="h3 blog-item-title">Design digest #80</h3>
                  <p class="blog-text">
                    Excepteur sint occaecat cupidatat no proident, quis nostrum exercitationem ullam corporis suscipit.
                  </p>
                </div>
              </a>
            </li>
            <li class="blog-post-item">
              <a href="#">
                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-4.jpg" alt="UI interactions of the week" loading="lazy">
                </figure>
                <div class="blog-content">
                  <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>
                  <h3 class="h3 blog-item-title">UI interactions of the week</h3>
                  <p class="blog-text">
                    Enim ad minim veniam, consectetur adipiscing elit, quis nostrud exercitation ullamco laboris nisi.
                  </p>
                </div>
              </a>
            </li>
            <li class="blog-post-item">
              <a href="#">
                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-5.jpg" alt="The forgotten art of spacing" loading="lazy">
                </figure>
                <div class="blog-content">
                  <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>
                  <h3 class="h3 blog-item-title">The forgotten art of spacing</h3>
                  <p class="blog-text">
                    Maxime placeat, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  </p>
                </div>
              </a>
            </li>
            <li class="blog-post-item">
              <a href="#">
                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-6.jpg" alt="Design digest #79" loading="lazy">
                </figure>
                <div class="blog-content">
                  <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>
                  <h3 class="h3 blog-item-title">Design digest #79</h3>
                  <p class="blog-text">
                    Optio cumque nihil impedit uo minus quod maxime placeat, velit esse cillum.
                  </p>
                </div>
              </a>
            </li>
          </ul>
        </section>
      </article>
         <!--
        - #CONTACT
      -->
      <article class="contact" data-page="contact">
        <header>
          <h2 class="h2 article-title">Contact</h2>
        </header>
        <section class="mapbox" data-mapbox>
          <figure>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d745.2795022129487!2d44.19087882563092!3d15.37009787678996!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1603dbbffdafef1d%3A0x4764f771ef901ac4!2z2YHZhtiv2YIg2KfZitis2YQg2KfZhNiz2YrYp9it2Yo!5e0!3m2!1sen!2s!4v1726405035966!5m2!1sen!2s"
              width="400" height="300" loading="lazy"></iframe>
          </figure>
        </section>
<!-- ........................................... -->
        <section class="contact-form">
          <h3 class="h3 form-title">Contact Form</h3>
          <form action="#" class="form" data-form>
            <div class="input-wrapper">
              <input type="text" name="fullname" class="form-input" placeholder="Full name" required data-form-input>
              <input type="email" name="email" class="form-input" placeholder="Email address" required data-form-input>
            </div>
            <textarea name="message" class="form-input" placeholder="Your Message" required data-form-input></textarea>
            <button class="form-btn" type="submit" disabled data-form-btn>
              <ion-icon name="paper-plane"></ion-icon>
              <span>Send Message</span>
            </button>
          </form>
        </section>
      </article>
    </div>
  </main>
  <!--
    - custom js link
  -->
  <script src="./assets/js/script.js"></script>
  <!--
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
</body>
</html>
