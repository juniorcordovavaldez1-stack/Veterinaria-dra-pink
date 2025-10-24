<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="theme-color" content="#F9C9D4" />

  <title>Clínica Veterinaria Dra. Pink | Cuidado y amor para tus mascotas</title>
  <meta name="description" content="Dra. Pink - Clínica veterinaria en SMP. Consultas, vacunación, peluquería y urgencias. Agenda por WhatsApp +51 988 277 398" />
  <meta name="keywords" content="veterinaria, Dra Pink, mascotas, Lima, San Martín de Porres, vacunación, peluquería canina" />

  <!-- Open Graph -->
  <meta property="og:title" content="Clínica Veterinaria Dra. Pink" />
  <meta property="og:description" content="Cuidado y amor para tus mascotas. Agenda por WhatsApp +51 988 277 398" />
  <meta property="og:type" content="website" />

  <!-- Google font Poppins -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --rosa-pastel:#F9C9D4;
      --rosa-fuerte:#E77CA5;
      --lila:#D9C4F3;
      --fondo:#FFF6FA;
      --texto:#3a2a2f;
      --accent:#E77CA5;
    }
    *{box-sizing:border-box}
    body{font-family:'Poppins',system-ui,Arial; margin:0; color:var(--texto); background: linear-gradient(180deg,var(--rosa-pastel),var(--lila));}
    a{color:inherit; text-decoration:none}

    /* Header */
    header{display:flex;flex-direction:column;align-items:center;gap:12px;padding:18px 20px}
    .logo{display:flex;align-items:center;justify-content:center}
    .logo img{width:110px;height:auto}
    nav{display:flex;gap:18px;flex-wrap:wrap;justify-content:center}
    nav a{padding:8px 12px;border-radius:12px;font-weight:600}
    nav a:hover{background:rgba(255,255,255,0.18)}

    /* Hero */
    .hero{max-width:1100px;margin:12px auto;padding:28px;text-align:center;background:rgba(255,255,255,0.28);border-radius:18px;backdrop-filter:blur(4px)}
    .hero h1{font-size:clamp(24px,5vw,40px);margin:6px 0}
    .hero p{margin:8px 0 18px;font-size:clamp(14px,2.6vw,18px)}
    .btn{display:inline-block;padding:12px 18px;border-radius:999px;background:var(--accent);color:white;font-weight:700}

    /* Services */
    .services{max-width:1100px;margin:28px auto;display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:16px;padding:0 16px}
    .card{background:white;padding:18px;border-radius:14px;box-shadow:0 6px 18px rgba(0,0,0,0.06);text-align:center}
    .card h3{margin:8px 0 4px}
    .card p{font-size:14px;color:#59474b}

    /* About */
    .about{max-width:900px;margin:28px auto;padding:18px;text-align:center}

    /* Location */
    .location{max-width:1100px;margin:28px auto;padding:18px;background:rgba(255,255,255,0.28);border-radius:12px}
    .map{width:100%;height:320px;border-radius:12px;overflow:hidden}
    .address{display:flex;flex-direction:column;gap:6px;padding:12px}

    /* Footer */
    footer{margin-top:30px;padding:18px;text-align:center;font-size:14px;color:#5a3f46}

    /* WhatsApp floating */
    .whatsapp{position:fixed;right:18px;bottom:18px;width:60px;height:60px;border-radius:50%;background:#25D366;display:flex;align-items:center;justify-content:center;box-shadow:0 8px 20px rgba(0,0,0,0.2);z-index:999}
    .whatsapp img{width:34px}

    /* Responsive tweaks */
    @media(min-width:900px){
      header{flex-direction:row;justify-content:space-between;padding:20px 36px}
      nav{order:2}
      .logo{order:1}
    }

    @media(max-width:480px){
      .hero{padding:18px}
      .map{height:220px}
    }
  </style>

  <!-- Structured data (Organization) -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"LocalBusiness",
    "name":"Clínica Veterinaria Dra. Pink",
    "telephone":"+51 988277398",
    "image":"https://dra-pink-vet.netlify.app/assets/logo.png",
    "address":{
      "@type":"PostalAddress",
      "streetAddress":"Av. Fray Bartolomé de las Casas 168",
      "addressLocality":"San Martín de Porres",
      "addressRegion":"Lima",
      "postalCode":"",
      "addressCountry":"PE"
    },
    "url":"https://dra-pink-vet.netlify.app/"
  }
  </script>
</head>
<body>
  <header>
    <div class="logo">
      <!-- Logo centered -->
      <img src="/assets/logo.png" alt="Logo Dra. Pink" />
    </div>

    <nav aria-label="Menú principal">
      <a href="#inicio">Inicio</a>
      <a href="#servicios">Servicios</a>
      <a href="#nosotros">Nosotros</a>
      <a href="#ubicacion">Ubicación</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <main>
    <section id="inicio" class="hero">
      <h1>Clínica Veterinaria Dra. Pink</h1>
      <p>Cuidamos a tus mascotas con amor y ternura. Atención profesional y servicios integrales en San Martín de Porres.</p>
      <a class="btn" href="https://wa.me/51988277398?text=Hola%20Dra.%20Pink%2C%20quiero%20agendar%20una%20cita">Agenda tu cita por WhatsApp</a>
    </section>

    <section id="servicios" class="services">
      <div class="card">
        <h3>Consultas y chequeos</h3>
        <p>Evaluaciones completas para detectar y prevenir problemas de salud.</p>
      </div>
      <div class="card">
        <h3>Vacunación</h3>
        <p>Protocolos de vacunación actualizados para perros y gatos.</p>
      </div>
      <div class="card">
        <h3>Desparasitación</h3>
        <p>Programas seguros y efectivos para mantener a tu mascota saludable.</p>
      </div>
      <div class="card">
        <h3>Peluquería y estética</h3>
        <p>Cortes, baños y aseo con productos de calidad y cariño.</p>
      </div>
      <div class="card">
        <h3>Emergencias</h3>
        <p>Atención prioritaria para casos urgentes y soporte profesional.</p>
      </div>
    </section>

    <section id="nosotros" class="about">
      <h2>Sobre Dra. Pink</h2>
      <p>En Dra. Pink creemos que cada mascota merece un trato especial. Nuestro equipo combina experiencia clínica con un enfoque afectuoso y personalizado. Trabajamos con cariño para devolver a tu mascota su mejor salud.</p>
    </section>

    <section id="ubicacion" class="location">
      <h2>Ubicación</h2>
      <div class="address">
        <strong>Av. Fray Bartolomé de las Casas 168, Urb. Los Jardines, San Martín de Porres, Lima</strong>
        <span>Horario: Lun - Vie: 9:00 - 19:00 | Sáb: 9:00 - 13:00</span>
        <a href="https://maps.google.com/maps?q=Av+Fray+Bartolom%C3%A9+de+las+Casas+168+Urb+Los+Jardines+San+Martin+de+Porres+Lima&z=15" target="_blank" rel="noopener">Abrir en Google Maps</a>
      </div>

      <div class="map" aria-hidden="false">
        <iframe
          src="https://maps.google.com/maps?q=Av+Fray+Bartolom%C3%A9+de+las+Casas+168+Urb+Los+Jardines+San+Martin+de+Porres+Lima&z=15&output=embed"
          width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
      </div>
    </section>

    <section id="contacto" class="about">
      <h2>Contacto</h2>
      <p>Teléfono / WhatsApp: <a href="https://wa.me/51988277398">+51 988 277 398</a></p>
      <p>Síguenos en nuestras redes: <a href="#">Instagram</a> · <a href="#">Facebook</a></p>
    </section>
  </main>

  <footer>
    <small>© 2025 Clínica Veterinaria Dra. Pink — Hecho con 💗 en Perú</small>
  </footer>

  <!-- WhatsApp floating button -->
  <a class="whatsapp" href="https://wa.me/51988277398?text=Hola%20Dra.%20Pink%2C%20quiero%20agendar%20una%20cita" target="_blank" aria-label="Chatear por WhatsApp">
    <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'><path fill='%23ffffff' d='M20.52 3.48A11.93 11.93 0 0012 .5 11.93 11.93 0 003.48 3.48 11.93 11.93 0 00.5 12c0 2.1.55 4.14 1.6 5.96L.5 23.5l5.69-1.49A11.93 11.93 0 0012 23.5c3.2 0 6.19-1.25 8.45-3.51A11.93 11.93 0 0023.5 12c0-3.2-1.25-6.19-3.51-8.45zM12 21c-1.86 0-3.63-.5-5.18-1.44l-.37-.22-3.38.88.91-3.28-.24-.38A9 9 0 113 12a8.9 8.9 0 01.5-3.08L3.7 9.1c.1.2.29.31.5.29l2.02-.18c.32 0 .62.12.85.34l1.6 1.48c.21.2.31.49.28.79l-.15 1.98c-.02.32.1.63.33.86l2.22 2.22c.24.24.56.36.88.34.35 0 .69-.13.95-.38l1.13-1.13c.26-.25.4-.6.4-.97 0-.35-.13-.69-.38-.95l-1.93-1.93c-.24-.24-.34-.57-.28-.9l.27-1.7c.07-.43.4-.77.83-.88l2.4-.57c.2-.05.42.02.57.17.15.15.22.36.18.57l-.57 2.4c-.11.43-.45.76-.88.83l-1.7.27c-.33.06-.66-.04-.9-.28L9.4 8.02C9.15 7.77 8.8 7.64 8.44 7.7 7.78 7.8 7.15 8.03 6.55 8.38 6.07 8.66 5.8 9.19 5.89 9.74c.13.78.46 1.53.98 2.2.52.67 1.2 1.2 1.97 1.57.77.36 1.61.5 2.44.38.37-.05.73-.18 1.04-.38l.94-.6c.32-.21.75-.2 1.05.03l1.28.93c.35.25.8.3 1.18.13.37-.17.64-.52.71-.93.09-.5-.09-1.02-.49-1.38l-1.16-.98c-.28-.24-.33-.66-.12-.96l1.06-1.36c.25-.33.2-.8-.12-1.08-.57-.51-1.26-.92-1.99-1.21-.99-.4-2.03-.52-3.06-.34-.86.15-1.69.49-2.38 1.01-.43.33-.95.52-1.5.52-.7 0-1.38-.29-1.88-.79l-1.47-1.47C6.83 6.05 5.96 5.76 5.1 6c-.22.06-.43.16-.61.29C2.64 7.6 2 9.73 2 12c0 5.52 4.48 10 10 10 2.27 0 4.4-.64 6.71-1.99.13-.07.24-.18.32-.31l.02-.02.02-.02z'/></svg>" alt="WhatsApp"/>
  </a>

  <script>
    // Smooth scroll for internal links
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click',function(e){
        e.preventDefault();
        const target=document.querySelector(this.getAttribute('href'));
        if(target) target.scrollIntoView({behavior:'smooth',block:'start'});
      });
    });
  </script>
</body>
</html>
