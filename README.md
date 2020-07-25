# Index
#CSS
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <link href="./CSS/CSS.css" rel="stylesheet">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shotcurt icon" href="img/logo.png" type="image/x-icon">
    <title>SofTech</title>
<head>
<body> 
    <header>
         <img src="img/logo.png" class="logo" alt="Logo">
         <h1 style="color:blue;">SofTeech</h1>
         <p>
           Oferecemos o desenvolvimento 
                   dos melhores sites 
                       e apps para sua empresa.
         </p>
    </header>
    <div class="menu">
        <nav>
            <ul>
                <li><a href="#servicos">SERVIÇOS</a></li>
                <li><a href="#clientes">CLIENTES</a></li>
                <li><a href="#time">TIME</a></li>
                <li><a href="#parceiros">PARCEIROS</a></li>
                <li><a href="#contato">CONTATO</a></li>
            </ul>
        </nav>
    </div>
    <section id="servicos">
        <h2>SERVIÇOS</h2>
        <p>
            Oferecemos o desenvolvimento dos melhores
            sites e apps para sua empresa.
        </p>

        <div class="linha">
            <div class="coluna">
                <img src="img/servico1.jpg" alt="Serviço" class="img_padrao">
            </div>
            <div class="coluna">
                <img src="img/servico2.jpg" alt="Serviço" class="img_padrao">
            </div>
            <div class="coluna">
                <img src="img/servico3.jpg" alt="Serviço" class="img_padrao">
            </div>
        </div>
    </section>

    <section id="clientes">
        <h2>CLIENTES</h2>
        <p>
            Temos 100% de satisfação dos nossos clientes.
        </p>

        <div class="linha">
            <div class="coluna">
                <img src="img/cliente1.jpg" alt="Cliente" class="img_padrao">
            </div>
            <div class="coluna">
                <img src="img/cliente2.jpg" alt="Cliente" class="img_padrao">
            </div>
            <div class="coluna">
                <img src="img/cliente3.jpg" alt="Cliente" class="img_padrao">
            </div>
        </div>
    </section>

    <section id="time">
        <h2>TIME</h2>
        <p>
            Nosso time está preparado
                 para qualquer
                    desafio. E garantimos
                        ótimo desempenho e qualidade
                            dos nossos serviços.
        </p>

        <div class="linha">
            <div class="coluna">
                <img src="img/time1.png" alt="Time" class="img_padrao">
            </div>
            <div class="coluna">
                <img src="img/time2.jpg" alt="Time" class="img_padrao">
            </div>
            <div class="coluna">
                <img src="img/time3.jpg" alt="Time" class="img_padrao">
            </div>
        </div>
    </section>

    <section id="parceiros">
        <h2>PARCEIROS</h2>
        <p>
            Nossos parceiros nos ajudam a entregar as melhores soluções
                para nossos clientes.
        </p>
        <a href="https://www.ibm.com/br-pt" target="blank"> <img src="img/parceiro1.png" alt="Parceiro" class="logo-parc"></a>
        <a href="https://www.microsoft.com/pt-br" target="blank"> <img src="img/parceiro2.png" alt="Parceiro"class="logo-parc"></a>
    </section>

    <section id="contato">
        <h2>CONTATO</h2>
        <p>
            Entre em contato com nossa equipe.
        </p>
        <p>
            <img src="img/email.png" alt="Email" class="logo_cont">
            <a href="mailto:contato@empresa.com">contato@empresa.com.br</a></p>
        </p>
        <p>
            <img src="img/fone.png" alt="Telefone" class="logo_cont">
            <a href="tel: 6199999999">(61)9999-9999</a></p>
        </p>    
    </section>
    <footer>
        Desenvolvido por Patrick Souza.
    </footer>
    <!--Opção de botão para retornar ao menu-->
     <!--<a href="index.html"><button>Página Inicial</button></a>-->

</body>
</html>

body {
    background-color: #EFEFFB;
    margin: 0;
}

header {
    background-color: #53e2e7;
    display: table;
    width: 100%;
}

.logo {
    margin: 30px 20px 20px 80px;
    width: 90px;
    height: 90px;
    float: left;
}

.texto {
    float: left;
    width: 100%;
    line-height: 15px;
}

.menu {
    text-align: center;
    background-color: rgb(17, 145,145);
}

.menu ul {
    margin: 0;
}

.menu li {
    display: inline-block;
    padding: 6px 25px;
}

.menu li :hover {
    font-weight: bold;
}

.menu a {
    text-decoration: none;
}

section {
    margin: auto;
    width: 80%;
}

.img_padrao {
    margin: 10px 0 20px 0;
    border-radius: 8px;
    width: 95%;
    height: 250px;
}

.coluna {
    float: left;
    width: 33.33%;
}

.linha::after {
    content: "";
    clear: both;
    display: table;
}

.logo-parc {
    margin: 20px;
    width: 150px;
    height: 60px;
    
}

.logo_cont{
    margin-top: 10px;
    width: 30px;
}

footer {
    display: flex;
    justify-content: center;
    margin: 30px 0 30px 0;
}

p {
    text-align: justify;
    font-size: 18px;
    margin: 0;
}

h1 {
    font-size: 50px;
    margin-top: 30px;
    margin-bottom: 0;
}

h2 {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    text-align: center;
}
