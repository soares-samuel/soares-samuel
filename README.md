### Olá, eu sou Samuel Soares! 👋

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samuel Soares | Backend Developer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --bg-color: #0d1117;
            --text-color: #c9d1d9;
            --accent-color: #58a6ff;
            --card-bg: #161b22;
            --border-color: #30363d;
            --highlight: #238636; /* Verde GitHub */
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth; /* Rolagem suave */
        }
        .container { max-width: 900px; margin: 0 auto; padding: 20px; }
        
        /* Header */
        header { text-align: center; padding: 80px 0 40px; }
        h1 { font-size: 3rem; margin: 0; color: #fff; letter-spacing: -1px; }
        .subtitle { font-size: 1.3rem; color: var(--accent-color); font-family: monospace; margin-top: 10px; }
        .tagline { margin-top: 15px; color: #8b949e; max-width: 600px; margin-left: auto; margin-right: auto; }
        
        section { padding: 50px 0; border-bottom: 1px solid var(--border-color); }
        h2 { color: #fff; font-size: 1.8rem; margin-bottom: 30px; display: flex; align-items: center; gap: 10px; }
        h2 i { color: var(--accent-color); font-size: 1.4rem; }

        /* Timeline Interativa */
        .timeline { position: relative; border-left: 3px solid var(--border-color); margin-left: 20px; padding-left: 30px; }
        .timeline-item { position: relative; margin-bottom: 40px; }
        .timeline-item::before {
            content: ''; position: absolute; left: -39px; top: 5px;
            width: 15px; height: 15px; border-radius: 50%;
            background: var(--accent-color); border: 3px solid var(--bg-color);
            transition: transform 0.3s ease;
        }
        .timeline-item:hover::before { transform: scale(1.5); background: var(--highlight); }
        .timeline-date { font-size: 0.9rem; color: var(--accent-color); font-weight: bold; }
        .timeline-title { font-size: 1.2rem; color: #fff; font-weight: bold; margin: 5px 0; }
        .timeline-desc { font-size: 0.95rem; }

        /* Badges de Conquistas */
        .achievements-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 15px; }
        .achievement-card {
            background: rgba(88, 166, 255, 0.1);
            border: 1px solid var(--accent-color);
            padding: 15px; border-radius: 8px;
            display: flex; align-items: center; gap: 15px;
            transition: transform 0.2s;
        }
        .achievement-card:hover { transform: translateY(-5px); background: rgba(88, 166, 255, 0.15); }
        .achievement-icon { font-size: 1.5rem; color: var(--accent-color); }
        .achievement-text div:first-child { font-weight: bold; color: #fff; }
        .achievement-text div:last-child { font-size: 0.85rem; color: #8b949e; }

        /* Skills */
        .skills { display: flex; gap: 10px; flex-wrap: wrap; }
        .skill-tag { 
            background: var(--card-bg); border: 1px solid var(--border-color); 
            padding: 8px 16px; border-radius: 20px; font-size: 0.9rem;
            display: flex; align-items: center; gap: 8px;
            transition: border-color 0.3s;
        }
        .skill-tag:hover { border-color: var(--accent-color); color: #fff; }

        /* Botões */
        .btn {
            display: inline-block; padding: 10px 20px;
            background-color: var(--accent-color); color: #000;
            text-decoration: none; border-radius: 6px; font-weight: bold;
            transition: opacity 0.2s;
        }
        .btn:hover { opacity: 0.9; }
        .btn-outline { background: transparent; border: 1px solid var(--border-color); color: var(--text-color); margin-left: 10px; }
        .btn-outline:hover { border-color: #fff; color: #fff; }

    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Samuel Soares</h1>
            <div class="subtitle">Backend Developer | Java • Spring Ecosystem</div>
            <p class="tagline">
                Estudante de Sistemas de Informação na Unifacisa. Transformando lógica de competições de robótica em arquiteturas de software escaláveis.
            </p>
            <div style="margin-top: 20px;">
                <a href="#projects" class="btn">Ver Projetos</a>
                <a href="#contact" class="btn btn-outline">Contato</a>
            </div>
        </header>

        <section>
            <h2><i class="fas fa-code"></i> Stack Tecnológico</h2>
            <div class="skills">
                <span class="skill-tag"><i class="fab fa-java"></i> Java 17/21</span>
                <span class="skill-tag"><i class="fas fa-leaf"></i> Spring Boot</span>
                <span class="skill-tag"><i class="fas fa-database"></i> Spring Data JPA</span>
                <span class="skill-tag"><i class="fas fa-server"></i> REST APIs</span>
                <span class="skill-tag"><i class="fas fa-database"></i> PostgreSQL</span>
                <span class="skill-tag"><i class="fab fa-docker"></i> Docker</span>
                <span class="skill-tag"><i class="fab fa-git-alt"></i> Git Flow</span>
            </div>
        </section>

        <section>
            <h2><i class="fas fa-history"></i> Minha Jornada</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-date">Atualmente (5º Período)</div>
                    <div class="timeline-title">B.Sc. Sistemas de Informação - Unifacisa</div>
                    <div class="timeline-desc">
                        Foco total em Engenharia de Software e Desenvolvimento Backend. Aprofundando conhecimentos em estruturas de dados, bancos de dados e arquitetura de sistemas.
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-date">Ensino Médio</div>
                    <div class="timeline-title">Equipe de Robótica SESI-Prata</div>
                    <div class="timeline-desc">
                        Início da carreira como <strong>Programador Líder</strong>. Responsável pela lógica dos robôs em competições de alto nível. Aqui aprendi que código eficiente ganha campeonatos.
                    </div>
                </div>
            </div>
        </section>

        <section>
            <h2><i class="fas fa-trophy"></i> Conquistas & Prêmios</h2>
            <div class="achievements-grid">
                <div class="achievement-card">
                    <div class="achievement-icon"><i class="fas fa-robot"></i></div>
                    <div class="achievement-text">
                        <div>2º Lugar Programação OBR</div>
                        <div>Olimpíada Brasileira de Robótica (Nacional)</div>
                    </div>
                </div>
                <div class="achievement-card">
                    <div class="achievement-icon"><i class="fas fa-medal"></i></div>
                    <div class="achievement-text">
                        <div>Campeão FLL & FTC</div>
                        <div>Competições de Robótica (Programador)</div>
                    </div>
                </div>
                <div class="achievement-card">
                    <div class="achievement-icon"><i class="fas fa-calculator"></i></div>
                    <div class="achievement-text">
                        <div>Destaque OBMEP</div>
                        <div>Olimpíada Bras. de Matemática</div>
                    </div>
                </div>
                <div class="achievement-card">
                    <div class="achievement-icon"><i class="fas fa-square-root-alt"></i></div>
                    <div class="achievement-text">
                        <div>Canguru de Matemática</div>
                        <div>Competição Internacional</div>
                    </div>
                </div>
            </div>
        </section>

        <section id="projects">
            <h2><i class="fas fa-laptop-code"></i> Projetos em Destaque</h2>
            <div style="background: var(--card-bg); padding: 20px; border-radius: 8px; border: 1px solid var(--border-color);">
                <h3 style="color: #fff; margin-top: 0;">API de Gestão (Exemplo)</h3>
                <p>Aqui você descreverá seu projeto backend Java mais forte.</p>
                <a href="#" style="color: var(--accent-color); text-decoration: none;">Ver no GitHub -></a>
            </div>
        </section>

        <section id="contact">
            <h2><i class="fas fa-envelope"></i> Contato</h2>
            <p>Vamos construir algo juntos?</p>
            <div style="margin-top: 20px;">
                <a href="https://linkedin.com/in/seu-linkedin" class="btn"><i class="fab fa-linkedin"></i> LinkedIn</a>
                <a href="https://github.com/seu-github" class="btn btn-outline"><i class="fab fa-github"></i> GitHub</a>
                <a href="mailto:seu-email@gmail.com" class="btn btn-outline"><i class="fas fa-envelope"></i> Email</a>
            </div>
        </section>

        <footer style="text-align: center; padding: 40px 0; color: #666; font-size: 0.8rem;">
            &copy; 2025 Samuel Soares. Feito com HTML, CSS e Café.
        </footer>
    </div>

</body>
</html>
