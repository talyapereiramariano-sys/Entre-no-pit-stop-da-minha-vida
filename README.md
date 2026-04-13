<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pit Stop da Talya</title>
    <style>
        :root {
            --vermelho: #CE1212; --amarelo: #FFD700; --preto: #000;
        }
        body {
            background-color: var(--preto); color: #fff;
            font-family: 'Courier New', Courier, monospace;
            margin: 0; padding: 15px; display: flex; justify-content: center;
        }
        .container {
            max-width: 450px; width: 100%; border: 4px solid var(--amarelo);
            background: #111; box-shadow: 8px 8px 0px var(--vermelho);
        }
        nav { background: var(--amarelo); padding: 10px; text-align: center; border-bottom: 4px solid #000; }
        nav a { color: #000; text-decoration: none; font-weight: bold; margin: 0 10px; font-size: 12px; }
        .p-20 { padding: 20px; }
        h1 { color: var(--amarelo); font-size: 18px; border-bottom: 2px dashed var(--vermelho); padding-bottom: 5px; }
        
        /* Galeria Pixelada */
        .scroller { display: flex; gap: 10px; overflow-x: auto; padding: 10px 0; }
        .scroller img { width: 140px; border: 3px solid var(--vermelho); border-radius: 5px; }

        .bio { background: rgba(255,255,255,0.05); padding: 15px; border-left: 5px solid var(--vermelho); font-size: 14px; line-height: 1.6; margin: 15px 0; }
        .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
        .card { background: #222; border: 2px solid #333; padding: 10px; text-align: center; font-size: 11px; }
        
        .bar-bg { width: 100%; height: 12px; background: #333; border: 1px solid var(--amarelo); margin: 10px 0; }
        .bar-fill { width: 100%; height: 100%; background: var(--vermelho); }
        
        .footer { background: var(--amarelo); color: #000; padding: 15px; font-weight: bold; text-align: center; font-size: 12px; }
    </style>
</head>
<body>
    <div class="container">
        <nav>
            <a href="https://instagram.com/liawxaf">INSTAGRAM</a>
            <a href="#">SPOTIFY</a>
            <a href="#">PINTEREST</a>
        </nav>
        <div class="p-20">
            <h1>Entre no pit stop da minha vida</h1>
            <p>Talya | @liawxaf</p>
            <div class="scroller">
                <img src="foto1.jpg" alt="Charles 1">
                <img src="foto2.jpg" alt="Charles 2">
                <img src="foto3.jpg" alt="Charles 3">
            </div>
            <div class="bio">
                entre notas de música e todos os tipos de doramas, encontro beleza nas pequenas coisas. 
                sou fã de Fórmula 1, especialmente de Charles Leclerc, piloto da Ferrari. 
                café, maquiagem, animais e mistérios de casos criminais completam meu mundo.
            </div>
            <div class="grid">
                <div class="card">🏎️ Ferrari F1</div>
                <div class="card">🦅 Corinthians</div>
                <div class="card">☕ Café & Choco</div>
                <div class="card">🎵 Porsche Love</div>
            </div>
            <div style="margin-top:20px;">
                Idioma: Português (Brasil)
                <div class="bar-bg"><div class="bar-fill"></div></div>
            </div>
            <p style="font-size: 13px;"><strong>Mood:</strong> esperando o próximo GP 🏁 e dia de jogo do timão! 🦅</p>
        </div>
        <div class="footer">
            "Papo reto: se gosta de F1, futebol ou só de um bom café, chega mais no direct! :)"
        </div>
    </div>
</body>
</html>
