<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>6 Lados</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4b0082;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #3a0069;
        }
        nav a {
            color: #fff;
            padding: 1rem;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #260041;
        }
        section {
            padding: 2rem;
            margin: 2rem auto;
            max-width: 800px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #4b0082;
            color: #fff;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 0.5rem;
            margin-bottom: 1rem;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .contact-form button {
            padding: 0.7rem 1.5rem;
            background-color: #4b0082;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #3a0069;
        }
    </style>
</head>
<body>
    <header>
        <h1>6 Lados</h1>
        <p>Enriquecendo sua experiência de RPG de mesa</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#sobre-mim">Sobre Mim</a>
        <a href="#dicas">Dicas</a>
        <a href="#materiais">Materiais</a>
        <a href="#contato">Contato</a>
    </nav>
    <section id="home">
        <h2>Bem-vindo ao 6 Lados</h2>
        <p>Nosso objetivo é proporcionar dicas e materiais para enriquecer sua experiência de RPG de mesa. Explore nosso site para encontrar recursos úteis para mestres e jogadores.</p>
    </section>
    <section id="sobre-mim">
        <h2>Sobre Mim</h2>
        <p>Olá! Eu sou um entusiasta de RPG de mesa com mais de 10 anos de experiência como mestre e jogador. Minha paixão é ajudar outros a criar e viver aventuras inesquecíveis. Aqui você encontrará minhas melhores dicas e materiais para aprimorar suas sessões de RPG.</p>
    </section>
    <section id="dicas">
        <h2>Dicas</h2>
        <article>
            <h3>Criação de Personagens</h3>
            <p>Personagens bem desenvolvidos são essenciais para uma boa campanha. Pense na história de fundo, motivações e objetivos de seus personagens para torná-los mais interessantes.</p>
        </article>
        <article>
            <h3>Construção de Mundos</h3>
            <p>Um mundo rico e detalhado pode transformar sua campanha. Dedique tempo para criar locais, culturas e histórias únicas que seus jogadores possam explorar.</p>
        </article>
        <article>
            <h3>Condução de Sessões</h3>
            <p>Seja flexível e esteja preparado para improvisar. As ações dos jogadores podem desviar da trama planejada, então esteja pronto para ajustar e manter a história fluindo.</p>
        </article>
    </section>
    <section id="materiais">
        <h2>Materiais</h2>
        <ul>
            <li><a href="#">Ficha de Personagem</a></li>
            <li><a href="#">Mapas de Terreno</a></li>
            <li><a href="#">Tabelas de Encontros</a></li>
        </ul>
    </section>
    <section id="contato">
        <h2>Contato</h2>
        <form class="contact-form">
            <input type="text" name="name" placeholder="Seu nome">
            <input type="email" name="email" placeholder="Seu email">
            <textarea name="message" rows="5" placeholder="Sua mensagem"></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 6 Lados. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
