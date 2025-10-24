<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Clínica Veterinaria Dra. Pink | Cuidado y amor para tus mascotas</title>
  <meta name="description" content="Dra. Pink - Clínica veterinaria en SMP. Consultas, vacunas, peluquería y emergencias. Atención con cariño para perros y gatos. Agenda por WhatsApp +51 988 277 398." />
  <meta name="keywords" content="veterinaria, Dra Pink, clínica veterinaria, vacunas mascotas, SMP, San Martín de Porres, Lima" />

  <!-- Google Font Poppins -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <!-- Theme color for mobile -->
  <meta name="theme-color" content="#F9C9D4" />

  <!-- JSON-LD LocalBusiness -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "VeterinaryCare",
    "name": "Clínica Veterinaria Dra. Pink",
    "telephone": "+51988277398",
    "address": {
      "@type": "PostalAddress",
      "streetAddress": "Av. Fray Bartolomé de las Casas 168, Urb. Los Jardines",
      "addressLocality": "San Martín de Porres",
      "addressRegion": "Lima",
      "addressCountry": "PE"
    },
    "url": "https://dra-pink-vet.netlify.app/",
    "description": "Clínica veterinaria Dra. Pink: consultas, vacunación, desparasitación, peluquería y emergencias. Cuidado con ternura.",
    "openingHours": "Mo,Tu,We,Th,Fr 09:00-19:00"
  }
  </script>

  <style>
    :root{
      --pink-1: #F9C9D4;
      --pink-2: #E77CA5;
      --lilac:  #D9C4F3;
      --accent: #E77CA5;
      --text: #3a2b2f;
      --card: rgba(255,255,255,0.6);
      --glass: rgba(255,255,255,0.55);
      --radius: 16px;
      font-family: 'Poppins', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }

    /* Reset & base */
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      background: linear-gradient(180deg, var(--pink-1) 0%, var(--lilac) 100%);
      line-height:1.4;
    }

    a{color:inherit; text-decoration:none}

    /* Container */
    .site{
      max-width:1100px;
      margin:0 auto;
      padding:20px;
    }

    /* Header */
    header{
      display:flex;
      align-items:center;
      justify-content:center; /* center logo */
      gap:20px;
      padding:12px 0;
      position:sticky;
      top:0;
      z-index:50;
      backdrop-filter: blur(6px);
      background: linear-gradient(180deg, rgba(255,255,255,0.35), rgba(255,255,255,0.12));
      border-bottom: 1px solid rgba(255,255,255,0.4);
    }
    .logo{
      display:flex;
      align-items:center;
      gap:12px;
      justify-content:center;
    }
    .logo img{
      height:68px;
      width:auto;
      border-radius:12px;
      object-fit:contain;
      background:transparent;
      padding:6px;
    }

    /* Nav */
    nav{
      display:flex;
      gap:18px;
      margin-left: 20px;
      align-items:center;
    }
    nav a{
      font-weight:600;
      padding:8px 10px;
      border-radius:10px;
      transition:all .18s ease;
      font-size:15px;
    }
    nav a:hover{background:rgba(255,255,255,0.25)}

    /* Hero */
    .hero{
      display:flex;
      gap:20px;
      align-items:center;
      justify-content:space-between;
      margin:24px 0;
      padding:28px;
      border-radius:24px;
      background: linear-gradient(90deg, rgba(255,255,255,0.45), rgba(255,255,255,0.2));
      box-shadow: 0 8px 30px rgba(0,0,0,0.06);
    }
    .hero-left{
      flex:1;
    }
    .hero h1{
      margin:0 0 12px;
      font-size:28px;
      line-height:1.05;
    }
    .hero p{margin:0 0 18px; opacity:0.95}
    .cta{
      display:inline-flex;
      align-items:center;
      gap:10px;
      background:var(--accent);
      color:white;
      padding:12px 16px;
      border-radius:12px;
      font-weight:700;
      box-shadow: 0 6px 18px rgba(231,124,165,0.28);
    }
    .cta svg{filter:drop-shadow(0 4px 8px rgba(0,0,0,0.08))}

    .hero-right{
      width:220px;
      text-align:center;
    }
    .hero-right img{max-width:100%; border-radius:14px; box-shadow:0 8px 20px rgba(0,0,0,0.06)}

    /* Services */
    .services{
      display:grid;
      grid-template-columns:repeat(2,1fr);
      gap:16px;
      margin:28px 0;
    }
    .card{
      background:var(--glass);
      padding:14px;
      border-radius:14px;
