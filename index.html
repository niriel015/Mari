<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Mariani - 4 Meses</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #ff4d6d;
            --pink-hub: #ffb6c1;
            --white: #ffffff;
            --bg-gradient: radial-gradient(circle at center, #1b2735 0%, #050505 100%);
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            background: var(--bg-gradient);
            color: var(--white);
            font-family: 'Poppins', sans-serif;
            overflow: hidden;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        #starField { position: fixed; top: 0; left: 0; width: 100%; height: 100%; z-index: 1; pointer-events: none; }

        /* --- SEU SVG DE BATIMENTO --- */
        .heart-svg { overflow: visible; filter: drop-shadow(0 0 10px var(--primary)); }
        .home-svg { width: 300px; margin: 20px 0; }
        .footer-svg { width: 140px; margin-top: 30px; opacity: 0.8; }

        .svg-line {
            fill: none; stroke: var(--primary); stroke-width: 2;
            stroke-linecap: round; stroke-linejoin: round;
            stroke-dasharray: 1; stroke-dashoffset: 1;
            animation: dash-anim 4s linear infinite;
        }

        .svg-heart {
            fill: var(--primary); transform-origin: center;
            animation: blink-anim 4s linear infinite;
        }

        @keyframes dash-anim { 0% { stroke-dashoffset: 1; } 80%, 100% { stroke-dashoffset: 0; } }
        @keyframes blink-anim {
            0%, 60% { opacity: 0; transform: scale(0); }
            70% { opacity: 1; transform: scale(1.2); }
            75% { opacity: 1; transform: scale(1.0); }
            80% { opacity: 1; transform: scale(1.2); }
            85%, 100% { opacity: 0; transform: scale(1.0); }
        }

        /* --- SISTEMA DE PÁGINAS --- */
        .page { 
            position: absolute; width: 100%; max-width: 600px; padding: 20px; 
            text-align: center; transition: 0.6s ease-in-out; 
            display: flex; flex-direction: column; align-items: center;
            z-index: 5; opacity: 0; pointer-events: none;
        }

        .page.active { opacity: 1; pointer-events: all; z-index: 10; }

        h1 { font-family: 'Dancing Script', cursive; font-size: clamp(2.5rem, 8vw, 3.5rem); margin-bottom: 0.5rem; text-shadow: 0 0 15px var(--primary); }

        /* --- GRID DE FOTOS TORTINHAS --- */
        .photo-grid { 
            display: grid; grid-template-columns: repeat(2, 1fr); 
            gap: 30px; width: 450px; max-width: 100%; margin: 30px 0; 
        }

        .photo-item { 
            width: 100%; aspect-ratio: 1/1; object-fit: cover; 
            border: 6px solid var(--white); border-radius: 4px; 
            box-shadow: 0 8px 20px rgba(0,0,0,0.5); 
            transition: 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275); 
            cursor: pointer;
        }

        /* Cada foto pendendo para um lado */
        .photo-item:nth-child(1) { transform: rotate(-6deg); }
        .photo-item:nth-child(2) { transform: rotate(5deg); }
        .photo-item:nth-child(3) { transform: rotate(-4deg); }
        .photo-item:nth-child(4) { transform: rotate(7deg); }

        /* Efeito ao passar o mouse ou clicar */
        .photo-item:hover { transform: rotate(0deg) scale(1.1); z-index: 50; border-color: var(--pink-hub); }
        .photo-item.zoom { transform: scale(1.4) rotate(0deg) !important; z-index: 999; border-color: var(--pink-hub); }

        /* --- CARTA --- */
        .envelope-wrapper { position: relative; width: 280px; height: 160px; margin-top: 20px; cursor: pointer; }
        .envelope { position: absolute; bottom: 0; width: 100%; height: 100%; background: #d1d1d1; border-radius: 0 0 10px 10px; z-index: 10; transition: 0.5s; }
        .flap { position: absolute; top: 0; width: 0; height: 0; border-left: 140px solid transparent; border-right: 140px solid transparent; border-top: 100px solid #e5e5e5; transform-origin: top; transition: 0.5s; z-index: 15; }
        .letter { 
            position: absolute; bottom: 5px; left: 10px; width: 260px; height: 150px; 
            background: #fff; border-radius: 8px; padding: 25px; color: #333; 
            text-align: left; transition: 0.8s; z-index: 5; opacity: 0; overflow-y: auto;
        }
        
        .is-open .envelope { transform: translateY(60px); opacity: 0.1; }
        .is-open .flap { transform: rotateX(180deg); }
        .is-open .letter { opacity: 1; transform: translateY(-320px) scale(1.2); width: 320px; height: 420px; left: -20px; z-index: 100; box-shadow: 0 20px 50px rgba(0,0,0,0.8); }

        /* BOTÕES */
        .btn { 
            background: rgba(255, 255, 255, 0.1); border: 1px solid rgba(255, 255, 255, 0.4); 
            padding: 12px 35px; border-radius: 30px; color: white; font-weight: 600; 
            cursor: pointer; backdrop-filter: blur(10px); transition: 0.3s; margin-top: 10px;
            position: relative; z-index: 20;
        }
        .btn:hover { background: var(--white); color: #000; }

        .shooting-star { position: absolute; background: #fff; border-radius: 50%; pointer-events: none; }
    </style>
</head>
<body>

    <div id="starField"></div>

    <section class="page active" id="p1">
        <h1>Para Mariani</h1>
        <svg class="heart-svg home-svg" viewBox="0 0 502.98 108.61">
            <path class="svg-heart" d="M213.35 29.43c19.41-15.19 33.68 10.86 37.73 18.82-.28-13.61 11.64-40.98 25.94-34.01 32.3 15.74-15.88 83.8-26.4 81.76-13.24-9-51.35-53.3-37.27-66.57Z" />
            <path pathLength="1" class="svg-line" d="M5.32 78.13c.96-.01 5-8.5 5.54-8.54.58-.05 6.1 8.51 7.1 8.51 3.66 0 9.29.06 10.71.05 2.53-.01 4.82-72.88 4.82-72.88l4.76 97.28 3.97-24.45 20.45-.22C64 77.86 77.1 63.66 78.36 63.8c1.31.15 6.68 14.08 7.94 14.07 2.3-.03 33.32.04 35.76.02.96 0 5-8.5 5.53-8.53.59-.05 6.1 8.51 7.1 8.5 3.66 0 9.3.07 10.72.06 2.53-.02 4.81-72.89 4.81-72.89l4.77 97.28 3.97-24.44s83.34-3.33 74.69 7.67c-8.65 11-45.3-42.94-31.65-53.58 25.6-19.96 49.96 36.94 40.26 36.5-12.2-.53 1.8-62.32 23.41-51.7 32.24 15.86-17.56 84.92-26.4 81.77-5.73-2.05-.68-21.68 31.4-26.58 26.65-6.42 29.5 2.35 52.62 7.11 2.53-.02 4.82-72.89 4.82-72.89l4.76 97.28 3.97-24.44 20.45-.22c1.31-.02 14.41-14.22 15.68-14.07 1.32.15 6.7 14.08 7.95 14.07 2.29-.03 33.32.04 35.76.02.95 0 5-8.5 5.53-8.54.58-.04 6.1 8.52 7.1 8.52 3.66 0 9.3.06 10.72.05 2.53-.02 4.81-72.89 4.81-72.89l4.77 97.28 3.97-24.44 20.45-.23c1.31-.01 14.4-14.22 15.68-14.07 1.32.16 6.69 14.09 7.94 14.07" />
        </svg>
        <p>4 meses iluminando o meu <span style="color: var(--pink-hub); font-weight: bold;">Niri Hub</span>.</p>
        <button class="btn" onclick="goTo(2)">Nossa Galeria</button>
    </section>

    <section class="page" id="p2">
        <h1 style="color: var(--pink-hub);">Nossos Momentos</h1>
        <div class="photo-grid">
            <img src="foto1.jpg" class="photo-item" onclick="toggleZoom(this)">
            <img src="foto2.jpg" class="photo-item" onclick="toggleZoom(this)">
            <img src="foto3.jpg" class="photo-item" onclick="toggleZoom(this)">
            <img src="foto4.jpg" class="photo-item" onclick="toggleZoom(this)">
        </div>
        <button class="btn" onclick="goTo(3)">Ler Minha Carta</button>
        <svg class="heart-svg footer-svg" viewBox="0 0 502.98 108.61">
            <path class="svg-heart" d="M213.35 29.43c19.41-15.19 33.68 10.86 37.73 18.82-.28-13.61 11.64-40.98 25.94-34.01 32.3 15.74-15.88 83.8-26.4 81.76-13.24-9-51.35-53.3-37.27-66.57Z" />
            <path pathLength="1" class="svg-line" d="M5.32 78.13c.96-.01 5-8.5 5.54-8.54.58-.05 6.1 8.51 7.1 8.51 3.66 0 9.29.06 10.71.05 2.53-.01 4.82-72.88 4.82-72.88l4.76 97.28 3.97-24.45 20.45-.22C64 77.86 77.1 63.66 78.36 63.8c1.31.15 6.68 14.08 7.94 14.07 2.3-.03 33.32.04 35.76.02.96 0 5-8.5 5.53-8.53.59-.05 6.1 8.51 7.1 8.5 3.66 0 9.3.07 10.72.06 2.53-.02 4.81-72.89 4.81-72.89l4.77 97.28 3.97-24.44s83.34-3.33 74.69 7.67c-8.65 11-45.3-42.94-31.65-53.58 25.6-19.96 49.96 36.94 40.26 36.5-12.2-.53 1.8-62.32 23.41-51.7 32.24 15.86-17.56 84.92-26.4 81.77-5.73-2.05-.68-21.68 31.4-26.58 26.65-6.42 29.5 2.35 52.62 7.11 2.53-.02 4.82-72.89 4.82-72.89l4.76 97.28 3.97-24.44 20.45-.22c1.31-.02 14.41-14.22 15.68-14.07 1.32.15 6.7 14.08 7.95 14.07 2.29-.03 33.32.04 35.76.02.95 0 5-8.5 5.53-8.54.58-.04 6.1 8.52 7.1 8.52 3.66 0 9.3.06 10.72.05 2.53-.02 4.81-72.89 4.81-72.89l4.77 97.28 3.97-24.44 20.45-.23c1.31-.01 14.4-14.22 15.68-14.07 1.32.16 6.69 14.09 7.94 14.07" />
        </svg>
    </section>

    <section class="page" id="p3">
        <div class="envelope-wrapper" onclick="this.classList.toggle('is-open')">
            <div class="flap"></div>
            <div class="envelope"></div>
            <div class="letter">
                <h2 style="font-family:'Dancing Script'; color:var(--primary); margin-bottom:10px;">Minha Mariani,</h2>
                <p style="font-size:0.95rem; line-height:1.6;">
                    Completar 4 meses ao seu lado é perceber que o tempo voa quando a gente está feliz. <br><br>
                    Obrigado por ser essa pessoa incrível que transforma meus dias comuns em algo especial. <br><br>
                    <b>Te amo infinitamente!</b>
                </p>
            </div>
        </div>
        <svg class="heart-svg footer-svg" viewBox="0 0 502.98 108.61">
            <path class="svg-heart" d="M213.35 29.43c19.41-15.19 33.68 10.86 37.73 18.82-.28-13.61 11.64-40.98 25.94-34.01 32.3 15.74-15.88 83.8-26.4 81.76-13.24-9-51.35-53.3-37.27-66.57Z" />
            <path pathLength="1" class="svg-line" d="M5.32 78.13c.96-.01 5-8.5 5.54-8.54.58-.05 6.1 8.51 7.1 8.51 3.66 0 9.29.06 10.71.05 2.53-.01 4.82-72.88 4.82-72.88l4.76 97.28 3.97-24.45 20.45-.22C64 77.86 77.1 63.66 78.36 63.8c1.31.15 6.68 14.08 7.94 14.07 2.3-.03 33.32.04 35.76.02.96 0 5-8.5 5.53-8.53.59-.05 6.1 8.51 7.1 8.5 3.66 0 9.3.07 10.72.06 2.53-.02 4.81-72.89 4.81-72.89l4.77 97.28 3.97-24.44s83.34-3.33 74.69 7.67c-8.65 11-45.3-42.94-31.65-53.58 25.6-19.96 49.96 36.94 40.26 36.5-12.2-.53 1.8-62.32 23.41-51.7 32.24 15.86-17.56 84.92-26.4 81.77-5.73-2.05-.68-21.68 31.4-26.58 26.65-6.42 29.5 2.35 52.62 7.11 2.53-.02 4.82-72.89 4.82-72.89l4.76 97.28 3.97-24.44 20.45-.22c1.31-.02 14.41-14.22 15.68-14.07 1.32.15 6.7 14.08 7.95 14.07 2.29-.03 33.32.04 35.76.02.95 0 5-8.5 5.53-8.54.58-.04 6.1 8.52 7.1 8.52 3.66 0 9.3.06 10.72.05 2.53-.02 4.81-72.89 4.81-72.89l4.77 97.28 3.97-24.44 20.45-.23c1.31-.01 14.4-14.22 15.68-14.07 1.32.16 6.69 14.09 7.94 14.07" />
        </svg>
    </section>

    <script>
        // Navegação
        function goTo(num) {
            document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
            setTimeout(() => {
                document.getElementById(`p${num}`).classList.add('active');
            }, 100);
        }

        // Estrelas de fundo
        const starField = document.getElementById('starField');
        function initStars() {
            for (let i = 0; i < 100; i++) {
                const star = document.createElement('div');
                star.style.cssText = `position:absolute; background:#fff; border-radius:50%; width:${Math.random()*2}px; height:${Math.random()*2}px; left:${Math.random()*100}%; top:${Math.random()*100}%; opacity:${Math.random()};`;
                starField.appendChild(star);
            }
        }

        function spawnShootingStar() {
            const star = document.createElement('div');
            star.className = 'shooting-star';
            star.style.width = '2px'; star.style.height = '2px';
            let x = Math.random() * 80; let y = -5;
            starField.appendChild(star);
            const interval = setInterval(() => {
                x += 0.5; y += 0.8;
                star.style.left = x + '%'; star.style.top = y + '%';
                if (y > 110) { clearInterval(interval); star.remove(); }
            }, 30);
        }

        // Zoom das fotos polaroid
        function toggleZoom(el) {
            const isZoomed = el.classList.contains('zoom');
            document.querySelectorAll('.photo-item').forEach(img => img.classList.remove('zoom'));
            if (!isZoomed) el.classList.add('zoom');
        }

        initStars();
        setInterval(spawnShootingStar, 4000);
    </script>
</body>
</html>
