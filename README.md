<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Repositório do Site de Motocicletas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0 20px;
        }
        h1, h2 {
            color: #444;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .image-gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .image-gallery img {
            flex: 1 1 calc(33.333% - 10px);
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
        .code-block {
            background: #f4f4f4;
            border-left: 3px solid #ccc;
            padding: 10px;
            margin: 20px 0;
            overflow-x: auto;
        }
        a {
            color: #007BFF;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Motocicletas - A Paixão sobre Duas Rodas</h1>
        <p>
            Este repositório contém o código-fonte de um site dedicado aos amantes de motocicletas. O site oferece uma variedade de recursos, incluindo:
        </p>
        <ul>
            <li>Informações detalhadas sobre diferentes modelos de motocicletas</li>
            <li>Galerias de fotos de alta qualidade</li>
            <li>Notícias e atualizações do mundo do motociclismo</li>
            <li>Tutoriais e dicas de manutenção</li>
            <li>Uma comunidade de entusiastas para discussões e troca de experiências</li>
        </ul>
        
        <h2>Galeria de Imagens</h2>
        <div class="image-gallery">
            <img src="https://example.com/path/to/image1.jpg" alt="Motocicleta 1">
            <img src="https://example.com/path/to/image2.jpg" alt="Motocicleta 2">
            <img src="https://example.com/path/to/image3.jpg" alt="Motocicleta 3">
        </div>

        <h2>Como começar</h2>
        <p>
            Para começar a explorar o projeto, clone este repositório em sua máquina local:
        </p>
        <div class="code-block">
            <code>git clone https://github.com/seu-usuario/seu-repositorio.git</code>
        </div>
        
        <h2>Tecnologias utilizadas</h2>
        <ul>
            <li>HTML5 e CSS3 para a estrutura e o design do site</li>
            <li>JavaScript para interatividade e funcionalidades dinâmicas</li>
            <li>Frameworks e bibliotecas como Bootstrap e jQuery</li>
        </ul>
        
        <h2>Contribuições</h2>
        <p>
            Contribuições são bem-vindas! Sinta-se à vontade para abrir issues para relatar problemas ou sugerir melhorias, e enviar pull requests para adicionar novas funcionalidades ou corrigir bugs.
        </p>
        <p>
            <a href="https://github.com/seu-usuario/seu-repositorio/issues">Relatar um problema</a> | 
            <a href="https://github.com/seu-usuario/seu-repositorio/pulls">Enviar um pull request</a>
        </p>
        
        <h2>Licença</h2>
        <p>
            Este projeto está licenciado sob a <a href="https://opensource.org/licenses/MIT">Licença MIT</a> - veja o arquivo <a href="https://github.com/seu-usuario/seu-repositorio/blob/main/LICENSE">LICENSE</a> para mais detalhes.
        </p>
    </div>
</body>
</html>
