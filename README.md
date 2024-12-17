<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AFOoficial</title>
    <link rel="stylesheet" href="pruebacss.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Rasa:ital,wght@0,300..700;1,300..700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://unpkg.com/swiper@8/swiper-bundle.min.css" />

<link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css?_cacheOverride=1727808415776" rel="stylesheet">

</head>

<body>

    <height-observer variable="announcement-bar">
        <div class="announcement-bar color-scheme color-scheme--scheme-3">
            <div class="announcement-carousel-container">
                <announcement-bar-carousel allow-swipe="" autoplay="5" id="carousel-sections--17275758477500__announcement-bar" class="announcement-bar__carousel">
                    <p class="prose-heading is-selected">ENVIO GRATIS PARA TODAS LAS COMPRAS POR ENCIMA DE LOS S/.200</p>
                </announcement-bar-carousel>
            </div>
        </div>
    </height-observer>

    <header>
        <div class="HEADING">
            <a href="afoweb.html"><img class="logo" src="IMG/Recurso 1.png" alt=""></a> 
                <div class="bag">
                    <i class="bx bx-shopping-bag" style="color:#fff9f9" id="shop-cart"></i>
                </div>
        </div>
    </header>

    //sidebar view//
    <nav class="navbar">
      <button class="menu-button" onclick="toggleSidebar()">
          <div class="menu-icon"></div>
      </button>
  </nav>
  
  <div class="sidebar" id="sidebar">
      <button class="close-button" onclick="toggleSidebar()">×</button>
      <div class="nav-links">
          <a href="afoweb.html">Home</a>
          <a href="aboutus.html">About us</a>
          <a href="#">Services</a>
          <a href="Contacto.html">Contact us</a>
      </div>
  </div>
  
  <div class="overlay" id="overlay" onclick="toggleSidebar()"></div>
  
  
  <script>
      function toggleSidebar() {
          const sidebar = document.getElementById('sidebar');
          const overlay = document.getElementById('overlay');
          
          sidebar.classList.toggle('active');
          overlay.classList.toggle('active');
      }
  </script>
  



    <nav class="headerlinks">
        <a href="afoweb.html" class="nav link">HOME</a>
        
        <a href="aboutus.html" class="nav link">ABOUT US</a>
        
        <a href="Contacto.html" class="nav link">CONTACT US</a>
        
        <a href="UPCOMING.html" class="nav link">UPCOMING</a>
    </nav>


    <section id="tranding">
        
        <div class="container">
          <div class="swiper tranding-slider">
            <div class="swiper-wrapper">
              
              <div class="swiper-slide tranding-slide">
                <div class="tranding-slide-img">
                  <img src="IMG/Grupo 3.jpg" alt="Tranding">
                </div>
                <div class="tranding-slide-content">                
                  <div class="tranding-slide-content-bottom">
                    <h2 class="cloth-name">
                      AFO TANK GREY
                    </h2>
                    <h3 class="cloth-rating">
                      <span>4.5</span>
                      <div class="rating">
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                      </div>
                    </h3>
                  </div>
                </div>
              </div>
              
              <div class="swiper-slide tranding-slide">
                <div class="tranding-slide-img">
                  <img src="IMG/image00001.jpg" alt="Tranding">
                </div>
                <div class="tranding-slide-content">
                  <div class="tranding-slide-content-bottom">
                    <h2 class="cloth-name">
                      AFO TANK BLACK
                    </h2>
                    <h3 class="cloth-rating">
                      <span>4.5</span>
                      <div class="rating">
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                      </div>
                    </h3>
                  </div>
                </div>
              </div>
              

              <div class="swiper-slide tranding-slide">
                <div class="tranding-slide-img">
                  <img src="IMG/image00003.jpg" alt="Tranding">
                </div>               
              </div>

             
              <div class="swiper-slide tranding-slide">
                <div class="tranding-slide-img">
                  <img src="IMG/image00004.jpg" alt="Tranding">
                </div>
                <div class="tranding-slide-content">
                  <div class="tranding-slide-content-bottom">
                    <h2 class="cloth-name">
                      3 PACK
                    </h2>
                    <h3 class="cloth-rating">
                      <span>4.5</span>
                      <div class="rating">
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                      </div>
                    </h3>
                  </div>
                </div>
              </div>
              
              <div class="swiper-slide tranding-slide">
                <div class="tranding-slide-img">
                  <img src="IMG/DSC01938.jpg" alt="Tranding">
                </div>
                <div class="tranding-slide-content">
                  <div class="tranding-slide-content-bottom">
                    <h2 class="cloth-name">
                      AFO COMPRESSION TANK
                    </h2>
                    <h3 class="cloth-rating">
                      <span>5.0</span>
                      <div class="rating">
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                        <ion-icon name="star"></ion-icon>
                      </div>
                    </h3>
                  </div>
                </div>
              </div>


          
            </div>
  
            <div class="tranding-slider-control">
              <div class="swiper-button-prev slider-arrow">
                <ion-icon name="arrow-back-outline"></ion-icon>
              </div>
              <div class="swiper-button-next slider-arrow">
                <ion-icon name="arrow-forward-outline"></ion-icon>
              </div>
              <div class="swiper-pagination"></div>
            </div>
  
          </div>
        </div>
      </section>

      <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
      <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
      <script src="https://unpkg.com/swiper@8/swiper-bundle.min.js"></script>
      <script src="script.js"></script>
      <script src="https://unpkg.com/boxicons@2.1.4/dist/boxicons.js"></script>


          <Div class="B-color">
            <h2 id="intro-collection"><span>LATEST COLLECTION</span></h2>
            <p id="collection-volume">VOL.3</p>

            //productos//

            <section class="store-product">
        
                <div class="shop content">
                    <div class="product-box">
                        <img class="productos" src="IMG/imgbox1.jpg" alt="">
                        <h2 class="product-title">Afo Tank Azul</h2>
                        <span class="price">S/.79.90</span>
                        <img class="add-cart" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAPlJREFUSEvt1T1KA1EUxfFf3IKksBGsrN2B2mhnI+4hYCU2YqOYRlKkintIlU5QCMkKLFyBNlaSHYgf8IbADC83mRBsMtVj7n3nf96ZOzMNK74aK9Y3L+AULRwmQ0P0MIgMzgPo4DIjdIPbWZAIcIZ+ErjDQ1qf4zqtj/Ccg0SAF+zhAt2SyB+gjScc1wV8YeM37yY+SyJb+MAEm3UB32lj7qRRvTJFI+xHkxHUxzgoesrOCkdLMqbGc4DifhRBuV7p/3fAolEtfII1oPIeRFMTRbZ+BlFCwojesR3KzG54w07uW3SCe+zWhLziCo85QE3d/Lboj7Y08Ad9OTMZVmA+TgAAAABJRU5ErkJggg==">
                    </div>
                </div>
        
                <div class="shop content">
                    <div class="product-box">
                        <img class="productos" src="IMG/imgbox2.jpg" alt="">
                        <h2 class="product-title">Afo Tank Negro</h2>
                        <span class="price">S/.79.90</span>
                        <img class="add-cart" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAPlJREFUSEvt1T1KA1EUxfFf3IKksBGsrN2B2mhnI+4hYCU2YqOYRlKkintIlU5QCMkKLFyBNlaSHYgf8IbADC83mRBsMtVj7n3nf96ZOzMNK74aK9Y3L+AULRwmQ0P0MIgMzgPo4DIjdIPbWZAIcIZ+ErjDQ1qf4zqtj/Ccg0SAF+zhAt2SyB+gjScc1wV8YeM37yY+SyJb+MAEm3UB32lj7qRRvTJFI+xHkxHUxzgoesrOCkdLMqbGc4DifhRBuV7p/3fAolEtfII1oPIeRFMTRbZ+BlFCwojesR3KzG54w07uW3SCe+zWhLziCo85QE3d/Lboj7Y08Ad9OTMZVmA+TgAAAABJRU5ErkJggg==">
        
                    </div>
                </div>
        
                <div class="shop content">
                    <div class="product-box">
                        <img class="productos" src="IMG/imgbox3.jpg" alt="">
                        <h2 class="product-title">Afo Tank Gris</h2>
                        <span class="price">S/.79.90</span>
                        <img class="add-cart" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAPlJREFUSEvt1T1KA1EUxfFf3IKksBGsrN2B2mhnI+4hYCU2YqOYRlKkintIlU5QCMkKLFyBNlaSHYgf8IbADC83mRBsMtVj7n3nf96ZOzMNK74aK9Y3L+AULRwmQ0P0MIgMzgPo4DIjdIPbWZAIcIZ+ErjDQ1qf4zqtj/Ccg0SAF+zhAt2SyB+gjScc1wV8YeM37yY+SyJb+MAEm3UB32lj7qRRvTJFI+xHkxHUxzgoesrOCkdLMqbGc4DifhRBuV7p/3fAolEtfII1oPIeRFMTRbZ+BlFCwojesR3KzG54w07uW3SCe+zWhLziCo85QE3d/Lboj7Y08Ad9OTMZVmA+TgAAAABJRU5ErkJggg==">
        
                    </div>
                </div>
        
                <div class="shop content">
                    <div class="product-box">
                        <img class="productos" src="IMG/imgbox4.jpg" alt="">
                        <h2 class="product-title">Afo Compression Tank</h2>
                        <span class="price">S/.129.90</span>
                        <img class="add-cart" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAPlJREFUSEvt1T1KA1EUxfFf3IKksBGsrN2B2mhnI+4hYCU2YqOYRlKkintIlU5QCMkKLFyBNlaSHYgf8IbADC83mRBsMtVj7n3nf96ZOzMNK74aK9Y3L+AULRwmQ0P0MIgMzgPo4DIjdIPbWZAIcIZ+ErjDQ1qf4zqtj/Ccg0SAF+zhAt2SyB+gjScc1wV8YeM37yY+SyJb+MAEm3UB32lj7qRRvTJFI+xHkxHUxzgoesrOCkdLMqbGc4DifhRBuV7p/3fAolEtfII1oPIeRFMTRbZ+BlFCwojesR3KzG54w07uW3SCe+zWhLziCo85QE3d/Lboj7Y08Ad9OTMZVmA+TgAAAABJRU5ErkJggg==">
        
                    </div>
                </div> 
                
                <div class="shop content">
                  <div class="product-box">
                      <img class="productos" src="IMG/imgbox6.JPG" alt="">
                      <h2 class="product-title">Afo Compression white</h2>
                      <span class="price">S/.129.90</span>
                      <img class="add-cart" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAPlJREFUSEvt1T1KA1EUxfFf3IKksBGsrN2B2mhnI+4hYCU2YqOYRlKkintIlU5QCMkKLFyBNlaSHYgf8IbADC83mRBsMtVj7n3nf96ZOzMNK74aK9Y3L+AULRwmQ0P0MIgMzgPo4DIjdIPbWZAIcIZ+ErjDQ1qf4zqtj/Ccg0SAF+zhAt2SyB+gjScc1wV8YeM37yY+SyJb+MAEm3UB32lj7qRRvTJFI+xHkxHUxzgoesrOCkdLMqbGc4DifhRBuV7p/3fAolEtfII1oPIeRFMTRbZ+BlFCwojesR3KzG54w07uW3SCe+zWhLziCo85QE3d/Lboj7Y08Ad9OTMZVmA+TgAAAABJRU5ErkJggg==">
      
                  </div>
              </div>
              
              <div class="shop content">
                <div class="product-box">
                    <img class="productos" src="IMG/imgbox5.jpg" alt="">
                    <h2 class="product-title">Afo Compression black</h2>
                    <span class="price">S/.129.90</span>
                    <img class="add-cart" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAPlJREFUSEvt1T1KA1EUxfFf3IKksBGsrN2B2mhnI+4hYCU2YqOYRlKkintIlU5QCMkKLFyBNlaSHYgf8IbADC83mRBsMtVj7n3nf96ZOzMNK74aK9Y3L+AULRwmQ0P0MIgMzgPo4DIjdIPbWZAIcIZ+ErjDQ1qf4zqtj/Ccg0SAF+zhAt2SyB+gjScc1wV8YeM37yY+SyJb+MAEm3UB32lj7qRRvTJFI+xHkxHUxzgoesrOCkdLMqbGc4DifhRBuV7p/3fAolEtfII1oPIeRFMTRbZ+BlFCwojesR3KzG54w07uW3SCe+zWhLziCo85QE3d/Lboj7Y08Ad9OTMZVmA+TgAAAABJRU5ErkJggg==">
    
                </div>
            </div>

            <div class="shop content">
              <div class="product-box">
                  <img class="productos" src="IMG/DSC07992.jpg" alt="">
                  <h2 class="product-title">Blank space short black</h2>
                  <span class="price">S/.90.00</span>
                  <img class="add-cart" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAPlJREFUSEvt1T1KA1EUxfFf3IKksBGsrN2B2mhnI+4hYCU2YqOYRlKkintIlU5QCMkKLFyBNlaSHYgf8IbADC83mRBsMtVj7n3nf96ZOzMNK74aK9Y3L+AULRwmQ0P0MIgMzgPo4DIjdIPbWZAIcIZ+ErjDQ1qf4zqtj/Ccg0SAF+zhAt2SyB+gjScc1wV8YeM37yY+SyJb+MAEm3UB32lj7qRRvTJFI+xHkxHUxzgoesrOCkdLMqbGc4DifhRBuV7p/3fAolEtfII1oPIeRFMTRbZ+BlFCwojesR3KzG54w07uW3SCe+zWhLziCo85QE3d/Lboj7Y08Ad9OTMZVmA+TgAAAABJRU5ErkJggg==">
  
              </div>
          </div>

          <div class="shop content">
            <div class="product-box">
                <img class="productos" src="IMG/DSC08000.jpg" alt="">
                <h2 class="product-title">Blank space short grey</h2>
                <span class="price">S/.90.00</span>
                <img class="add-cart" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAPlJREFUSEvt1T1KA1EUxfFf3IKksBGsrN2B2mhnI+4hYCU2YqOYRlKkintIlU5QCMkKLFyBNlaSHYgf8IbADC83mRBsMtVj7n3nf96ZOzMNK74aK9Y3L+AULRwmQ0P0MIgMzgPo4DIjdIPbWZAIcIZ+ErjDQ1qf4zqtj/Ccg0SAF+zhAt2SyB+gjScc1wV8YeM37yY+SyJb+MAEm3UB32lj7qRRvTJFI+xHkxHUxzgoesrOCkdLMqbGc4DifhRBuV7p/3fAolEtfII1oPIeRFMTRbZ+BlFCwojesR3KzG54w07uW3SCe+zWhLziCo85QE3d/Lboj7Y08Ad9OTMZVmA+TgAAAABJRU5ErkJggg==">

            </div>
        </div>

        <div class="shop content">
          <div class="product-box">
              <img class="productos" src="IMG/DSC08022.jpg" alt="">
              <h2 class="product-title">Blank space short navy blue</h2>
              <span class="price">S/.90.00</span>
              <img class="add-cart" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAPlJREFUSEvt1T1KA1EUxfFf3IKksBGsrN2B2mhnI+4hYCU2YqOYRlKkintIlU5QCMkKLFyBNlaSHYgf8IbADC83mRBsMtVj7n3nf96ZOzMNK74aK9Y3L+AULRwmQ0P0MIgMzgPo4DIjdIPbWZAIcIZ+ErjDQ1qf4zqtj/Ccg0SAF+zhAt2SyB+gjScc1wV8YeM37yY+SyJb+MAEm3UB32lj7qRRvTJFI+xHkxHUxzgoesrOCkdLMqbGc4DifhRBuV7p/3fAolEtfII1oPIeRFMTRbZ+BlFCwojesR3KzG54w07uW3SCe+zWhLziCo85QE3d/Lboj7Y08Ad9OTMZVmA+TgAAAABJRU5ErkJggg==">

          </div>
      </div>
    </Div>


    <main class="grid-container">

      <article class="grid-item grid-item-featured">
          <img 
              src="IMG/imgbox6.JPG" 
              alt="Featured Image" 
              class="grid-item-image"
          >
          <div class="grid-item-content">
              <h2 class="grid-item-title">ESSENTIALS</h2>
              <p class="grid-item-description">
                  Los escenciales y favoritos de nuestros compradores
              </p>
          </div>
      </article>


      <article class="grid-item">
        <a href="Contacto.html"></a>
          <img 
              src="IMG/Vertical (2).jpg" 
              alt="Grid Item 1" 
              class="grid-item-image"
          >
          <div class="grid-item-content">
              <h2 class="grid-item-title">CONTACT US</h2>
              <p class="grid-item-description">
                  nuestro contacto directo
              </p>
          </div>
      </article>

      <article class="grid-item">
          <img 
              src="IMG/GRUNGE_15.jpg" 
              alt="Grid Item 2" 
              class="grid-item-image"
          >
          <div class="grid-item-content">
              <h2 class="grid-item-title">THE AESTHETICS</h2>

          </div>
      </article>

      <article class="grid-item">
          <img 
              src="IMG/black.JPG" 
              alt="Grid Item 3" 
              class="grid-item-image"
          >
          <div class="grid-item-content">
              <h2 class="grid-item-title">UPCOMING</h2>
              <p class="grid-item-description">
                  Nuevos lanzamientos
              </p>
          </div>
      </article>

      <article class="grid-item">
          <img 
              src="IMG/imgbox1.jpg" 
              alt="Grid Item 4" 
              class="grid-item-image"
          >
          <div class="grid-item-content">
              <h2 class="grid-item-title">HOME</h2>
              <p class="grid-item-description">
                  Vuelve al inicio
              </p>
          </div>
      </article>
  </main>

  <footer class="footer">
    <div class="footer-container">
        <div class="footer-content">
            <div class="footer-section">
                <h3>Sobre nosotros</h3>
                <p>Estamos dedicados a brindar servicios y productos de alta calidad a nuestros clientes. Nuestra misión es superar expectativas y crear relaciones duraderas con ellos.</p>
            </div>

            <div class="footer-section">
                <h3>Contact Us</h3>
                <ul class="contact-info">
                    <li>📍 Conquistadores 918, San Isidro</li>
                    <li>🌆 Lima, 15074</li>
                    <li>📞 (51) 987-263-991</li>
                    <li>✉️ comunityafo@gmail.com</li>
                </ul>
            </div>

            <div class="footer-section">
                <h3>Disponibilidad de horario</h3>
                <ul class="contact-info">
                    <li>Lunes - Viernes: 9:00 AM - 6:00 PM</li>
                    <li>Sabado: 10:00 AM - 4:00 PM</li>
                    <li>Domingo: Closed</li>
                </ul>
            </div>
        </div>

        <div class="footer-bottom">
            <p>&copy; 2024 ALL FOR ONE. Todos los derechos reservados.</p>
        </div>
    </div>
</footer>
            </section>
  </section>
    

















</body>
</html>
