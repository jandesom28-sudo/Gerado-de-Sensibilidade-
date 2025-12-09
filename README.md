# Gerado-de-Sensibilidade-
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gerador de Sensibilidade - Janderson</title>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>
    <div class="container">
        <h1>Gerador de Sensibilidade ✨</h1>
        
        <div class="generator-box">
            <p>Selecione seu Dispositivo:</p>
            <select id="device-select">
                <option value="default">Selecione...</option>
                <option value="android">Android</option>
                <option value="ios">iOS</option>
            </select>
            
            <p>Selecione o Jogo:</p>
            <input type="text" id="game-name" placeholder="Ex: Free Fire, COD Mobile">
            
            <button id="generate-button">Gerar Sensibilidade</button>
            
            <div id="result-area" class="result-area">
                Aguardando a geração...
            </div>
        </div>

        <hr>

        <div class="premium-box">
            <h2>🔑 Acesso Premium</h2>
            <p>Insira sua Chave de Acesso Premium para configurações exclusivas:</p>
            <input type="text" id="premium-key" placeholder="Chave de Acesso Premium...">
            <button id="activate-premium">Ativar Premium</button>
        </div>

        <hr>
        
        <div id="ultra-premium-section" class="ultra-premium-box hidden">
            <h2 style="color: #FFD700;">👑 Configurações Ultra-Poderosas</h2>
            <p>Sua chave foi validada. Use essas configurações para um desempenho insano!</p>
            
            <div id="ultra-result-area" class="result-area" style="background-color: #4B0082; color: #FFF; border: 2px solid gold;">
                Clique para gerar a sensibilidade Premium!
            </div>
            
            <button id="generate-ultra-button" style="background-color: #FFD700; color: #4B0082;">Gerar Sensibilidade Premium</button>
        </div>
        
        <footer>
            Criado por 
            <a href="index.html">Janderson</a>
        </footer>
        
    </div>

    <script src="game.js"></script>

