# Tabela html
• Repositório tabela do módulo html

• SITE DE RECEITAS

• Menções:
  • Primeiro projeto feito sozinho
  • Tive que recorrer ao chatGPT 3 vezes para criar uma aparência de folha central, para juntar dois textos com cores (tag <span>). (Lembrete: Tive que usar duas vezes para setar as cores e juntar os textos)
  • Tive dificuldade diverças vezes e tive que recorrer a um código já feito com muita ajuda dos devs criadores do canal no youtube Dev em Dobro, na Semana do 0 ao programador contratado.
  • Tive extremas facilidade ao realizar os códigos em css.
  • Projeto feito para o frontEnd Mentor.
  • Tive dificuldades de conseguir criar um texto intuitivo e legal
  • Tive que olhar diversas vezes para o modelo final no frontEnd Mentor
  • As fontes e imagens foram retiradas do frontEnd Mentor

• Aqui está o código: (HTML)

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Folha na Tela com Bordas Redondas</title>
    <link rel="stylesheet" href="./src/css/estilos.css">
    <link rel="stylesheet" href="./src/css/fontes.css">
    <link rel="stylesheet" href="./src/css/reset.css">
    <style>
        body {
            background-color: #f8f8f8; /* Cor de fundo semelhante ao papel */
            margin: 20px; /* Margens para imitar o espaço em branco em uma folha */
            font-family: Arial, sans-serif; /* Fonte padrão */
        }

        .folha {
            background-color: #ffffff; /* Cor da folha (branca) */
            padding: 20px; /* Preenchimento interno para simular o conteúdo na folha */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Sombra para dar profundidade */
            max-width: 1310px; /* Largura máxima da folha para evitar que ocupe toda a largura da tela */
            margin: 0 auto; /* Centralizar a folha na tela */
            border-radius: 10px; /* Borda redonda */
        }
    </style>
    <style>
        .esquerda {
            color: black; /* Cor da frase à esquerda */
            float: left; /* Move para a esquerda */
        }

        .direita {
            color: brown; /* Cor da frase à direita */
            float: right; /* Move para a direita */
        }

        /* Limpar as propriedades float para evitar problemas de layout */
        .clear {
            clear: both;
        }
    </style>
    <style>
        .duas-cores {
            color: brown; /* Cor da primeira parte da linha */
        }

        .outra-cor {
            color: black; /* Cor da segunda parte da linha */
        }
    </style>
</head>
<body>
    <div class="geral">
        <div class="folha">
            <div class="cabecalho">
                <img src="./src/imagens/image-omelette.jpeg" alt="imagem de um omelte">
                <h1 class="tituloa">
                    Receita de um Omelete Simples
                </h1>
                <p class="texto">
                    É fácil e rápido. Perfeito para um lanche. Esse clássico omelete<br>combina ovos fritos com coisas a gosto.
                </p>
            </div>
            <div class="preparo">
                <h1 class="titulo">
                        Tempo de Preparo:
                </h1>
                <div class="preparo2">
                    <p class="textoa">
                        <span class="duas-cores">•</span>
                        <span class="outra-cor">Total: Aproximadamente 10 minutos;</span>
                    </p>
                    <p class="textoa">
                        <span class="duas-cores">•</span>
                        <span class="outra-cor">Preparo: 5 minutos;</span>
                    </p>
                    <p class="textoa">
                        <span class="duas-cores">•</span>
                        <span class="outra-cor">cozinhamentoeds: 5 minutos;</span>
                    </p>
                </div>
            </div>
            <div class="ingredientes">
                <h1 class="titulo">
                    Ingredientes:
                </h1>
                <div class="ingredientes2">
                    <p class="textoa">
                        <span class="duas-cores">•</span>
                        <span class="outra-cor">2-3 ovos largos;</span>
                    </p>
                    <p class="textoa">
                        <span class="duas-cores">•</span>
                        <span class="outra-cor">Sal a gosto;</span>
                    </p>
                    <p class="textoa">
                        <span class="duas-cores">•</span>
                        <span class="outra-cor">Pimenta a gosto;</span>
                    </p>
                    <p class="textoa">
                        <span class="duas-cores">•</span>
                        <span class="outra-cor">Colher de sopa ou óleo;</span>
                    </p>
                    <p class="textoa">
                        <span class="duas-cores">•</span>
                        <span class="outra-cor">Recheios opcionais: queijo, vegetais em cubos,<br>carnes cozidas, ervas e etc;</span>
                    </p>
                    
                <div class="instrucoes">
                    <h1 class="titulo">
                        Instruções
                    </h1>
                    <div class="instrucoes2">
                        <p class="textoa">
                            <span class="duas-cores"><strong>1.</strong></span>
                            <span class="outra-cor"><strong>Bater os ovos.</strong> Em um pote, bata os ovos com uma pitada de sal e pimenta até tudo se juntar. Você pode adicionar uma colher de água ou leite para diluir a textura.</span>
                        </p>
                        <p class="textoa">
                            <span class="duas-cores"><strong>2.</strong></span>
                            <span class="outra-cor"><strong>Aqueça a panela.</strong> Coloque um antiderente ou manteiga na panela em temperatura média para não grudar o omelete.</span>
                        </p>
                        <p class="textoa">
                            <span class="duas-cores"><strong>3.</strong></span>
                            <span class="outra-cor"><strong>Cozinhe o omelete. </strong>Quando a manteiga borbulhar na panela coloque os ovos.Vire a panela para garantir que os ovos cozinhem na superfície.</span>
                        </p>
                        <p class="textoa">
                            <span class="duas-cores"><strong>4.</strong></span>
                            <span class="outra-cor"><strong> Adicione recheios (opicional). </strong>Quando os ovos estiverem cozinhados coloque os recheios a gosto.</span>
                        </p>
                        <p class="textoa">
                            <span class="duas-cores"><strong>5.</strong>.</span>
                            <span class="outra-cor"><strong> Dobre e sirva. </strong>Quando o omelete terminar o cozinhamento, coloque-o em um prato, dobre-o com uma espatula ou algo parecido, e sirva-o.</span>
                        </p>
                        <p class="textoa">
                            <span class="duas-cores"><strong>6.</strong></span>
                            <span class="outra-cor"><strong>6. Aproveite. </strong>Siva quente, com sal adicional e pimenta se nessesário.</span>
                        </p> 
                    </div>
                </div>
   
                </div>
            </div>
        </div>
    </div>
</head>
<body>
    
</body>
</html>

• Aqui está o segundo código: (Está na seguinte ordem: Código de estilização do projeto(estilos.css), Código para setar fontes internas(fontes.css))

  body{
    background-color: #FFF0CB;
}

.titulo{
    font-family: Young;
    font-size: 50px;
    color: #a95e13;
}

.tituloa{
    font-family: Young;
    font-size: 50px;
}

.outra-cor{
    font-family: Outfit;
    font-size: 25px;
}

.texto{
    font-family: Outfit;
    font-size: 25px;
}

.textoa{
    color: brown;
}

.direita, .esquerda{
    font-family: Outfit;
}

.instrucoes{
    border-top: 1px solid #282828;
}

.ingredientes{
    border-top: 1px solid #282828;
}

.preparo{
    border-top: 1px solid #282828;
}

_________________________________________________________________________________________________________________________________________________


@font-face {
    font-family: "Outfit";
    src: url(/src/fontes/Outfit-VariableFont_wght.ttf);
}

@font-face {
    font-family: "Young";
    src: url(/src/fontes/YoungSerif-Regular.ttf);
}
