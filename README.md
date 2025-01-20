<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gestão Escolar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #004d99;
            color: white;
            padding: 20px 10px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: space-around;
            background-color: #0066cc;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-size: 1.2em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            margin: 20px;
        }
        .section {
            background: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #004d99;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gestão Escolar</h1>
        <p>Bem-vindo ao sistema de gestão escolar!</p>
    </header>
    <nav>
        <a href="#matriculas">Matrículas</a>
        <a href="#diario">Diário do Professor</a>
        <a href="#plano">Plano de Aula</a>
        <a href="#portfolios">Portfólios</a>
        <a href="#chat">Chat com a Família</a>
        <a href="#documentos">Documentos Escolares</a>
    </nav>
    <div class="container">
        <section id="matriculas" class="section">
            <h2>Matrículas</h2>
            <p>Área para cadastrar e gerenciar as matrículas dos alunos.</p>
            <button>Gerenciar Matrículas</button>
        </section>

        <section id="diario" class="section">
            <h2>Diário do Professor</h2>
            <p>Espaço para o professor registrar informações diárias.</p>
            <button>Acessar Diário</button>
        </section>

        <section id="plano" class="section">
            <h2>Plano de Aula</h2>
            <p>Organize seus planos de aula mensais e semanais.</p>
            <button>Gerenciar Planos</button>
        </section>

        <section id="portfolios" class="section">
            <h2>Portfólios</h2>
            <p>Armazene e visualize os portfólios dos alunos.</p>
            <button>Visualizar Portfólios</button>
        </section>

        <section id="chat" class="section">
            <h2>Chat com a Família</h2>
            <p>Ferramenta para comunicação entre escola e família.</p>
            <button>Acessar Chat</button>
        </section>

        <section id="documentos" class="section">
            <h2>Documentos Escolares</h2>
            <p>Gerencie documentos importantes da escola.</p>
            <button>Gerenciar Documentos</button>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 Gestão Escolar. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
