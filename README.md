<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="css/index2.css" />
    <link rel="stylesheet" href="css/normalize.css" />
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    <title>Mrdj Online</title>
  </head>
  <body>
    <header>
      <nav class="nav collapsible">
        <a class="nav__brand" href="#"><img src="icons/logo.svg" alt="" /></a>
        <svg class="icon icon--white nav__toggler">
          <use xlink:href="icons/sprite.svg#menu"></use>
        </svg>
        <ul class="list nav__list collapsible__content">
          <li class="nav__items"><a href="#">Home</a></li>
          <li class="nav__items"><a href="#">About</a></li>
          <li class="nav__items"><a href="#">Price</a></li>
          <li class="nav__items"><a href="#">Testimonials</a></li>
        </ul>
      </nav>
    </header>
    <section class="block block--dark block--skewed--right hero">
      <div class="container grid grid--1x2">
        <header class="block__header hero__content" data-aos="fade-right">
          <h1 class="block__heading hero__heading">WELCOME TO Mrdj</h1>
          <p class="hero__tagline">Mrdj company, since 1980's, Bangalore</p>
          <a href="#" class="btn btn--accent btn--stretched">get started</a>
        </header>
        <picture data-aos="fade-left">
          <source
            type="image/webp"
            srcset="images/banner@1x.webp 1x, images/banner@2x.webp 2x" />
          <source
            type="image/png"
            srcset="images/banner@1x.png 1x, images/banner@2x.png 2x" />
          <img class="hero__image" src="images/banner.png" alt=""
        /></picture>
      </div>
    </section>
    <section class="block container block--domain">
      <header class="block__header" data-aos="fade-up">
        <h2 class="block__heading">Starting Price at $9 Per Month</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam,
          vel.
        </p>
      </header>
      <div class="input--group" data-aos="flip-up">
        <input type="text" class="input" placeholder="Enter your domain name" />
        <button class="btn btn--accent">
          <svg class="icon icon--primary">
            <use xlink:href="icons/sprite.svg#search"></use>
          </svg>
          Search
        </button>
      </div>
      <ul class="list block--domain__prices" data-aos="zoom-in">
        <li><span class="badge badge--secondary">.com $10</span></li>
        <li>.sg $11</li>
        <li>.space $12</li>
        <li>.org $13</li>
        <li>.co $14</li>
        <li>.nt $15</li>
      </ul>
    </section>
    <section class="block container block--plans">
      <div class="grid grid--1x3" data-aos="zoom-in">
        <div class="plan">
          <div class="card">
            <header class="card__header card--secondary">
              <h3 class="plan__name">Entry</h3>
              <span class="plan__price">$14</span>
              <span class="plan__billingCycle">/month</span>
              <span class="badge badge--secondary badge--small">10% off</span>
              <span class="plan__description">Easy to start on the cloud</span>
            </header>
            <div class="card__body">
              <ul class="list list--tick">
                <li class="list__item">Unlimited Websites</li>
                <li class="list__item">Unlimited Bandwidth</li>
                <li class="list__item">100 GB SSD Storage</li>
                <li class="list__item">3 Gb RAM</li>
              </ul>
              <button class="btn btn--outline btn--block">buy now</button>
            </div>
          </div>
        </div>
        <div class="plan plan--popular">
          <div class="card">
            <header class="card__header card--primary">
              <h3 class="plan__name">Entry</h3>
              <span class="plan__price">$14</span>
              <span class="plan__billingCycle">/month</span>
              <span class="badge badge--primary badge--small">10% off</span>
              <span class="plan__description">Easy to start on the cloud</span>
            </header>
            <div class="card__body">
              <ul class="list list--tick">
                <li class="list__item">Unlimited Websites</li>
                <li class="list__item">Unlimited Bandwidth</li>
                <li class="list__item">100 GB SSD Storage</li>
                <li class="list__item">3 Gb RAM</li>
              </ul>
              <button class="btn btn--outline btn--block">buy now</button>
            </div>
          </div>
        </div>
        <div class="plan">
          <div class="card">
            <header class="card__header card--secondary">
              <h3 class="plan__name">Entry</h3>
              <span class="plan__price">$14</span>
              <span class="plan__billingCycle">/month</span>
              <span class="badge badge--secondary badge--small">10% off</span>
              <span class="plan__description">Easy to start on the cloud</span>
            </header>
            <div class="card__body">
              <ul class="list list--tick">
                <li class="list__item">Unlimited Websites</li>
                <li class="list__item">Unlimited Bandwidth</li>
                <li class="list__item">100 GB SSD Storage</li>
                <li class="list__item">3 Gb RAM</li>
              </ul>
              <button class="btn btn--outline btn--block">buy now</button>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="block container" data-aos="zoom-in-down">
      <header class="block__header">
        <h2 class="block__heading">Host On The Cloud to Keep Growing</h2>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Est,
          reprehenderit?
        </p>
      </header>
      <article class="grid grid--1x2 feature">
        <div class="feature__content" data-aos="fade-right">
          <span class="icon--container">
            <svg class="icon icon--primary">
              <use xlink:href="icons/sprite.svg#easy"></use>
            </svg>
          </span>
          <h3 class="feature__heading">Super Easy to use</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima quis
            possimus facere mollitia maiores magni et quas eaque ad suscipit.
          </p>
          <a href="#" class="link--arrow">learn more</a>
        </div>
        <picture data-aos="fade-left">
          <source
            type="image/webp"
            srcset="images/easy@1x.webp 1x, images/easy@2x.webp 2x"
          />
          <source
            type="image/jpg"
            srcset="images/easy@1x.jpg 1x, images/easy@2x.jpg 2x"
          />
          <img class="feature__image" src="images/easy.jpg" alt="" />
        </picture>
      </article>

      <article class="grid grid--1x2 feature">
        <div class="feature__content" data-aos="fade-left">
          <span class="icon--container">
            <svg class="icon icon--primary">
              <use xlink:href="icons/sprite.svg#easy"></use>
            </svg>
          </span>
          <h3 class="feature__heading">Super Easy to use</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima quis
            possimus facere mollitia maiores magni et quas eaque ad suscipit.
          </p>
          <a href="#" class="link--arrow">learn more</a>
        </div>
        <picture data-aos="fade-right">
          <source
            type="image/webp"
            srcset="images/easy@1x.webp 1x, images/easy@2x.webp 2x"
          />
          <source
            type="image/jpg"
            srcset="images/easy@1x.jpg 1x, images/easy@2x.jpg 2x"
          />
          <img class="feature__image" src="images/easy.jpg" alt="" />
        </picture>
      </article>

      <article class="grid grid--1x2 feature">
        <div class="feature__content" data-aos="fade-right">
          <span class="icon--container">
            <svg class="icon icon--primary">
              <use xlink:href="icons/sprite.svg#easy"></use>
            </svg>
          </span>
          <h3 class="feature__heading">Super Easy to use</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima quis
            possimus facere mollitia maiores magni et quas eaque ad suscipit.
          </p>
          <a href="#" class="link--arrow">learn more</a>
        </div>
        <picture data-aos="fade-left">
          <source
            type="image/webp"
            srcset="images/easy@1x.webp 1x, images/easy@2x.webp 2x"
          />
          <source
            type="image/jpg"
            srcset="images/easy@1x.jpg 1x, images/easy@2x.jpg 2x"
          />
          <img class="feature__image" src="images/easy.jpg" alt="" />
        </picture>
      </article>
    </section>
    <section
      class="block block--dark block--skewed--left block--showcase"
      data-aos="zoom-out-up"
    >
      <header class="block__header">
        <h2>User-Friendly Control Panel</h2>
      </header>
      <div class="container grid grid--1x2">
        <picture class="block--showcase__image">
          <source
            type="image/webp"
            srcset="images/ipad.webp 1x, images/ipad@2x.webp 2x"
          />
          <source
            type="image/png"
            srcset="images/ipad.png 1x, images/ipad@2x.png 2x"
          />

          <img src="images/ipad.png" alt="ipad-image" />
        </picture>
        <ul class="list">
          <li>
            <div class="media">
              <div class="media__image">
                <svg class="icon icon--primary">
                  <use xlink:href="icons/sprite.svg#snap"></use>
                </svg>
              </div>
              <div class="media__body">
                <h3 class="media__title showcase__media__title">
                  Easy Start & Managed Updates
                </h3>
                <p class="showcase__media__paragraph">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit. In
                  quos nostrum numquam eaque similique ipsum ab explicabo quasi
                  fugit aliquid?
                </p>
              </div>
            </div>
          </li>
          <li>
            <div class="media">
              <div class="media__image">
                <svg class="icon icon--primary">
                  <use xlink:href="icons/sprite.svg#snap"></use>
                </svg>
              </div>
              <div class="media__body">
                <h3 class="media__title showcase__media__title">
                  Easy Start & Managed Updates
                </h3>
                <p>
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit. In
                  quos nostrum numquam eaque similique ipsum ab explicabo quasi
                  fugit aliquid?
                </p>
              </div>
            </div>
          </li>
          <li>
            <div class="media">
              <div class="media__image">
                <svg class="icon icon--primary">
                  <use xlink:href="icons/sprite.svg#snap"></use>
                </svg>
              </div>
              <div class="media__body">
                <h3 class="media__title showcase__media__title">
                  Easy Start & Managed Updates
                </h3>
                <p>
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit. In
                  quos nostrum numquam eaque similique ipsum ab explicabo quasi
                  fugit aliquid?
                </p>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </section>
    <section class="block" data-aos="zoom-in">
      <header class="block__header">
        <h2 class="block__heading">What out customer are telling</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur,
          sequi.
        </p>
      </header>
      <div class="container">
        <div class="card testimonial">
          <div class="grid grid--1x2">
            <div class="testimonial__image">
              <img src="images/testimonial.jpg" alt="a customer smiling face" />
              <span class="icon--container icon--container--accent">
                <svg class="icon icon--white icon--small">
                  <use xlink:href="icons/sprite.svg#quotes"></use>
                </svg>
              </span>
            </div>
            <blockquote class="quote">
              <p class="quote__text">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Expedita molestias distinctio qui sequi accusamus perspiciatis
                obcaecati culpa facere sunt? Dolorem?
              </p>

              <footer class="quote__footer">
                <div class="media">
                  <div class="media__image">
                    <svg class="icon icon--primary quote__line">
                      <use xlink:href="icons/sprite.svg#line"></use>
                    </svg>
                  </div>
                  <div class="media__body">
                    <h3 class="media__title quote__author">Joel fernando</h3>
                    <p class="media__company quote__companyName">
                      Bread of life
                    </p>
                  </div>
                </div>
              </footer>
            </blockquote>
          </div>
        </div>
      </div>
    </section>
    <footer class="block block--dark footer">
      <div class="grid container footer__sections">
        <section class="collapsible collapsible--expanded footer__section">
          <div class="collapsible__header footer__header">
            <h2 class="collapsible__heading footer__heading">Products</h2>
            <svg class="icon icon--white collapsible__chevron">
              <use xlink:href="icons/sprite.svg#chevron"></use>
            </svg>
          </div>
          <div class="collapsible__content">
            <ul class="list footer__content">
              <li><a href="#">Website hosting</a></li>
              <li><a href="#">Free Automated Wordpress</a></li>
              <li><a href="#">Migrations</a></li>
            </ul>
          </div>
        </section>

        <section class="collapsible footer__section">
          <div class="collapsible__header">
            <h2 class="collapsible__heading footer__heading">Company</h2>
            <svg class="icon icon--white collapsible__chevron">
              <use xlink:href="icons/sprite.svg#chevron"></use>
            </svg>
          </div>
          <div class="collapsible__content">
            <ul class="list footer__content">
              <li><a href="#">About</a></li>
              <li><a href="#">Affiliates</a></li>
              <li><a href="#">Blog</a></li>
            </ul>
          </div>
        </section>

        <section class="collapsible footer__section">
          <div class="collapsible__header">
            <h2 class="collapsible__heading footer__heading">Support</h2>
            <svg class="icon icon--white collapsible__chevron">
              <use xlink:href="icons/sprite.svg#chevron"></use>
            </svg>
          </div>
          <div class="collapsible__content">
            <ul class="list footer__content">
              <li><a href="#">Contact</a></li>
              <li><a href="#">Knowledge Base</a></li>
              <li><a href="#">FAQ</a></li>
            </ul>
          </div>
        </section>

        <section class="collapsible footer__section">
          <div class="collapsible__header">
            <h2 class="collapsible__heading footer__heading">Domains</h2>
            <svg class="icon icon--white collapsible__chevron">
              <use xlink:href="icons/sprite.svg#chevron"></use>
            </svg>
          </div>
          <div class="collapsible__content">
            <ul class="list footer__content">
              <li><a href="#">Domain Checker</a></li>
              <li><a href="#">Domain Transfer</a></li>
              <li><a href="#">Free Domain</a></li>
            </ul>
          </div>
        </section>

        <section class="footer__brand">
          <img src="images/logo.svg" alt="logo" />
          <p class="footer__brand__copyright">Copyrights @2020 MRDJ</p>
        </section>
      </div>
    </footer>

    <script src="js/main.js"></script>
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
      AOS.init();
    </script>
  </body>
</html>
