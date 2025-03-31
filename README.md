# Web-Page-Primeiros-Passos
Este é um exemplo de como criar uma página web no quesito front-end. Para aqueles que ainda não conhecem o termo, front-end é o aspecto visual de uma web page (barras e letras coloridas, efeitos visuais presentes, etc). Neste exemplo, também pode ser encontrados algumas funções no quesito back-end (botões, link para outras páginas da web, etc), embora eles não estejam funcionando no momento. Isto está aqui somente para servir como base para um projeto ainda em desenvolvimento.

Obs: por favor, não utilize as mesmas referências de links presentes no código que está presente neste repositório. Utilize suas próprias imagens e referências na suas criações baseadas neste programa.

Parte HTML5:

<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Recanto Carneiros</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header></header>
        <main></main>
        <footer></footer>
        <h1>Sejam todos bem-vindos à página da web oficial do <span>Recanto Carneiros</span>!</h1>
        <h2>Aqui você poderá encontrar informações sobre as unidades disponíveis para serem alugadas, além de atrações e pontos turísticos localizados pela região !</h2>
        <p>Entre elas, temos essas referências: </p>
        <img src="imagens/Imagem da praia de Carneiros.jpeg" alt="Foto da praia dos Carneiros">
        <img src="imagens/Imagem de passeios do Manguezal Ecoturismo.jpeg" alt="Imagem do Manguezal Turismo">
        <ul>
            <li>Praia dos Carneiros</li>
            <li>Manguezal Turismo</li>
            <li>Tapera do Sabor</li>
        </ul>
        <p>Para mais informações, entre em contato conosco !</p>
        <a href="link de referência" target="_blank">link</a>
        <button>Botão</button>
    </body>
</html>

#Este código é a fundação da sua página da web. Nele estão as informações que você deseja colocar na sua web-page, como imagens, mensagens de texto, referências, etc. Ele é dividido entre duas partes principais: a head (cabeça) e o body (corpo).

#Na "head", é onde está presente o nome da sua página, dentro da função "title", assim como as ferramentas que lhe ajudam a definir qual será o idioma presente no seu código e alguns outros.

#O "body" contém as mensagens de texto que você colocará na sua web-page, como parágrafos, sub-parágrafos, listas, adiante, além de outras ferramentas, como links, imagens, botões. É nele que ficam as funcionalidades que irão lhe permitir interagir como a sua página web.
///////////////////////////////////////////////////////////////////////////////////
Agora que você viu como se dá os passos inicias para criar uma web-page, agora deve-se aprender a como decorar sua página, como adicionar camadas de cores para seus parágrafos e linhas, adicionar efeitos especiais, dentres outros. Para isso, você deve aprender a programar com a linguagem CSS. Logo abaixo, está o código usado neste projeto para adicionar cores para uma aréa específica do parágrafo inicial, a tela de fundo da página e o botão.
//////////////////////////////////////////////////////////////////////////////////
Parte CSS:

body {
    background-color: white;
    color: rgb(4, 189, 4);
}

button {
    background-color: white;
    color: black;
}
   footer {
       background-color: gray;
       color: white;

   }
h1 {
    font-weight: bold;
}

span {
    color: #22D4FD;
    border: 1px solid #22D4FD;
    padding: 10px;
}
#Por enquanto, isto é o que está disponível. Obrigado por utilizar este código como base para seus próprios projetos. Até o próximo repositório !
