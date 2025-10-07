<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cupcakes Tropicais - Cardápio de Cupcakes Brasileiros</title>
    <style>
        /* CSS Geral */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #ff69b4; /* Rosa tropical */
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 10px 0 0 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ffd700; /* Dourado no hover */
        }
        main {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        section {
            margin-bottom: 40px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        h2 {
            color: #ff69b4;
            border-bottom: 2px solid #ff69b4;
            padding-bottom: 10px;
        }
        .flavor-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .flavor-item {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            text-align: center;
            transition: transform 0.3s;
        }
        .flavor-item:hover {
            transform: scale(1.05);
        }
        .flavor-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        .price {
            font-size: 1.2em;
            font-weight: bold;
            color: #28a745; /* Verde para preços */
        }
        footer {
            background-color: #28a745; /* Verde tropical */
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        footer a {
            color: #ffd700;
            text-decoration: none;
        }
        /* Responsivo */
        @media (max-width: 768px) {
            header h1 { font-size: 2em; }
            nav ul li { display: block; margin: 10px 0; }
            .flavor-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Doce Brasil: A Viagem Começa em um Cupcake</h1>
        <p>Cupcakes com Sabor do Brasil</p>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#cardapio">Cardápio</a></li>
                <li><a href="#menu">Menu</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>🇧🇷🧁 Sabores que Dançam no Paladar</h2>
            <p>Uma seleção de cupcakes que celebram o Brasil com emoção, memória e sabor.</p>
            <img src="https://cdn.discordapp.com/attachments/1250637193924575296/1424910980068020335/2191849e-113f-492c-b016-b65fd0448dd5.jpg?ex=68e5ab43&is=68e459c3&hm=dfa5d19be28d35e82c5ebd515c27bceab760b3b45c9565b850419fba3f0e3afc&" alt="" style="width: 30%; border-radius:5 px;">
        </section>

        <section id="cardapio">
            <h2>Nosso Cardápio</h2>
            <div class="flavor-grid">
                <div class="flavor-item">
                    <h3>🥥 Carioca Tropical</h3>
                    <p><strong>Sabor:</strong> Coco<br>
                    <strong>Inspiração:</strong> O Rio de Janeiro e seu clima praiano, leve e doce.<br>
                    <strong>Descrição:</strong> Um mergulho direto nas areias de Copacabana! Com sabor suave de coco, esse cupcake representa o calor, o charme e a leveza da Cidade Maravilhosa.</p>
                </div>
                <div class="flavor-item">
                    <h3>🍋 Explosão de Carnaval</h3>
                    <p><strong>Sabor:</strong> Limão<br>
                    <strong>Inspiração:</strong> A refrescância e energia vibrante do Carnaval brasileiro.<br>
                    <strong>Descrição:</strong> Cítrico, alegre e cheio de personalidade! Esse cupcake traz o frescor da folia e a vibração das ruas em festa, com um toque azedinho que anima qualquer paladar.</p>
                </div>
                <div class="flavor-item">
                    <h3>📺🍫 Doce de Tela</h3>
                    <p><strong>Sabores:</strong> Chocolate com cobertura de chocolate e cenoura com ganache de chocolate<br>
                    <strong>Inspiração:</strong> A infância brasileira ao som das aberturas do SBT e cheirinho de bolo saindo do forno.<br>
                    <strong>Descrição:</strong> Direto das tardes nostálgicas de sofá, desenhos animados e comerciais inesquecíveis. Essa dupla saborosa mistura o aconchego da cenoura com a intensidade do chocolate — um verdadeiro programa de sucesso!</p>
                </div>
                <div class="flavor-item">
                    <h3>⚽❤️ O 10 do Chef</h3>
                    <p><strong>Sabor:</strong> Massa vermelha com recheio de leite Ninho e cobertura de Nutella<br>
                    <strong>Inspiração:</strong> A paixão nacional pelo futebol e a emoção de torcer.<br>
                    <strong>Descrição:</strong> O craque da nossa seleção de sabores! Com massa vibrante, recheio cremoso e cobertura de Nutella, esse cupcake é um golaço que conquista qualquer torcida. Sabor campeão!</p>
                </div>
            </div>
            </div>
        </section>

    <section id="menu">
            <h2>Menu</h2>
            <div class="flavor-grid">
                <div class="flavor-item">
                    <h3>🥥 Carioca Tropical</h3>
                    <p><strong>Flavor:</strong> Coconut<br>
                    <strong>Inspiration:</strong> Rio de Janeiro and its light, beachy, sweet vibe.<br>
                    <strong>Description:</strong> A direct dive into the sands of Copacabana! With a smooth coconut flavor, this cupcake represents the warmth, charm, and lightness of the Marvelous City.</p>
                </div>
                <div class="flavor-item">
                    <h3>🍋 Carnival Explosion</h3>
                    <p><strong>Flavor:</strong> Lemon<br>
                    <strong>Inspiration:</strong> The refreshing and vibrant energy of Brazilian Carnival.<br>
                    <strong>Description:</strong> Citrusy, cheerful, and full of personality! This cupcake brings the freshness of the festivities and the lively vibe of the streets, with a tangy touch to excite any palate.</p>
                </div>
                <div class="flavor-item">
                    <h3>📺🍫 Sweet on Screen</h3>
                    <p><strong>Flavors:</strong> Chocolate cupcake with chocolate frosting & carrot cupcake with chocolate ganache<br>
                    <strong>Inspiration:</strong> Brazilian childhood to the sound of SBT TV show openings and the smell of cake from the oven.<br>
                    <strong>Description:</strong> Straight from nostalgic afternoons on the couch, cartoons, and unforgettable commercials. This tasty duo mixes the coziness of carrot with the intensity of chocolate—a true hit show!</p>
                </div>
                <div class="flavor-item">
                    <h3>⚽❤️ The Chef's Number 10</h3>
                    <p><strong>Flavor:</strong> Red velvet cake with Ninho milk filling and Nutella topping<br>
                    <strong>Inspiration:</strong> The national passion for football and the thrill of cheering.<br>
                    <strong>Description:</strong> The star player of our flavor selection! With vibrant cake, creamy filling, and Nutella topping, this cupcake is a goal that wins over any crowd. Champion flavor!</p>
                </div>
            </div>
        </section>
    </main>

    <footer id="contato">
        <h2>Entre em Contato</h2>
        <p>Email: <a href="mailto:cupcakes.tropicais@email.com">cupcakes.tropicais@email.com</a> | Instagram: <a href="https://instagram.com/cupcakestropicais" target="_blank">@cupcakestropicais</a></p>
        <p>Site: <a href="https://www.cupcakestropicais.com.br" target="_blank">www.cupcakestropicais.com.br</a> (fictício – personalize!)</p>
        <p>&copy; 2023 Cupcakes Tropicais. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
