<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Taxi Ermua — Servicio Profesional</title>
  <meta name="description" content="Taxi profesional en Ermua. Traslados a aeropuertos, estaciones, recorridos locales y servicio 24/7. Hablamos euskera, castellano e inglés.">
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{--accent:#0b6e4f;--muted:#6b7280;--bg:#f7f7f8;--card:#ffffff}
    *{box-sizing:border-box}
    body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; margin:0; background:var(--bg); color:#0f172a; line-height:1.45}
    .container{width:min(1100px,94%);margin:0 auto;padding:28px 0}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#06634a);display:flex;align-items:center;justify-content:center;color:white;font-weight:700}
    nav a{margin-left:16px;color:var(--muted);text-decoration:none;font-weight:600}
    .hero{display:grid;grid-template-columns:1fr 360px;gap:24px;align-items:center;margin-top:28px}
    .card{background:var(--card);padding:20px;border-radius:14px;box-shadow:0 6px 18px rgba(12,20,30,0.06)}
    h1{margin:0;font-size:28px}
    p.lead{color:var(--muted);margin-top:10px}
    .cta{display:flex;gap:10px;margin-top:16px}
    .btn{padding:10px 14px;border-radius:10px;border:0;cursor:pointer;font-weight:700}
    .btn-primary{background:var(--accent);color:white}
    .btn-ghost{background:transparent;border:1px solid #e6e6e9;color:var(--muted)}

    .services{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:18px}
    .service{padding:12px;border-radius:10px;background:linear-gradient(180deg,#fff,#fbfbfb);border:1px solid #efefef}
    .small{font-size:13px;color:var(--muted)}

    aside.contact{position:sticky;top:20px}
    .lang-badges{display:flex;gap:8px;margin-top:12px}
    .badge{padding:6px 10px;border-radius:999px;background:#f1f5f9;font-weight:600;font-size:13px}

    section{margin-top:22px}
    .grid-2{display:grid;grid-template-columns:1fr 1fr;gap:14px}
    footer{margin-top:28px;padding:18px 0;color:var(--muted);font-size:14px;text-align:center}

    /* responsive */
    @media (max-width:880px){
      .hero{grid-template-columns:1fr}
      .services{grid-template-columns:repeat(2,1fr)}
      .grid-2{grid-template-columns:1fr}
      nav{display:none}
    }
  </style>
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "TaxiService",
    "name": "Taxi Ermua - Tiziano Ronchetti",
    "image": "",
    "telephone": "+34 6XXXXXXXX",
    "areaServed": "Ermua, País Vasco, España",
    "description": "Servicio de taxi profesional en Ermua: traslados a aeropuertos, estaciones, rutas locales y servicios por horas. Hablamos euskera, castellano e inglés.",
    "openingHours": "Mo,Tu,We,Th,Fr,Sa,Su 00:00-23:59"
  }
  </script>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">T</div>
        <div>
          <div style="font-weight:700">Taxi Ermua</div>
          <div class="small">Servicio profesional • 24/7 • Hablamos euskera</div>
        </div>
      </div>
      <nav>
        <a href="#servicios">Servicios</a>
        <a href="#idiomas">Idiomas</a>
        <a href="#sobre-mi">Sobre mí</a>
        <a href="#contacto">Contacto</a>
      </nav>
    </header>

    <main>
      <div class="hero">
        <div class="card">
          <h1>Taxi Ermua — Transporte fiable y cercano</h1>
          <p class="lead">Traslados a aeropuertos, estaciones, viajes interurbanos, servicios por horas y transporte de pequeños paquetes. Atención personalizada y puntualidad en cada traslado.</p>

          <div class="cta">
            <a href="tel:+34600000000" class="btn btn-primary">Llamar ahora</a>
            <a href="https://wa.me/34600000000" class="btn btn-ghost" target="_blank" rel="noopener">WhatsApp</a>
          </div>

          <div class="services" id="servicios" aria-label="Servicios">
            <div class="service">
              <strong>Traslados a aeropuertos</strong>
              <div class="small">Bilbao (BIO), Vitoria (VIT), San Sebastián (EAS)</div>
            </div>
            <div class="service">
              <strong>Estaciones y conexiones</strong>
              <div class="small">Conexiones a trenes y autobuses, espera incluida.</div>
            </div>
            <div class="service">
              <strong>Rutas locales y excursiones</strong>
              <div class="small">Visitas por la comarca, reservas para eventos y bodas.</div>
            </div>
            <div class="service">
              <strong>Servicios por horas</strong>
              <div class="small">Reserva por horas para gestiones o acompañamiento.</div>
            </div>
            <div class="service">
              <strong>Transporte de paquetería</strong>
              <div class="small">Pequeños envíos urgentes dentro de la provincia.</div>
            </div>
            <div class="service">
              <strong>Servicios corporativos</strong>
              <div class="small">Facturación y contratos para empresas.</div>
            </div>
          </div>

          <section id="idiomas">
            <h3>Idiomas</h3>
            <div class="lang-badges">
              <div class="badge">Euskera (Euskara) — Nativo</div>
              <div class="badge">Castellano — Nativo</div>
              <div class="badge">Inglés — Nivel conversacional</div>
            </div>
            <p class="small" style="margin-top:10px">Si necesitas atención en otro idioma, pregúntame al reservar: intento facilitar siempre la comunicación.</p>
          </section>

        </div>

        <aside class="contact">
          <div class="card">
            <h3 id="contacto">Contacto & Reserva</h3>
            <p class="small">Teléfono y WhatsApp para reservas rápidas. También puedes usar el formulario abajo.</p>
            <p style="margin:12px 0;font-weight:700">Tel: <a href="tel:+34600000000">+34 600 000 000</a></p>
            <p style="margin:6px 0;font-weight:700">WhatsApp: <a href="https://wa.me/34600000000" target="_blank">Enviar mensaje</a></p>
            <p style="margin:6px 0;font-weight:700">Email: <a href="mailto:taxi@ermua.example">taxi@ermua.example</a></p>

            <hr style="margin:12px 0;border:none;border-top:1px solid #f0f0f0">
            <strong>Horario</strong>
            <div class="small">Servicio 24/7 — disponibilidad según demanda</div>
            <div style="margin-top:10px;text-align:center">
              <a class="btn btn-primary" href="#formulario">Reservar online</a>
            </div>
          </div>

          <div style="height:18px"></div>

          <div class="card">
            <h4>Ubicación</h4>
            <div class="small">Ermua, Debabarrena — País Vasco</div>
            <!-- Replace iframe src if you prefer a different map or a lighter solution -->
            <div style="margin-top:10px;border-radius:8px;overflow:hidden">
              <iframe src="https://www.google.com/maps?q=Ermua,+Spain&output=embed" width="100%" height="180" style="border:0" loading="lazy"></iframe>
            </div>
          </div>
        </aside>
      </div>

      <section class="card" style="margin-top:18px">
        <h3 id="sobre-mi">Sobre mí</h3>
        <div class="grid-2" style="align-items:start">
          <div>
            <p class="small">Me llamo [Nombre del conductor], conductor con X años de experiencia en el sector local. Conozco la comarca y las rutas con precisión; ofrezco servicios con trato cercano, discreto y profesional.</p>

            <h4 style="margin-top:14px">Compromisos</h4>
            <ul class="small">
              <li>Puntualidad garantizada</li>
              <li>Vehículo limpio y con mantenimiento al día</li>
              <li>Facturación y opciones para empresas</li>
              <li>Atención personalizada y respeto por la privacidad</li>
            </ul>
          </div>
          <div>
            <h4>Tarifas orientativas</h4>
            <p class="small">Las tarifas dependen de distancia y destino. A modo orientativo:</p>
            <ul class="small">
              <li>Tarifa mínima local: 4,50€ (sujeto a ordenanzas municipales)</li>
              <li>Ermua → Bilbao (aprox.): desde 60€</li>
              <li>Esperas: tarifa por minuto según acuerdo</li>
            </ul>
            <p class="small" style="margin-top:8px">Nota: Sustituye estas cifras por tus tarifas reales o el enlace a la ordenanza municipal si aplica.</p>
          </div>
        </div>
      </section>

      <section class="card" style="margin-top:18px">
        <h3>Reseñas de clientes</h3>
        <p class="small">"Servicio perfecto, puntual y muy atento." — Ana M.</p>
        <p class="small">"Nos llevó al aeropuerto sin problemas; el conductor muy amable." — Koldo E.</p>
        <p class="small">Puedes añadir aquí reseñas reales importadas de Google o testimonios.</p>
      </section>

      <section class="card" style="margin-top:18px" id="formulario">
        <h3>Formulario de reserva</h3>
        <form id="bookingForm">
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px">
            <input required placeholder="Nombre" name="name" style="padding:10px;border-radius:8px;border:1px solid #e6e6e6">
            <input required placeholder="Teléfono" name="phone" style="padding:10px;border-radius:8px;border:1px solid #e6e6e6">
            <input placeholder="Email (opcional)" name="email" style="padding:10px;border-radius:8px;border:1px solid #e6e6e6">
            <input required placeholder="Fecha y hora" name="datetime" type="datetime-local" style="padding:10px;border-radius:8px;border:1px solid #e6e6e6">
          </div>
          <textarea name="details" placeholder="Origen → Destino / Comentarios" style="width:100%;margin-top:10px;padding:10px;border-radius:8px;border:1px solid #e6e6e6"></textarea>
          <div style="display:flex;gap:10px;margin-top:12px">
            <button type="submit" class="btn btn-primary">Enviar reserva</button>
            <button type="button" id="clearBtn" class="btn btn-ghost">Limpiar</button>
          </div>
          <p id="result" class="small" style="margin-top:10px;color:var(--muted)"></p>
        </form>
        <p class="small" style="margin-top:8px">Este formulario no envía datos a ningún servidor. Copia el HTML y conéctalo a tu servicio preferido (email, Google Forms, Zapier, o un backend simple) para recibir reservas.</p>
      </section>

    </main>

    <footer>
      © <span id="year"></span> Taxi Ermua — Todos los derechos reservados • Actualiza datos de contacto en el HTML
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();

    const form = document.getElementById('bookingForm');
    const result = document.getElementById('result');

    form.addEventListener('submit', (e)=>{
      e.preventDefault();
      const data = new FormData(form);
      // Validación mínima
      if(!data.get('name') || !data.get('phone') || !data.get('datetime')){
        result.textContent = 'Rellena los campos obligatorios (nombre, teléfono y fecha/hora).';
        return;
      }
      // Mostrar resumen y aconsejar integración
      result.textContent = 'Reserva recibida (simulada). Copia los datos manualmente o conecta el formulario a un backend para procesar solicitudes.';
      // Aquí podrías añadir envío por fetch a tu servidor si lo activas.
      form.reset();
    });

    document.getElementById('clearBtn').addEventListener('click',()=>{form.reset();result.textContent='';});
  </script>
</body>
</html>
