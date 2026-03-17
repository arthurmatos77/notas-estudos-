# notas-estudos-
minhas notas senac tec 
markdawn 

## Configurando git 


Para utilizar o git na minha maquina eu preciso configurar deterrminado comandos,sendo eles 

```bash
git config global 
```

## configurando o git hub 
 coloquei informações sobre o git para salvar e subir no site tive pequanas difulcades.

 ### OQUE É GIT ?
  ferramenta para atividades on line , que salva o estado de cada arquivo na hora e caso o arquivo não sofra a alterações  ele cria um link simbólico para o arquivo não editado


exemplos para consulta na prova 
   // function
// getElementById 
// addEventlistners


// ----------- Questão 1 ------------//
function questao1 ()  {
// escrever o enunciado aqui
// some os 2 numeros
const numero = Number(prompt("DIGITE UM NÚMERO:"))
const numero2 = Number(prompt("DIGITE OUTRO NÚMERO:"))
alert(numero+numero2)
}

const buttonquestao1 = document.getElementById("questao1")
buttonquestao1.addEventListener('click' , () => { questao1() })

como criar um repositorio 

primeiro passo ir no git repositorios 

aperta na tecla verde escrita 'new repositores'
apos criar vai ser encamnhado para outra aba 
apos isso coloque a opçao ssh para nao dar erro 
depois abra o git bash e coloque cd document/
depois coloque git clone e o nome do repositorio 
com botão direito clique e aperte em paste 
e escreva cd " nome do repositorio" se aparecer main esta certo 
entre no vs code 
clique ctrl k o 
depois pesquise o repositorio 
quando achar abra ele clicando apenas uma vez para abrir no seu vs code 
depois coloque index.html e script para fazer as questões 
depois coloque ponto de !

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2>Avaliação </h2>

    <button id="questao1" >Questão 1</button>
    <button id="questao2" >Questão 2</button>

    <script src="./scripts/avaliacao.js"></script>
</body>
</html>


