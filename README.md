<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AuAuMimos - Loja para Pets</title>
    <style>
        body { 
            font-family: Arial, sans-serif; 
            text-align: center; 
            margin: 0; 
            padding: 0; 
            background: url('https://via.placeholder.com/1920x1080/ffe5d9/ffffff?text=Poodle+Marrom') no-repeat center center fixed; 
            background-size: cover; 
            color: #5d4037; 
        }
        header { background: #ffb6b9; color: white; padding: 20px; font-size: 28px; font-weight: bold; }
        .container { display: flex; flex-wrap: wrap; justify-content: center; padding: 20px; }
        .produto { background: #ffdde1; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); padding: 20px; margin: 15px; width: 280px; transition: transform 0.3s; }
        .produto:hover { transform: scale(1.05); }
        .produto img { width: 100%; height: auto; border-radius: 10px; }
        .btn-comprar { background: #ff8fab; color: white; padding: 12px; border: none; cursor: pointer; width: 100%; border-radius: 5px; font-size: 16px; transition: background 0.3s ease; }
        .btn-comprar:hover { background: #e57373; }
        footer { background: #ffb6b9; color: white; text-align: center; padding: 20px; margin-top: 20px; font-size: 14px; }
        nav { background: #ff8fab; padding: 15px; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-size: 18px; }
        nav a:hover { text-decoration: underline; }
        .contato { background: #ffdde1; padding: 30px; margin: 20px auto; width: 50%; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); }
        .contato input, .contato textarea { width: 90%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px; }
        .contato button { background: #ff8fab; color: white; padding: 12px; border: none; cursor: pointer; border-radius: 5px; font-size: 16px; transition: background 0.3s ease; }
        .contato button:hover { background: #e57373; }
    </style>
</head>
<body>
    <header>AuAuMimos - Loja para Pets</header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Produtos</a>
        <a href="#">Sobre</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="container">
        <div class="produto">
            <img src="https://via.placeholder.com/250" alt="Produto 1">
            <h3>Brinquedo para Cachorro</h3>
            <p>R$ 99,90</p>
            <button class="btn-comprar">Comprar</button>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/250" alt="Produto 2">
            <h3>Cama Confortável</h3>
            <p>R$ 79,90</p>
            <button class="btn-comprar">Comprar</button>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/250" alt="Produto 3">
            <h3>Ração Premium</h3>
            <p>R$ 59,90</p>
            <button class="btn-comprar">Comprar</button>
        </div>
    </div>
    <div id="contato" class="contato">
        <h2>Fale Conosco</h2>
        <form>
            <input type="text" name="nome" placeholder="Seu Nome" required>
            <input type="email" name="email" placeholder="Seu Email" required>
            <textarea name="mensagem" rows="5" placeholder="Sua Mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </div>
    <footer>
        <p>&copy; 2024 AuAuMimos | Contato: contato@auaumimos.com | Redes Sociais: @auaumimos</p>
    </footer>
</body>
</html>
