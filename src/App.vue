<script setup>
import "@fontsource/poppins";
import "@fontsource/league-spartan";
</script>

<template>
  <header class="header" data-header>
    <div class="container">
      <a href="#" class="logo">
        <img
          src="./assets/images/logo.png"
          width="100%"
          height="100%"
          alt="EduWeb logo"
        />
      </a>

      <nav class="navbar" data-navbar>
        <div class="wrapper">
          <a href="#" class="logo">
            <img
              src="./assets/images/logo.png"
              width="100"
              height="100"
              alt="EduWeb logo"
            />
          </a>

          <button
            class="nav-close-btn"
            aria-label="close menu"
            data-nav-toggler
          >
            <ion-icon name="close-outline" aria-hidden="true"></ion-icon>
          </button>
        </div>

        <ul class="navbar-list">
          <li class="navbar-item">
            <a href="#home" class="navbar-link" data-nav-link>Home</a>
          </li>

          <li class="navbar-item">
            <a href="#about" class="navbar-link" data-nav-link>Our Services</a>
          </li>

          <li class="navbar-item">
            <a href="#courses" class="navbar-link" data-nav-link>About Us</a>
          </li>

          <li class="navbar-item">
            <a href="#blog" class="navbar-link" data-nav-link>Our Events</a>
          </li>

          <li class="navbar-item">
            <a href="#footer" class="navbar-link" data-nav-link>Contact Us</a>
          </li>
        </ul>
      </nav>

      <div class="header-actions">
       
        <a href="#footer" class="btn has-before">
          <span class="span">Send Email</span>

          <ion-icon name="arrow-forward-outline" aria-hidden="true"></ion-icon>
        </a>

        <button
          class="header-action-btn"
          aria-label="open menu"
          data-nav-toggler
        >
          <ion-icon name="menu-outline" aria-hidden="true"></ion-icon>
        </button>
      </div>

      <div class="overlay" data-nav-toggler data-overlay></div>
    </div>
  </header>

  <main>
    <article>
      <section
        class="section hero has-bg-image"
        id="home"
        aria-label="home"
        style="background-image: url('./assets/images/hero-bg.svg')"
      >
        <div class="container">
          <div class="hero-content">
            <h3 class="h3 section-title">
              One <span class="span">Island</span>, one
              <span class="span">Nation</span>
            </h3>

            <h1 class="h1 section-title">
              Equal <span class="span">opportunity</span>
            </h1>

            <p class="hero-text">
              For too long, our rural communities have been overlooked not
              because of a lack of potential, but because opportunities never
              reached them. Rural people are exceptional too. Imagine the power
              of a nation that lifts everyone, from city to countryside. It’s
              time we break down barriers and recognize that talent knows no
              boundaries. When we open doors for all, we don’t just build a
              stronger community; we build a stronger nation
            </p>

            <a href="#" class="btn has-before">
              <span class="span">Contact Us</span>

              <ion-icon
                name="arrow-forward-outline"
                aria-hidden="true"
              ></ion-icon>
            </a>
          </div>

          <figure class="hero-banner">
            <div class="img-holder one" style="--width: 270; --height: 300">
              <img
                src="./assets/images/image7.jpg"
                width="270"
                height="300"
                alt="hero banner"
                class="img-cover"
              />
            </div>

            <div class="img-holder two" style="--width: 240; --height: 370">
              <img
                src="./assets/images/image3.jpg"
                width="240"
                height="370"
                alt="hero banner"
                class="img-cover"
              />
            </div>

           

            <img
              src="./assets/images/hero-shape-2.png"
              width="622"
              height="551"
              alt=""
              class="shape hero-shape-2"
            />
          </figure>
        </div>
      </section>

      <section class="section about" id="about" aria-label="about">
        <div class="container">
          <figure class="about-banner">
            <div class="img-holder" style="--width: 520; --height: 370">
              <img
                src="./assets/images/image4.jpg"
                width="520"
                height="370"
                loading="lazy"
                alt="about banner"
                class="img-cover"
              />
            </div>

         
        
            <img
              src="./assets/images/about-shape-3.png"
              width="722"
              height="528"
              loading="lazy"
              alt=""
              class="shape about-shape-3"
            />
          </figure>

          <div class="about-content">
            <p class="section-subtitle">Our Services</p>

            <h2 class="h2 section-title">
              Join us at <span class="span">Win Together Madagascar,</span>
            </h2>

            <p class="section-text">
              where we turn aspirations into achievements! Our exciting array of
              services is designed to inspire, educate, and connect individuals,
              ensuring that everyone has the chance to thrive and shine in our
              vibrant community!
            </p>

            <ul class="about-list">
              <li class="about-item">
                <ion-icon
                  name="checkmark-done-outline"
                  aria-hidden="true"
                ></ion-icon>

                <span class="span">Online conference</span>
              </li>

              <li class="about-item">
                <ion-icon
                  name="checkmark-done-outline"
                  aria-hidden="true"
                ></ion-icon>

                <span class="span">Events</span>
              </li>

              <li class="about-item">
                <ion-icon
                  name="checkmark-done-outline"
                  aria-hidden="true"
                ></ion-icon>

                <span class="span">Trade fairs</span>
              </li>
            </ul>

            <img
              src="./assets/images/about-shape-4.svg"
              width="100"
              height="100"
              loading="lazy"
              alt=""
              class="shape about-shape-4"
            />
          </div>
        </div>
      </section>

      <section class="section category" aria-label="category" id="courses">
        <div class="container">
          <p class="section-subtitle">About Us</p>

          <h2 class="h2 section-title">
            Across <span class="span">the island</span>, we share information
            without borders.
          </h2>

          <p class="section-text">
            This is made possible by the technology we have at our disposal.
          </p>

          <ul class="grid-list cardDim">
            <li class="itemdim">
              <div class="category-card" style="--color: 170, 75%, 41%">
                <div class="card-icon">
                  <img
                    src="./assets/images/category-1.svg"
                    width="40"
                    height="40"
                    loading="lazy"
                    alt="Online Degree Programs"
                    class="img"
                  />
                </div>

                <h3 class="h3">
                  <a href="#" class="card-title">Mission</a>
                </h3>

                <p class="card-text">
                  Sharing the right information, verified and verifiable
                </p>
                <p class="card-text">Connecting people with informants</p>
                <p class="card-text">
                  Sharing opportunities through online conferences, events and
                  trade fairs
                </p>
              </div>
            </li>

            <li class="itemdim">
              <div class="category-card" style="--color: 351, 83%, 61%">
                <div class="card-icon">
                  <img
                    src="./assets/images/category-2.svg"
                    width="40"
                    height="40"
                    loading="lazy"
                    alt="Non-Degree Programs"
                    class="img"
                  />
                </div>

                <h3 class="h3">
                  <a href="#" class="card-title">value</a>
                </h3>

                <p class="card-text">Passion</p>
                <p class="card-text">Responsibility</p>
                <p class="card-text">Honesty</p>
                <p class="card-text">Integrity</p>
              </div>
            </li>

            <li class="itemdim">
              <div class="category-card full" style="--color: 229, 75%, 58%">
                <div class="card-icon">
                  <img
                    src="./assets/images/category-3.svg"
                    width="40"
                    height="40"
                    loading="lazy"
                    alt="Off-Campus Programs"
                    class="img"
                  />
                </div>

                <h3 class="h3">
                  <a href="#" class="card-title">Vision</a>
                </h3>

                <p class="card-text">
                  Don't get ripped off because you didn't receive the
                  information!
                </p>
              </div>
            </li>
          </ul>
        </div>
      </section>

      <section
        class="video has-bg-image"
        aria-label="video"
        style="background-image: url('./assets/images/video-bg.png')"
      >
        <div class="container">
          <div class="video-card">
            <div
              class="video-banner img-holder has-after"
              style="--width: ; --height: "
            >
              <img
                src="./assets/images/image8.JPG"
                width="970"
                height="550"
                loading="lazy"
                alt="video banner"
                class="img-cover"
              />

              <button class="play-btn" aria-label="play video">
                <ion-icon name="play" aria-hidden="true"></ion-icon>
              </button>
            </div>

            <img
              src="./assets/images/video-shape-1.png"
              width="1089"
              height="605"
              loading="lazy"
              alt=""
              class="shape video-shape-1"
            />

            <img
              src="./assets/images/video-shape-2.png"
              width="158"
              height="174"
              loading="lazy"
              alt=""
              class="shape video-shape-2"
            />
          </div>
        </div>
      </section>

      <section class="section stats" aria-label="stats">
        <div class="container">
          <ul class="grid-list">
            <li>
              <div class="stats-card" style="--color: 170, 75%, 41%">
                <h3 class="card-title">29.3k</h3>

                <p class="card-text">Student Enrolled</p>
              </div>
            </li>

            <li>
              <div class="stats-card" style="--color: 351, 83%, 61%">
                <h3 class="card-title">32.4K</h3>

                <p class="card-text">Class Completed</p>
              </div>
            </li>

            <li>
              <div class="stats-card" style="--color: 260, 100%, 67%">
                <h3 class="card-title">100%</h3>

                <p class="card-text">Satisfaction Rate</p>
              </div>
            </li>

            <li>
              <div class="stats-card" style="--color: 42, 94%, 55%">
                <h3 class="card-title">354+</h3>

                <p class="card-text">Top Instructors</p>
              </div>
            </li>
          </ul>
        </div>
      </section>

      <section
        class="section blog has-bg-image"
        id="blog"
        aria-label="blog"
        style="background-image: url('./assets/images/blog-bg.svg')"
      >
        <div class="container">
          <p class="section-subtitle">Our Evants</p>

          <h2 class="h2 section-title">Get News With Wintogether</h2>

          <ul class="grid-list">
            <li>
              <div class="blog-card">
                <figure
                  class="card-banner img-holder has-after"
                  style="--width: 370; --height: 370"
                >
                  <img
                    src="./assets/images/event1.png"
                    width="370"
                    height="370"
                    loading="lazy"
                    alt="Become A Better Blogger: Content Planning"
                    class="img-cover"
                  />
                </figure>

                <div class="card-content">
                  <a href="#" class="card-btn" aria-label="read more">
                    <ion-icon
                      name="arrow-forward-outline"
                      aria-hidden="true"
                    ></ion-icon>
                  </a>

                  <a href="#" class="card-subtitle">Online</a>

                  <h3 class="h3">
                    <a href="#" class="card-title"
                      >Become A Better Blogger: Content Planning</a
                    >
                  </h3>

                  <ul class="card-meta-list">
                    <li class="card-meta-item">
                      <ion-icon
                        name="calendar-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">Oct 10, 2021</span>
                    </li>

                    <li class="card-meta-item">
                      <ion-icon
                        name="chatbubbles-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">Com 09</span>
                    </li>
                  </ul>

                  <p class="card-text">
                    Lorem Ipsum Dolor Sit Amet Cons Tetur Adipisicing Sed.
                  </p>
                </div>
              </div>
            </li>

            <li>
              <div class="blog-card">
                <figure
                  class="card-banner img-holder has-after"
                  style="--width: 370; --height: 370"
                >
                  <img
                    src="./assets/images/event2.jpg"
                    width="370"
                    height="370"
                    loading="lazy"
                    alt="Become A Better Blogger: Content Planning"
                    class="img-cover"
                  />
                </figure>

                <div class="card-content">
                  <a href="#" class="card-btn" aria-label="read more">
                    <ion-icon
                      name="arrow-forward-outline"
                      aria-hidden="true"
                    ></ion-icon>
                  </a>

                  <a href="#" class="card-subtitle">Online</a>

                  <h3 class="h3">
                    <a href="#" class="card-title"
                      >Become A Better Blogger: Content Planning</a
                    >
                  </h3>

                  <ul class="card-meta-list">
                    <li class="card-meta-item">
                      <ion-icon
                        name="calendar-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">Oct 10, 2021</span>
                    </li>

                    <li class="card-meta-item">
                      <ion-icon
                        name="chatbubbles-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">Com 09</span>
                    </li>
                  </ul>

                  <p class="card-text">
                    Lorem Ipsum Dolor Sit Amet Cons Tetur Adipisicing Sed.
                  </p>
                </div>
              </div>
            </li>

            <li>
              <div class="blog-card">
                <figure
                  class="card-banner img-holder has-after"
                  style="--width: 370; --height: 370"
                >
                  <img
                    src="./assets/images/event3.png"
                    width="370"
                    height="370"
                    loading="lazy"
                    alt="Become A Better Blogger: Content Planning"
                    class="img-cover"
                  />
                </figure>

                <div class="card-content">
                  <a href="#" class="card-btn" aria-label="read more">
                    <ion-icon
                      name="arrow-forward-outline"
                      aria-hidden="true"
                    ></ion-icon>
                  </a>

                  <a href="#" class="card-subtitle">Online</a>

                  <h3 class="h3">
                    <a href="#" class="card-title"
                      >Become A Better Blogger: Content Planning</a
                    >
                  </h3>

                  <ul class="card-meta-list">
                    <li class="card-meta-item">
                      <ion-icon
                        name="calendar-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">Oct 10, 2021</span>
                    </li>

                    <li class="card-meta-item">
                      <ion-icon
                        name="chatbubbles-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">Com 09</span>
                    </li>
                  </ul>

                  <p class="card-text">
                    Lorem Ipsum Dolor Sit Amet Cons Tetur Adipisicing Sed.
                  </p>
                </div>
              </div>
            </li>
          </ul>

          <img
            src="./assets/images/blog-shape.png"
            width="186"
            height="186"
            loading="lazy"
            alt=""
            class="shape blog-shape"
          />
        </div>
      </section>
      <section class="section course" aria-label="course">
        <div class="container">
          <p class="section-subtitle">Popular Courses</p>

          <h2 class="h2 section-title">Pick A Course To Get Started</h2>

          <ul class="grid-list">
            <li>
              <div class="course-card">
                <figure
                  class="card-banner img-holder"
                  style="--width: 370; --height: 220"
                >
                  <img
                    src="./assets/images/event4.jpg"
                    width="370"
                    height="220"
                    loading="lazy"
                    alt="Build Responsive Real- World Websites with HTML and CSS"
                    class="img-cover"
                  />
                </figure>

                <div class="abs-badge">
                  <ion-icon name="time-outline" aria-hidden="true"></ion-icon>

                  <span class="span">3 Jun 2020</span>
                </div>

                <div class="card-content">
                  <span class="badge">Beginner</span>

                  <h3 class="h3">
                    <a href="#" class="card-title"
                      >Build Responsive Real- World Websites with HTML and
                      CSS</a
                    >
                  </h3>

                  <div class="wrapper">
                    <div class="rating-wrapper">
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                    </div>

                    <p class="rating-text">(5.0/7 Rating)</p>
                  </div>

                  <data class="price" value="35">Free</data>

                  <ul class="card-meta-list">
                    <!-- <li class="card-meta-item">
                      <ion-icon
                        name="library-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">8 Lessons</span>
                    </li> -->

                    <li class="card-meta-item">
                      <ion-icon
                        name="people-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">20 Students</span>
                    </li>
                  </ul>
                </div>
              </div>
            </li>

            <li>
              <div class="course-card">
                <figure
                  class="card-banner img-holder"
                  style="--width: 370; --height: 220"
                >
                  <img
                    src="./assets/images/image6.JPG"
                    width="370"
                    height="220"
                    loading="lazy"
                    alt="Java Programming Masterclass for Software Developers"
                    class="img-cover"
                  />
                </figure>

                <div class="abs-badge">
                  <ion-icon name="time-outline" aria-hidden="true"></ion-icon>

                  <span class="span">3 Jun 2020</span>
                </div>

                <div class="card-content">
                  <span class="badge">Advanced</span>

                  <h3 class="h3">
                    <a href="#" class="card-title"
                      >Java Programming Masterclass for Software Developers</a
                    >
                  </h3>

                  <div class="wrapper">
                    <div class="rating-wrapper">
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                    </div>

                    <p class="rating-text">(4.5 /9 Rating)</p>
                  </div>

                  <data class="price" value="35">Free</data>

                  <ul class="card-meta-list">
                    <!-- <li class="card-meta-item">
                      <ion-icon
                        name="library-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">15 Lessons</span>
                    </li> -->

                    <li class="card-meta-item">
                      <ion-icon
                        name="people-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">35 Students</span>
                    </li>
                  </ul>
                </div>
              </div>
            </li>

            <li>
              <div class="course-card">
                <figure
                  class="card-banner img-holder"
                  style="--width: 370; --height: 220"
                >
                  <img
                    src="./assets/images/image5.JPG"
                    width="370"
                    height="220"
                    loading="lazy"
                    alt="The Complete Camtasia Course for Content Creators"
                    class="img-cover"
                  />
                </figure>

                <div class="abs-badge">
                  <ion-icon name="time-outline" aria-hidden="true"></ion-icon>

                  <span class="span">3 Jun 2020</span>
                </div>

                <div class="card-content">
                  <span class="badge">Intermediate</span>

                  <h3 class="h3">
                    <a href="#" class="card-title"
                      >The Complete Camtasia Course for Content Creators</a
                    >
                  </h3>

                  <div class="wrapper">
                    <div class="rating-wrapper">
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                    </div>

                    <p class="rating-text">(4.9 /7 Rating)</p>
                  </div>

                  <data class="price" value="35">Free</data>

                  <ul class="card-meta-list">
                    <!-- <li class="card-meta-item">
                      <ion-icon
                        name="library-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">13 Lessons</span>
                    </li> -->

                    <li class="card-meta-item">
                      <ion-icon
                        name="people-outline"
                        aria-hidden="true"
                      ></ion-icon>

                      <span class="span">18 Students</span>
                    </li>
                  </ul>
                </div>
              </div>
            </li>
          </ul>

          <!-- <a href="#" class="btn has-before">
            <span class="span">Browse more courses</span>

            <ion-icon name="arrow-forward-outline" aria-hidden="true"></ion-icon>
          </a> -->
        </div>
      </section>
    </article>
  </main>

  <footer
    class="footer"
    style="background-image: url('./assets/images/footer-bg.png')"
    id="footer"
  >
    <div class="footer-top section">
      <div class="container grid-list">
        <div class="footer-brand">
          <a href="#" class="logo">
            <img
              src="./assets/images/logo2.png"
              width="80"
              height="100"
              alt="EduWeb logo"
            />
          </a>

          <p class="footer-brand-text">
            Lorem ipsum dolor amet consecto adi pisicing elit sed eiusm tempor
            incidid unt labore dolore.
          </p>

        

          <div class="wrapper">
            <span class="span">Call:</span>

            <a href="tel:+011234567890" class="footer-link">+261 34 89 195 84</a>
          </div>

          <div class="wrapper">
            <span class="span">Email:</span>

            <a href="mailto:info@eduweb.com" class="footer-link"
              >contact@wintogether.mg</a
            >
          </div>
        </div>

        <ul class="footer-list">
          <li>
            <p class="footer-list-title">Contacts</p>
          </li>













          <li>
            <a href="#" class="footer-link">Win Together Madagasikara</a>
          </li>

          <li>
            <a href="#" class="footer-link">WinTogetherMada</a>
          </li>

          <li>
            <a href="#" class="footer-link">LOT 2086 Bis 3rd Floor</a>
          </li>

          <li>
            <a href="#" class="footer-link">67 Ha Antananarivo Madagascar</a>
          </li>

          <li>
            <a href="#" class="footer-link">contact@wintogether.mg</a>
          </li>

          <li>
            <a href="#" class="footer-link">+261 34 89 195 84</a>
          </li>
        </ul>

        <ul class="footer-list">
          <li>
            <p class="footer-list-title">Links</p>
          </li>

          <li>
            <a href="#" class="footer-link">Home</a>
          </li>
         


          <li>
            <a href="#home" class="footer-link">Our Services</a>
          </li>

          <li>
            <a href="#courses" class="footer-link">About Us</a>
          </li>

          <li>
            <a href="#blog" class="footer-link">Our Events</a>
          </li>

          <li>
            <a href="#footer" class="footer-link">Contact Us</a>
          </li>

        </ul>

        <div class="footer-list">
          <p class="footer-list-title">Messages</p>

          <p class="footer-list-text">
            Enter your email address and name to leave your message
          </p>

        
          <form class="form-container">
            <label for="message" class="label">Your message</label>
            <textarea
              id="message"
              rows="4"
              class="textarea"
              placeholder="Leave a comment..."
            ></textarea>
            
          </form>
          <form action="" class="newsletter-form">
            <input
              type="text"
              name="email_address"
              placeholder="Your Name"
              required
              class="input-field"
            />
            
          </form>
          <form action="" class="newsletter-form">
           
            <input
              type="email"
              name="email_address"
              placeholder="Your email"
              required
              class="input-field"
            />

           
          </form>
          <div class="btnsend">
            <button type="submit" class="btn has-before sendBtn">
              <span class="span">Send</span>

              <ion-icon
                name="arrow-forward-outline"
                aria-hidden="true"
              ></ion-icon>
            </button>
          </div>
          

          <ul class="social-list">
            <li>
              <a href="#" class="social-link">
                <ion-icon name="logo-facebook"></ion-icon>
              </a>
            </li>

            <li>
              <a href="#" class="social-link">
                <ion-icon name="logo-linkedin"></ion-icon>
              </a>
            </li>

            <li>
              <a href="#" class="social-link">
                <ion-icon name="logo-instagram"></ion-icon>
              </a>
            </li>

            <li>
              <a href="#" class="social-link">
                <ion-icon name="logo-twitter"></ion-icon>
              </a>
            </li>

            <li>
              <a href="#" class="social-link">
                <ion-icon name="logo-youtube"></ion-icon>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>

    <div class="footer-bottom">
      <div class="container">
        <p class="copyright">
          Copyright 2025 All Rights Reserved by
          <a href="#" class="copyright-link">FabrinoDev</a>
        </p>
      </div>
    </div>
  </footer>
  <a
    href="#top"
    class="back-top-btn"
    aria-label="back top top"
    data-back-top-btn
  >
    <ion-icon name="chevron-up" aria-hidden="true"></ion-icon>
  </a>
</template>

<style scoped>

.btnsend{

  padding: 10px;

}

.sendBtn{
  width: 100%!important;
}
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
  /* background-color: red; */
  display: flex;
  justify-content: center;
}

.logodiv {
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
body {
  font-family: "Poppins", sans-serif;
}

  /* Conteneur du formulaire */
  .form-container {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    background-color: #f9f9f9;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }

  /* Label */
  .label {
    display: block;
    margin-bottom: 10px;
    font-size: 14px;
    font-weight: 500;
    color: #333;
  }

  /* Textarea */
  .textarea {
    width: 100%;
    padding: 12px;
    font-size: 14px;
    color: #333;
    background-color: #f8f8f8;
    border: 1px solid #ccc;
    border-radius: 8px;
    transition: all 0.3s ease;
    resize: none;
  }

  .textarea::placeholder {
    color: #aaa;
  }

  /* Focus effect */
  .textarea:focus {
    border-color: #007BFF;
    outline: none;
    background-color: #fff;
    box-shadow: 0 0 5px rgba(0, 123, 255, 0.3);
  }

  /* Dark mode */
  @media (prefers-color-scheme: dark) {
    .form-container {
      background-color: #333;
      color: white;
    }

    .label {
      color: #ddd;
    }

    .textarea {
      background-color: #444;
      color: white;
      border: 1px solid #666;
    }

    .textarea::placeholder {
      color: #aaa;
    }

    .textarea:focus {
      border-color: #66b2ff;
      background-color: #555;
      box-shadow: 0 0 5px rgba(102, 178, 255, 0.3);
    }
  }
</style>
