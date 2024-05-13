# Resultado
### (algo próximo disto)

![alt text](image.png)

isto para primeira parte em seguida o resultado com reposicionamento dos itens.

com o reposicionamento e ajuste tamanho  deve ficar parecido como abaixo:

![alt text](image-1.png)

<hr>

Agora vamos focar no estudo de como foi escrito o nosso CSS. (vejamos abaixo):

``` css
.mesa{
    position: fixed;
    width:900px;
    height:600px;
    background-color: green;
      }
.robot{
   position: relative;
   top:5px;
   left:15px;
   width:160px;
   height:60px;
   background-color: black;  }      
.jogador{
    position: relative;
    top:390px;
    left:15px;
    width:160px;
    height:60px;
    background-color: black; }   
.baralho{
    position: relative;
    top:200px;
    left:315px;
    width:60px;
    height:80px;
    background-color:yellow;}   
```
Nome: LoyrHm
Codigo do JOGO21.HTML:
``` HTML
<!DOCTYPE html> <!-- Define o tipo de documento, no caso HTML5 -->
<html lang="en"> <!--  inglês -->
<head> <!-- Começa a seção de cabeçalho do documento -->
    <meta charset="UTF-8"> <!-- Define o conjunto de caracteres como UTF-8 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Define as configurações de viewport para dispositivos móveis -->
    <title>Document</title> <!-- Define o título da página -->
    <link rel="stylesheet" href="estilo.css"> <!-- Liga o arquivo CSS para estilizar a página -->
</head>
<body> <!-- Começa a seção de corpo do documento -->
    <div class="mesa"> <!-- Cria uma div com a classe "mesa" -->
        <div class="robot"></div> <!-- Cria uma div com a classe "robot" -->
        <div class="baralho"></div> <!-- Cria uma div com a classe "baralho" -->
        <div class="jogador"></div> <!-- Cria uma div com a classe "jogador" -->
    </div>
</body>
</html>
```

CÒDIGO DO ESTILO.CSS

``` css
.mesa{ /* cria a classe "mesa" */
    position: fixed; /* Mantém a tag com a classe mesa fixada na tela */
    width: 900px; /* Define a LARGURA como 900 pixels */
    height: 600px; /* Define a ALTURA como 600 pixels */
    background-color: green; /* Define a COR DE FUNDO como verde */
}

.robot{ /* cria a classe "robot" */
    position: relative; /* Permite mover o robô dentro da mesa */
    top: 5px; /* Move 5 pixels para baixo em relação à sua posição normal */
    left: 15px; /* Move 15 pixels para a direita em relação à sua posição normal */
    width: 160px; /* Define a LARGURA do robô como 160 pixels */
    height: 60px; /* Define a ALTURA do robô como 60 pixels */
    background-color: black; /* Define a cor de fundo como preta */
}

.jogador{ /* Cria a classe "jogador" */
    position: relative; /* Permite mover o jogador dentro da mesa */
    top: 390px; /* Move 390 pixels para baixo em relação à sua posição normal */
    left: 15px; /* Move 15 pixels para a direita em relação à sua posição normal */
    width: 160px; /* Define a LARGURA do jogador como 160 pixels */
    height: 60px; /* Define a ALTURA do jogador como 60 pixels */
    background-color: black; /* Define a cor de fundo como preta */
}

.baralho{ /* Cria a classe "baralho" */
    position: relative; /* Permite mover o baralho dentro da mesa */
    top: 200px; /* Move 200 pixels para baixo em relação à sua posição normal */
    left: 315px; /* Move 315 pixels para a direita em relação à sua posição normal */
    width: 60px; /* Define a LARGURA como 60 pixels */
    height: 80px; /* Define a ALTURA como 80 pixels */
    background-color: yellow; /* Define a cor de fundo como amarela */
}
```

