# projeto_final_css

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Currículo de Adam Keyes - Desenvolvedor Front-end</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #363232;
    }


    .container {
        max-width: 800px;
        margin: 20px auto;
        padding: 20px;
        background-color: #837878;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h1, h2, h3 {
        margin-bottom: 10px;
    }
    p {
        margin: 5px 0;
    }
    .section {
        margin-bottom: 20px;
    }
    .skills {
        margin-top: 10px;
    }
    .skill {
        display: inline-block;
        background-color: #007bff;
        color: #fff;
        padding: 5px 10px;
        margin-right: 5px;
        border-radius: 5px;
    }
    .experience, .education {
        margin-top: 20px;
    }
    .experience h3, .education h3 {
        margin-bottom: 5px;
    }
    .experience p, .education p {
        margin: 5px 0;


    }

    .foto{margin-left: 600px;


    }
    .tudo{margin top: 190px;}


    

    
</style>
</head>
<body>
<div class="container">
    <h1>Currículo</h1>
    <div class="section">
        <h2>Adam Keyes</h2>
        <p>Desenvolvedor Front-end</p>
        <p>Contato: adamkeyes@example.com | Telefone: (123) 456-7890 | Localização: Cidade, País</p>
        <div class="foto">
        <img src="https://adamkeyes-portfolio.vercel.app/assets/images/image-profile-desktop.webp" height="180px" width="100px"></img> </div>
    </div>

    <div class="tudo">
    <div class="section experience">
        <h3>Experiência Profissional</h3>
        <p><strong>Desenvolvedor Front-end</strong></p>
        <p>Empresa ABC - Cidade, País</p>
        <p>Julho 2020 - Presente</p>
        <ul>
            <li>Desenvolvimento e manutenção de interfaces de usuário responsivas usando HTML, CSS e JavaScript.</li>
            <li>Colaboração com a equipe de design para implementar designs de alta qualidade.</li>
            <li>Otimização de desempenho e acessibilidade do site.</li>
        </ul>
    </div>
    <div class="section education">
        <h3>Educação</h3>
        <p><strong>Bacharel em Ciência da Computação</strong></p>
        <p>Universidade XYZ - Cidade, País</p>
        <p>Setembro 2016 - Junho 2020</p>
    </div>
    <div class="section skills">
        <h3>Habilidades</h3>
       <li> HTML5</li>
       <li>CSS3</li>
       <li>JavaScript</li>
       <li>Responsive Design</li>
       <li>Bootstrap</li>
       <li>SASS/SCSS</li>
       <li>Git</li>
    </div>
    <div class="Projetos"><h1>Projects</h1>
    <img src="https://neilpatel.com/wp-content/uploads/2023/06/Best_landing_pages3-700x397.jpg"></img></div></div>
</div>
</body>
</html>
