1.  O projeto de hoje consiste em uma Landing Page sobre arquitetura com um breve formulario feito em Sheet Monkey e anexado com o Google Planilhas.
   O arquivo esta dividido em Index.html e tambem em Style.css, nao foi utilizado nenhum tipo de integraçao com o JavaScript


- 1 div -> "menusup" Aonde contem a parte inicial do site (background) | class="textosmenu -> classe aonde contem os textos do inicio da web;
	 
- 2 div -> part2num1 Contem o background cor das letras, margem do background;
	 
- 3 div -> part2num2 -> Contem o texto de numero 2, da segunda parte do site;
   
- 4 div -> part2num3 -> Contem o texto de numero 3, da segunda parte do site;
   
- 5 div -> class="partimg -> contem toda a 3 parte do site, imagem, background | id="imgarch" -> Contem a imagem | id="tetoimg" -> Contem o texto "Arquitetos com História e Experiência." |
-  id="tetoimg2" -> Contem o texto

- 6 <div id="form" -> Aqui nesta Div se inicia o formulario. | id="textoform -> contem o texto da parte final do site | input id="nomeform" -> Aonde tem o input do Nome no formulario |
- input id="mailform" -> Contem o input do Email. 


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


8. *CSS:* Descreva o estilo CSS aplicado ao projeto. Isso pode incluir cores, fontes, layout e outros estilos. Liste as classes e IDs usados no CSS e explique como eles afetam a aparência do projeto.

*    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
*

#menusup ->  Aonde contem toda a parte inicial do projeto, background, margens e etc.

#tit -> Aonde foi arrumado e centralizado o titulo principal 

#subt -> Aonde foi arrumado e centralizado o titulo principal

.textosmenu -> Classe aonde organiza todos juntos

#part2num1 -> Aqui começa a parte 2 do site, na qual contem 3 textos em seguida um paralelo lateralmente ao outro

#numero{
    margin-top: 20px;
    margin: 40px;
    margin-left: 70px;
    text-align: left;
}

#textonum{
    margin: 40px;
    margin-top: -60px;
    margin-left: 70px;
    text-align: left;

}

.textsecondo{
    margin-left: 50px;
}

#part2num3{
text-align: center;
margin-top: -129px;
color: black;
}

#numero2{
    margin-right: 190px;
    margin-top: 32px;
    line-height: 0.5px;
}

#part2num3{

    text-align: right;
    color: black;
    margin-top: -39px;
    margin-right: 80px;
}

#numero3{
    line-height: 0.5px;
    margin-right: 53px;
    

}

.partimg{

    text-align: right;
    margin-top: 160px;
    margin-right: 90px;
    height: 200px;
    background-size: contain;
    background-color: rgb(255, 255, 255);
    margin: -18.5px; 
    padding: 1%;
    background-size: cover;   
    margin-top: 63px;
    padding: 20%;
    color: rgb(0, 0, 0);


}



#tetoimg{
    text-align: left;
    margin-left: -250px;
    margin-top: -500px;
    font-size: 320%;
}

#tetoimg:hover{
   color:  cornflowerblue;
    transform:translateY(-7px);
    transition-duration:0.2s;
    

}

#tetoimg2{
text-align: left;
margin-left: -250px;
margin-top: 10%;
font-size: 200%;
}

#imgarch{
    margin-left: 900px;
    margin-top: -200px;
    cursor: pointer;

}


#form{
    text-align: right;
    margin-top: 160px;
    margin-right: 90px;
    height: 300px;
    background-size: contain;
    background-color: rgb(65, 65, 65);
    margin: -373px; 
    padding: 1%;
    background-size: cover;   
    margin-top: 267px;
    padding: 25%;
    color: rgb(0, 0, 0);
    
}

#textoform{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    color: rgb(255, 255, 255);
    font-size: 250%;
    margin-top: -175px;
    text-align: center;
}

#button{
    background-color: chocolate;
    height: 80px;
    width: 500px;
    font-size: 190%;
    color: white;
    border-radius: 5px;
    border: 0px;
    margin-right: 32%;
    margin-top: -40%;
    font-weight: bolder;
    cursor: pointer;
    margin-top: -1%;

}

#button:hover{
    background-color: cornflowerblue;
    color: aliceblue;
    transform:translateY(-7px);
    transition-duration:0.5s;
    box-shadow: 0px 15px 20px rgb(65, 65, 65);


}

.inputform{
    width: 600px;
    height: 70px;
    background-color: whitesmoke;
    margin: 30px;
    border: 5px;
    border-radius: 5px;
    margin-right: 380px;
    font-size: larger;
    margin-top: 10%;
    font-weight: 100;
}
     
#nomeform{
    margin-top: 10%;
}

#mailform{
    margin-top: -40px;
}










9. *Funcionalidades:* Liste e descreva as principais funcionalidades do projeto, como interações do usuário, animações ou qualquer outra coisa relevante.
Algumas funcionalidades:

1- Arquitetos com História e Experiência -> Fica azul quando passa o mouse em cima do mesmo.
2- O fomulario -> No formulario, temos o campo de nome e email como input, que as informaçoes sao armazenadas na planilha
3- O botao "Fale Conosco" -> Tem uma funcionalidade de submeter as informaçoes para a planilha e tambem troca a cor quando clicado no mesmo.



Material usados como referencia: https://www.figma.com/file/0FRiZbs30dfSniazKiM1rM/Desafio-1---Desenvolva-uma-Landing-Page?mode=dev 



    Att.: Kauã Fernandes


_____000000000____________________00000000000_____
___0000______00__00000000000000_00_________0000___
_00__________0000_______________0000__________00__
_0_________000_____________________000_________00_
_0_______00__________________________000________0_
_00_____00_____________________________00_______0_
__0000000______0000___________0000______00___0000_
______00______000000_________000000______00000____
______00_______0000___________0000_______00_______
______00_____________00000000____________00_______
______00_____________00____00____________00_______
_______0______________000000____________00________
_______00________________00____________000________
________000______________00___________00__________
__________000____________00_________000___________
____________0000_________0_______0000_____________
_______________0000000_000_0000000________________

 


 
