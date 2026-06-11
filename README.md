# projeto-agrinhoo
projeto agrinho 26
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Projeto Agrinho 2026 🌾✨</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="logo">Agrinho 2026 ✨</div>
        <nav>
            <a href="#sobre">Sobre</a>
            <a href="#projeto">O Projeto</a>
            <a href="#galeria">Galeria</a>
        </nav>
    </header>

    <section class="hero">
        <h1>Inovação no Campo com Muito Estilo! 👩‍🌾💖</h1>
        <p>Bem-vindos ao meu projeto do Agrinho 2026. Unindo tecnologia, sustentabilidade e criatividade.</p>
        <a href="#projeto" class="btn">Conhecer Projeto</a>
    </section>

    <section id="sobre" class="content-section">
        <h2>Sobre o Projeto</h2>
        <p>Este espaço foi criado para compartilhar a evolução da nossa ideia para o Agrinho deste ano. Queremos mostrar que a tecnologia no campo também tem espaço para muita cor, sensibilidade e inovação liderada por meninas!</p>
    </section>

    <section id="projeto" class="content-section card-section">
        <h2>Nossas Ideias 💡</h2>
        <div class="cards-container">
            <div class="card">
                <h3>🌱 Sustentabilidade</h3>
                <p>Cuidado com a terra usando inteligência e tecnologia limpa.</p>
            </div>
            <div class="card">
                <h3>🤖 Tecnologia</h3>
                <p>Automação de processos agrícolas de um jeito simples e visual.</p>
            </div>
            <div class="card">
                <h3>🌸 Design</h3>
                <p>Porque a tecnologia no campo também pode ser linda e intuitiva!</p>
            </div>
        </div>
    </section>

    <footer>
        <p>Feito com 💖 para o Agrinho 2026</p>
    </footer>

</body>
</html>/* Configurações Gerais */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: #fff5f7; /* Fundo rosa bem clarinho */
    color: #4a3b40;
}

/* Menu de Navegação */
header {
    background-color: #ffffff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 5%;
    box-shadow: 0 4px 6px rgba(255, 182, 193, 0.2);
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
    color: #ff85a2; /* Rosa choque suave */
}

nav a {
    text-decoration: none;
    color: #6c757d;
    margin-left: 20px;
    font-weight: 600;
    transition: color 0.3s;
}

nav a:hover {
    color: #ff85a2;
}

/* Seção Principal (Hero) */
.hero {
    background: linear-gradient(135deg, #ffe3ec 0%, #e8f5e9 100%); /* Degradê rosa e verde pastel */
    padding: 80px 5%;
    text-align: center;
}

.hero h1 {
    font-size: 2.5rem;
    color: #d84b72;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 30px;
    color: #616161;
}

.btn {
    display: inline-block;
    background-color: #ff85a2;
    color: white;
    padding: 12px 30px;
    border-radius: 25px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 4px 15px rgba(255, 133, 162, 0.4);
    transition: transform 0.2s;
}

.btn:hover {
    transform: scale(1.05);
}

/* Seções de Conteúdo */
.content-section {
    padding: 60px 5%;
    text-align: center;
}

.content-section h2 {
    color: #d84b72;
    margin-bottom: 20px;
    position: relative;
}

/* Cards do Projeto */
.cards-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
    margin-top: 30px;
}

.card {
    background-color: white;
    border: 2px solid #ffe3ec;
    border-radius: 15px;
    padding: 25px;
    width: 280px;
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.02);
    transition: y 0.3s;
}

.card:hover {
    transform: translateY(-5px);
    border-color: #ff85a2;
}

.card h3 {
    color: #2e7d32; /* Verde fazenda */
    margin-bottom: 15px;
}

/* Rodapé */
footer {
    background-color: #ffe3ec;
    text-align: center;
    padding: 20px;
    color: #d84b72;
    font-weight: 500;
    margin-top: 40px;
}
