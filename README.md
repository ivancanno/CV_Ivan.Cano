
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Currículum — Iván Cano</title>
  <style>
    /* ---------- ESTILOS GENERALES ---------- */
    :root {
      --primary: #2563eb;
      --light: #f8fafc;
      --text-dark: #1e293b;
      --text-light: #475569;
      --border: #e2e8f0;
      --card: #ffffff;
      --radius: 12px;
      font-family: "Inter", "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    }

    body {
      margin: 0;
      background: var(--light);
      color: var(--text-dark);
      display: flex;
      justify-content: center;
      padding: 40px 16px;
    }

    .cv-container {
      display: flex;
      flex-direction: row;
      background: var(--card);
      max-width: 960px;
      width: 100%;
      border-radius: var(--radius);
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
      overflow: hidden;
    }

    /* ---------- COLUMNA IZQUIERDA ---------- */
    aside {
      background: #eaf1ff;
      width: 300px;
      padding: 32px 24px;
    }

    .name {
      font-size: 1.8rem;
      font-weight: 700;
      color: var(--primary);
      margin: 0;
    }

    .subtitle {
      margin: 4px 0 16px 0;
      font-weight: 600;
      color: var(--text-dark);
    }

    .section-title {
      margin-top: 28px;
      font-size: 0.9rem;
      text-transform: uppercase;
      letter-spacing: 0.6px;
      font-weight: 700;
      color: var(--text-light);
      border-bottom: 1px solid var(--border);
      padding-bottom: 4px;
    }

    .contact p {
      margin: 8px 0;
      font-size: 0.9rem;
      color: var(--text-light);
    }

    .contact a {
      color: var(--primary);
      text-decoration: none;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
      margin-top: 8px;
    }

    .skill {
      background: var(--primary);
      color: white;
      padding: 5px 10px;
      border-radius: 20px;
      font-size: 0.8rem;
      font-weight: 600;
    }

    ul.clean {
      padding-left: 16px;
      margin: 8px 0;
      color: var(--text-light);
      font-size: 0.9rem;
    }

    /* ---------- COLUMNA DERECHA ---------- */
    main {
      flex: 1;
      padding: 32px;
    }

    h2 {
      margin-top: 0;
      font-size: 1.2rem;
      color: var(--primary);
      border-bottom: 2px solid var(--primary);
      display: inline-block;
      padding-bottom: 4px;
    }

    .desc {
      color: var(--text-light);
      line-height: 1.6;
      font-size: 0.95rem;
    }

    .job, .edu {
      margin-bottom: 20px;
    }

    .job-title, .edu-title {
      font-weight: 600;
      font-size: 1rem;
    }

    .job-meta, .edu-meta {
      font-size: 0.85rem;
      color: var(--text-light);
      margin-bottom: 4px;
    }

    footer {
      text-align: center;
      font-size: 0.8rem;
      color: var(--text-light);
      border-top: 1px solid var(--border);
      padding-top: 10px;
      margin-top: 20px;
    }

    /* ---------- RESPONSIVE ---------- */
    @media (max-width: 768px) {
      .cv-container {
        flex-direction: column;
      }
      aside {
        width: 100%;
      }
    }
  </style>
</head>

<body>
  <div class="cv-container">
    <aside>
      <h1 class="name">Iván Cano</h1>
      <p class="subtitle">ADE y Gastronomía<br>Máster en Business analytics e IA</p>

      <div class="section-title">Contacto</div>
      <div class="contact">
        <p>📧 <a href="mailto:i.cano1sei@gmail.com">i.cano1sei@gmail.com</a></p>
        <p>📞 <a href="tel:+34722353683">+34 722 35 36 83</a></p>
        <p>📍 Arroyomolinos, Madrid</p>
      </div>

      <div class="section-title">Habilidades</div>
      <div class="skills">
        <span class="skill">Resolutivo</span>
        <span class="skill">Comunicativo</span>
        <span class="skill">Analítico</span>
        <span class="skill">Curioso</span>
        <span class="skill">Proactivo</span>
        <span class="skill">Motivador</span>
        <span class="skill">Influyente</span>
      </div>

      <div class="section-title">Conocimientos</div>
      <ul class="clean">
        <li>Manejo básico de SAP y Jamovi</li>
        <li>Comprensión básica de Python</li>
        <li>Creación de modelos de Machine Learning</li>
        <li>Manejo avanzado de Excel</li>
      </ul>

      <div class="section-title">Idiomas</div>
      <p class="desc">Inglés — Nivel B2 (Cambridge, 2016)</p>
    </aside>

    <main>
      <h2>Perfil</h2>
      <p class="desc">
        Titulado en Administración y Dirección de Empresas y Gastronomía con mención en Dirección y Gestión Hotelera.
        Apasionado por la gestión empresarial, la innovación y el análisis de datos aplicados al sector hostelero.
      </p>

      <h2>Experiencia laboral</h2>

      <div class="job">
        <div class="job-title">Administrativo comercial (prácticas) — Real Casino de Madrid</div>
        <div class="job-meta">Nov 2023 – Ene 2024</div>
        <p class="desc">Presentación de tarifas, asesoramiento a clientes y gestión administrativa de eventos y presupuestos.</p>
      </div>

      <div class="job">
        <div class="job-title">Cocinero en prácticas — Terraza de Paco Roncero (2⭐ Michelin)</div>
        <div class="job-meta">Sep 2023 – Nov 2023</div>
        <p class="desc">Apoyo en la preparación y ejecución de menús de alta gastronomía bajo estándares Michelin.</p>
      </div>

      <div class="job">
        <div class="job-title">Jefe de cocina sustituto — Aula de naturaleza Emilio Hurtado</div>
        <div class="job-meta">Jul 2023 – Ago 2023</div>
        <p class="desc">Responsable de la gestión de cocina y coordinación del personal.</p>
      </div>

      <div class="job">
        <div class="job-title">Profesor particular — Física y Matemáticas</div>
        <div class="job-meta">2019 – 2022</div>
        <p class="desc">Impartición de clases personalizadas a estudiantes de ESO y Bachillerato.</p>
      </div>

      <h2>Formación académica</h2>

      <div class="edu">
        <div class="edu-title">Grado en ADE — Universidad Francisco de Vitoria</div>
        <div class="edu-meta">2020 – 2025</div>
      </div>

      <div class="edu">
        <div class="edu-title">Grado en Gastronomía (Dirección y Gestión Hotelera) — UFV</div>
        <div class="edu-meta">2020 – 2024</div>
      </div>

      <div class="edu">
        <div class="edu-title">Máster en Inteligencia Artificial aplicada a la Analítica de Negocio — UFV</div>
        <div class="edu-meta">2025 – 2026</div>
      </div>

      <footer>
        © 2025 Iván Cano — Currículum Vitae
      </footer>
    </main>
  </div>
</body>
</html>
