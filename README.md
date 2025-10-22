<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Perfil — Estudiante DAW | Desarrollador Web</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#94a3b8;--accent:#06b6d4}
    *{box-sizing:border-box;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial}
    body{margin:0;background:linear-gradient(180deg,#071024 0%,#071a2a 100%);color:#e6eef6;line-height:1.4}
    .container{max-width:960px;margin:40px auto;padding:24px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);border:1px solid rgba(255,255,255,0.04);backdrop-filter:blur(6px);border-radius:14px;padding:20px}

    .hero{display:flex;gap:20px;align-items:center}
    .avatar{width:120px;height:120px;border-radius:50%;overflow:hidden;border:3px solid rgba(255,255,255,0.06)}
    .avatar img{width:100%;height:100%;object-fit:cover;display:block}

    .hero h1{margin:0 0 6px 0;font-size:22px}
    .hero p{margin:0;color:var(--muted)}

    .gif-banner{margin:18px 0;border-radius:10px;overflow:hidden}
    .gif-banner img{width:100%;height:auto;display:block}

    .grid{display:grid;grid-template-columns:1fr 300px;gap:18px;margin-top:16px}
    @media (max-width:880px){.grid{grid-template-columns:1fr}}

    .about,.projects{padding:14px}
    .skills{background:linear-gradient(90deg, rgba(255,255,255,0.02), transparent);padding:12px;border-radius:10px}
    .skill-list{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}
    .skill{padding:6px 10px;background:rgba(255,255,255,0.03);border-radius:8px;font-size:13px;color:var(--muted)}

    .projects-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:10px}
    @media (max-width:640px){.projects-grid{grid-template-columns:1fr}}
    .proj{background:rgba(255,255,255,0.02);padding:10px;border-radius:8px}
    .proj h4{margin:0 0 6px 0;font-size:15px}
    .proj p{margin:0;color:var(--muted);font-size:13px}

    .contact{margin-top:12px;padding:12px;text-align:center}
    .btn{display:inline-block;padding:10px 14px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#0ea5a3);color:#042027;text-decoration:none;font-weight:600}

    footer{margin-top:18px;color:var(--muted);font-size:13px;text-align:center}

    /* small ribbon for GitHub profile READMEs */
    .ribbon{position:absolute;right:0;top:0}
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div style="position:relative">
        <!-- Replace the avatar.png and banner.gif with your own files or URLs -->
        <div class="hero">
          <div class="avatar">
            <img src="https://images.unsplash.com/photo-1527980965255-d3b416303d12?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Avatar estudiante">
          </div>
          <div>
            <h1>Juan Pérez — Estudiante DAW • Desarrollador Web en formación</h1>
            <p>Apasionado por JavaScript, HTML y CSS. Construyendo proyectos para aprender y mostrar en GitHub. Buscando prácticas y colaboraciones.</p>
            <div style="margin-top:8px;color:var(--muted);font-size:13px">📍 Madrid · 🎓 1º DAW · ⌨️ Teclado 60%</div>
          </div>
        </div>

        <div class="gif-banner">
          <!-- Animated banner / GIF -->
          <img src="https://media.giphy.com/media/3o7btPCcdNniyf0ArS/giphy.gif" alt="GIF banner animado">
        </div>

        <div class="grid">
          <div>
            <section class="about">
              <h3>Sobre mí</h3>
              <p>Soy estudiante de Desarrollo de Aplicaciones Web (DAW). Me encanta crear interfaces limpias, aprender nuevas librerías (React, Vue) y mejorar mis conocimientos en desarrollo front-end y back-end.</p>

              <div style="margin-top:12px" class="skills">
                <strong>Habilidades</strong>
                <div class="skill-list">
                  <span class="skill">HTML</span>
                  <span class="skill">CSS</span>
                  <span class="skill">JavaScript</span>
                  <span class="skill">Git & GitHub</span>
                  <span class="skill">Node.js</span>
                  <span class="skill">React (básico)</span>
                  <span class="skill">SQL</span>
                </div>
              </div>

              <div style="margin-top:12px">
                <strong>Objetivo</strong>
                <p style="margin:6px 0;color:var(--muted)">Publicar proyectos de calidad en GitHub, contribuir a proyectos open source y conseguir una primera experiencia profesional como desarrollador web.</p>
              </div>
            </section>

            <section class="projects" style="margin-top:12px">
              <h3>Proyectos destacados</h3>
              <div class="projects-grid">
                <div class="proj">
                  <h4>Escape Room Web</h4>
                  <p>Juego en JavaScript que simula puzzles interactivos en el navegador. (Proyecto del curso)</p>
                </div>
                <div class="proj">
                  <h4>RSS & Atom Generator</h4>
                  <p>Pequeña herramienta en Node.js para crear feeds RSS/Atom automáticamente.</p>
                </div>
                <div class="proj">
                  <h4>Landing Responsiva</h4>
                  <p>Landing desarrollada con HTML y CSS moderno (flexbox & grid).</p>
                </div>
                <div class="proj">
                  <h4>Mini API REST</h4>
                  <p>API en Express para gestionar reservas de un chiringuito (POO aplicado).</p>
                </div>
              </div>
            </section>
          </div>

          <aside style="padding:14px">
            <div style="background:rgba(255,255,255,0.02);padding:12px;border-radius:10px">
              <h3>Contacto</h3>
              <p style="margin:6px 0;color:var(--muted)">Puedes encontrarme en GitHub y LinkedIn — o enviarme un email.</p>
              <div style="display:flex;flex-direction:column;gap:8px;margin-top:8px">
                <a class="btn" href="#" target="_blank">GitHub: @tu-usuario</a>
                <a class="btn" href="#" style="background:linear-gradient(90deg,#60a5fa,#7c3aed);color:white">LinkedIn</a>
              </div>
            </div>

            <div style="margin-top:12px;padding:12px;background:rgba(255,255,255,0.02);border-radius:10px">
              <h4>Tips para el README</h4>
              <ul style="margin:6px 0 0 18px;color:var(--muted)">
                <li>Usa imágenes optimizadas (≤200 KB).</li>
                <li>Añade GIFs cortos para mostrar tu proyecto en acción.</li>
                <li>Incluye enlaces a repositorios y demo en vivo.</li>
              </ul>
            </div>

            <div style="margin-top:12px;text-align:center;color:var(--muted)">
              <small>Este HTML está listo para editar: cambia textos, imágenes y enlaces por los tuyos.</small>
            </div>
          </aside>
        </div>

        <footer>
          © "Tu Nombre" — Estudiante DAW • Generado para perfil de GitHub
        </footer>
      </div>
    </div>
  </div>
</body>
</html>
