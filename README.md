# jomuz.github.io
Pagina Web Iris Computer
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Iris Computer</title>
    <link rel="stylesheet" href="..\estilos\estilo1.css" />
  </head>
  <body>
    <header class="header">
      <div class="header-container">
        <div class="header-left">
          <img
            src="..\imagenes\logo de iris.png"
            alt="Logo de la Tienda"
            class="logo"
          />
          <nav class="nav">
            <div class="dropdown">
              <button class="dropdown-btn">Categorías</button>
              <div class="dropdown-content">
                <a href="#">Laptops</a>
                <a href="#">PCs de Escritorio</a>
                <a href="#">Componentes</a>
                <a href="#">Monitores</a>
              </div>
            </div>
            <a href="#" class="nav-link">Sobre Nosotros</a>
            <a href="catalogo.html" class="nav-link">Productos</a>
            <a href="contactos.html" class="nav-link">Contactos</a>
          </nav>
        </div>
        <div class="header-center">
          <form action="busqueda.html" method="GET">
            <input
              type="search"
              name="q"
              placeholder="Buscar productos..."
              class="search-bar"
            />
          </form>
        </div>

 <div class="header-right">
          <a href="iniciosesion.html" class="nav-link"
            >Iniciar Sesión / Registrarse</a
          >
          <a href="#" class="nav-link">🛒</a>
        </div>
      </div>

  <div id="notification-message" class="notification-popup">
        <p>✅ ¡Suscrito exitosamente!</p>
        <p>Recibirás nuestras mejores ofertas pronto.</p>
    </div>
    <script src="..\SCRIPTS\script1.js"></script>
    </header>

  <main>
      <section class="slider">
        <div class="slide">
          <img
            src="..\imagenes\curvo oferta xiaomi.webp"
            alt="Monitor Curvo Xiaomi"
          />
        </div>
        <div class="slide">
          <img src="..\imagenes\teclado oferta.webp" alt="Teclado Gamer" />
        </div>
        <div class="slide">
          <img src="..\imagenes\mouse oferta.webp" alt="Mouse ReDragon" />
        </div>
      </section>

   <section class="value-proposition">
        <div class="value-item">
          <span class="icon">🚀</span>
          <h3>Envío Rápido y Seguro</h3>
          <p>Recibe tus componentes en tiempo récord.</p>
        </div>
        <div class="value-item">
          <span class="icon">🛡️</span>
          <h3>Garantía de 12 Meses</h3>
          <p>Cobertura total contra defectos de fábrica.</p>
        </div>
        <div class="value-item">
          <span class="icon">💲</span>
          <h3>Precios Competitivos</h3>
          <p>Calidad premium al mejor precio del mercado.</p>
        </div>
        <div class="value-item">
          <span class="icon">💳</span>
          <h3>Múltiples Pagos</h3>
          <p>Aceptamos tarjetas de débito, crédito y transferencias.</p>
        </div>
      </section>

  <section class="flash-sale">
        <h2>🔥 Oferta Flash - Solo Hoy 🔥</h2>
        <div class="sale-content">
          <img src="..\imagenes\ryzen 7 4700g.webp" alt="Producto en Oferta" />
          <div class="sale-details">
            <h3>Procesador Ryzen 7 4700G</h3>
            <p class="old-price">Bs. 2200</p>
            <p class="new-price">Bs. 1800</p>
            <a href="#" class="buy-btn">¡Comprar Ahora!</a>
            <div class="countdown">
              Tiempo restante: <span id="timer">00:00:00</span>
            </div>
          </div>
        </div>
      </section>

  <section class="recommended-products">
        <h2>Productos Recomendados</h2>
        <div class="products-grid">
          <div class="product-card">
            <img src="..\imagenes\ryzen 7 4700g.webp" alt="Laptop Gamer" />
            <h3>RYZEN 7 4700G</h3>
            <p>Bs. 1800</p>
          </div>
          <div class="product-card">
            <img
              src="..\imagenes\asus prime b550 wifi.webp"
              alt="Monitor Curvo"
            />
            <h3>ASUS PRIME B550M-A WIFI"</h3>
            <p>Bs. 1880</p>
          </div>
          <div class="product-card">
            <img
              src="..\imagenes\ventus rtx 5080.webp"
              alt="Teclado Mecánico"
            />
            <h3>MSI VENTUS 3X RTX 5080</h3>
            <p>Bs. 25800</p>
          </div>
          <div class="product-card">
            <img
              src="..\imagenes\corsair bronze.webp"
              alt="Mouse Inalámbrico"
            />
            <h3>CORSAIR CX650 Bronze</h3>
            <p>Bs. 898</p>
          </div>
        </div>
      </section>
<section class="testimonials">
            <h2>Lo que dicen nuestros clientes</h2>
            <div class="testimonial-grid">
                <div class="testimonial-card">
                    <p>"Excelente servicio y los mejores precios en La Paz. La calidad de los componentes es insuperable."</p>
                    <p class="client-name">⭐⭐⭐⭐⭐ Juan P.</p>
                </div>
                <div class="testimonial-card">
                    <p>"Mi nueva PC gamer corre todo a ultra. ¡Gracias Iris Computer por el armado profesional y rápido!"</p>
                    <p class="client-name">⭐⭐⭐⭐⭐ María F.</p>
                </div>
                <div class="testimonial-card">
                    <p>"Fácil de comprar y el envío a Santa Cruz fue rapidísimo. El monitor llegó en perfectas condiciones."</p>
                    <p class="client-name">⭐⭐⭐⭐⭐ Carlos S.</p>
                </div>
            </div>
        </section>
        
  <section class="newsletter">
            <h2>¡No te pierdas ninguna oferta!</h2>
            <p>Suscríbete a nuestro boletín para recibir descuentos exclusivos y novedades.</p>
            <form action="#" method="POST" class="newsletter-form">
                <input type="email" name="email" placeholder="Ingresa tu correo electrónico..." required>
                <button type="submit">Suscribirme</button>
            </form>
        </section>

<section class="social-media">
        <h2>Síguenos en nuestras redes</h2>
        <div class="iframe-container">
          <iframe
            src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FIrisComputerBolivia&tabs=timeline&width=340&height=500&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
            width="340"
            height="400"
            style="border: none; overflow: hidden"
          ></iframe>
          <iframe
            src="https://www.instagram.com/iriscomputerbolivia/embed"
            width="340"
            height="400"
          ></iframe>
          <iframe
            src="https://www.tiktok.com/embed/@iriscomputer?lang=es-419&referrer=https%3A%2F%2Fwww.iriscomputer.bo%2F"
            width="340"
            heigth="400"
          ></iframe>
        </div>
      </section>
    </main>

  <footer class="footer">
      <p>&copy; 2025 Iris computer. Todos los derechos reservados.</p>
    </footer>

<script src="..\SCRIPTS\script1.js"></script>
  </body>
</html>
