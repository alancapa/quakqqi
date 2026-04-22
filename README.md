<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experimento de Mobilidade e Acessibilidade Urbana</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <a href="#conteudo-principal" class="skip-link">Pular para o conteúdo principal</a>

    <header class="site-header">
        <div class="container header-content">
            <div class="logo">AcessoUrbs</div>
            <button id="menu-toggle" class="menu-toggle" aria-expanded="false" aria-controls="main-nav" aria-label="Abrir menu de navegação">
                <span class="hamburger"></span>
            </button>
            <nav id="main-nav" class="main-nav">
                <ul>
                    <li><a href="#hero">Início</a></li>
                    <li><a href="#tecnologias">Tecnologias</a></li>
                    <li><a href="#design-universal">Design Universal</a></li>
                    <li><a href="#fontes">Créditos</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main id="conteudo-principal">
        <section id="hero" class="hero fade-in">
            <div class="container">
                <h1>A Cidade para <span>Todos</span></h1>
                <p>Explorando inovações em mobilidade e acessibilidade urbana para construir espaços onde o ir e vir seja um direito garantido, independente de condições físicas ou sensoriais.</p>
                <a href="#tecnologias" class="btn-cta">Descubra as Tecnologias</a>
            </div>
        </section>

        <section id="tecnologias" class="section bg-light">
            <div class="container fade-in">
                <h2>Inovações em Acessibilidade</h2>
                <div class="cards-grid">
                    <article class="card">
                        <div class="card-icon" aria-hidden="true">♿</div>
                        <h3>Rampas Inteligentes</h3>
                        <p>Sistemas automatizados e modulares que se ajustam ao nível do transporte público, garantindo embarque autônomo para cadeirantes.</p>
                    </article>
                    <article class="card">
                        <div class="card-icon" aria-hidden="true">🦯</div>
                        <h3>Sensores Urbanos</h3>
                        <p>Semáforos e calçadas equipados com beacons bluetooth que enviam sinais sonoros espaciais e alertas para smartphones de pessoas cegas.</p>
                    </article>
                    <article class="card">
                        <div class="card-icon" aria-hidden="true">🚐</div>
                        <h3>Transporte Adaptado 2.0</h3>
                        <p>Frotas projetadas com piso baixo integral, fixadores universais e painéis de comunicação em Libras guiados por IA.</p>
                    </article>
                </div>
            </div>
        </section>

        <section id="design-universal" class="section fade-in">
            <div class="container content-text">
                <h2>A Importância do Design Universal</h2>
                <p>O <strong>Design Universal</strong> não é sobre criar nichos especiais, mas sobre desenvolver ambientes, produtos e serviços que possam ser utilizados pelo maior número possível de pessoas, sem necessidade de adaptação.</p>
                <p>Quando projetamos calçadas niveladas, não beneficiamos apenas cadeirantes, mas também idosos, pessoas empurrando carrinhos de bebê e trabalhadores transportando cargas. Uma cidade acessível é, fundamentalmente, uma cidade mais eficiente e humana para toda a sua população.</p>
            </div>
        </section>
    </main>

    <footer id="fontes" class="credits-section">
        <div class="container">
            <h3>Fontes e Referências</h3>
            <ul>
                <li><a href="https://www.w3.org/WAI/" target="_blank" rel="noopener noreferrer">W3C - Web Accessibility Initiative</a></li>
                <li><a href="https://www.gov.br/mdh/pt-br" target="_blank" rel="noopener noreferrer">Ministério dos Direitos Humanos e da Cidadania (LBI)</a></li>
                <li><a href="https://unhabitat.org/" target="_blank" rel="noopener noreferrer">ONU-Habitat - Programa das Nações Unidas para os Assentamentos Humanos</a></li>
                <li><a href="https://www.ibge.gov.br/" target="_blank" rel="noopener noreferrer">IBGE - Estatísticas de População</a></li>
            </ul>
            <p class="footer-note">Desenvolvido como um experimento educativo sobre mobilidade urbana e acessibilidade digital.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
