# notas-estudos
aulas do senac sobre programação 
markdown

git 

## configurando Git 


para ultilizar o git na minha maquina eu preciso configura determinados comandos, sendo eles

git   
````bash
git config  --global
```` 


aula do melhro sor 
CONFG REPOSITORIO GIT HUB
 
abrir o git hub, clicar na foto de perfil
clicar em repositers, e new
colocar o nome: avaliaçao-2026 (coloque uma descriçao, oque vai ter dentro do repositorio)
visibilidade: publica
add readme: ON
com o repositorio criado, clica em code, SSH e copia
vai no git bash
escreve cd doc, da tab e enter dps (tem que aparecer cd Documents/)
dai escreve git clone, da espaço e cola o negocio do SSH
pra fazer isso, clica no botao direito e em paste
sai do git bash e vai pro vscode, botao direito ctrl K O
entra na pasta/repositorio que vc criou
depois, botao direito no vazio, new filer, e escreve index html
pra criar o scripts, faz a mesma coisa mas clica no new folder
 
-------------------------------------------------------------------------------------------------------------------
HTML
 
 dentro do index html: ! enter
 tira o en, e coloca "pt-br" (pra deixer em portugues automatico)
 
-------------------------------------------------------------------------------------------------------------------
STYLE
 
criar um "style" para estilizar o site (botao direito, new folder)
dentro do "style" escreve "style.css" (botao direito, new filer)
 
e copia tudo aquilo que ta no style.css
 
-------------------------------------------------------------------------------------------------------------------
ai vai no index.html, apaga aquelas coisas e copia isso
 
<!DOCTYPE html>
<html lang="pt-br">
 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./style/style.css">
</head>
 
<body>
   
    <header id="exemplo">
        avaliaçao
    </header>
 
    <main>
        <h2>exercicios</h2>
        <button id="exercicio1">Executar exercicio 1</button>
        <button id="exercicio2">Executar exercicio 2</button>
         <button id="exercicio3">Executar exercicio 3</button>
        <button id="exercicio4">Executar exercicio 4</button>
        <button id="exercicio5">Executar exercicio 5</button>
        <button id="exercicio6">Executar exercicio 6</button>
        <button id="exercicio7">Executar exercicio 7</button>
        <button id="exercicio8">Executar exercicio 8</button>
        <button id="exercicio9">Executar exercicio 9</button>
        <button id="exercicio10">Executar exercicio 10</button>
        <button id="exercicio11">Executar exercicio 11</button>
         <button id="exercicio12">Executar Exercicio 12</button>
        <button id="exercicio13">Executar Exercicio 13</button>
        <button id="exercicio14">Executar Exercicio 14</button>
        <button id="exercicio15">Executar Exercicio 15</button>
        <button id="exercicio16">Executar Exercicio 16</button>
        <button id="exercicio17">Executar Exercicio 17</button>
        <button id="exercicio18">Executar Exercicio 18</button>
    </main>
 
 <footer id="rodape" >
         avaliaçao 19/03
    </footer>
<script src="./script/teste.js"></script>
</body>
 
</html>            
 
-------------------------------------------------------------------------------------------------------------------
 
<link rel="stylesheet" href="./style/style.css">
 "./style/style.css"> ( reescreve essa parte, pra desbugar )          
 
 e muda tambem    <script src="./script/teste.js"></script>
     
(teste.js, no caso cocloca a pasta que voce tiver usando pra avaliaçao, e lembra de colocar .js no final)
 
 
 

automáticocontente 
body {
    background-color: #EEE;
    margin: 0 auto;
    font-family: Arial, Helvetica, sans-serif;
}
h1 {
    margin: 0 0 20px 0;
}
 
header {
    background-color: #af6b4c;
    color: #FFF;
    text-align: center;
    padding: 16px;
}
 
header a {
    text-decoration: none;
    background-color: #6d4330;
    color: #FFF;
    border-radius: 4px;
    padding: 10PX 20PX;
    transition: background-color 1s ease;
}
header a:hover {
    background-color: #351f15;
}
/* Além do :hover existem também os estados :focus e :active que podem ser usados para melhorar a acessibilidade e a experiência do usuário */
main {
    padding: 16px; /*   %    rem  */
}
 
section {
    background-color: #FFF;
    padding: 16px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    margin: 16px 0;
    /* margin-top: 16px;
    margin-bottom: 16px; */
}
 
.last {
    margin-bottom: 80px;
}
/*
Você pode usar a classe .last para adicionar uma margem maior ao último elemento,
ou usar o seletor :last-child para selecionar o último elemento de um tipo específico.
Exemplo:
 
section:last-child {
    margin-bottom: 80px;
}
*/
 
h2 {
    border-bottom: 2px solid #af6b4c;
    padding-bottom: 8px;
    margin-bottom: 16px;
}
 
input, textarea, select {
    width: 99%;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
}
#cor {
    width: 50px;
    height: 50px;
}
 
form div {
    margin-bottom: 16px;
}
 
form button {
    background-color: #af6b4c;
    color: #FFF;
    border-radius: 4px;
    border: none;
    padding: 12px 24px;
    cursor: pointer;
}
form button:hover {
    background-color: #48281a;
}
 
footer {
    background-color: #af6b4c;
    padding: 16px;
    text-align: center;
    color: #FFF;
    font-size: 16px;
 
    position: fixed;
    bottom: 0;
    width: 100%;
}
 
