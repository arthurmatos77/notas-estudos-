html marcaçao

css costumizaçao 

js da a vida , manipulaçao do don 

alert,para mostrar o rsultado 
serve para exibir uma mensagem 
nao recebe reposta 
bloqueia a tela ate o usario confirmar 
ideal para exemplos simples e aprendizado 

detalhe importante!
o cod para e espera o usario

prompt, ele ira nos permitir realizar duas açoes

mostrar uma pergunta
receber uma reposta do usario

detalhe importante!



exemplo disso 

const nota1 = number(prompt("digite a primeira nota"))




prompt + variaveis 
aqui nasce algo poderoso, guardar repostas 
o valor digitado pode ser armazenado 
variaveis passam a ter significado real 
o codigo começa a reagir ao usario

sem variavel , a repostas se perder 

manipulaçao de DOM 

getElementByld 

funçao retorna uma referencia ao elemento pelo seu ID 
Uso principal selecionar elementos unicos em uma pagina para manipulaçao ou leitura de dados.

const element = docment.getElementById('my-elemente');
element.style.color = 'blue;

createElement

const 


click exemplo
disparado 
const button= document.getElementById('my-)




funçoes 

por hora serao utilizads apenas para reaproveitar código 
sao declaradas de seguinte forma 

> function exemplo() {

}
const buttonExercicio3 = document.getElementByid("exercicio3")
buttonExercicio.addEventLister('click',()=>) { exemplo() }


IF ELSE

o if e else são estruturas condicionais que permitem executar diferentes blocos de codigos com base em uma condiçao ou expressao booleana. 




let ocupado = 1 

if(ocupado==1){
     console.log("ocupado"); 
} else { 
    console.log("livre")
}

if else if else 

alem disso , tambem e possivel utilizar multiplas estruturas if  aninhadas para verificar varias condicoes consecutivos, ou usar a estrutura else if para acionar condiçoes intermediarias  


let ocupado = 2 

if(ocupado ==1){
console.log("ocupado");
} else if (ocupado== 2) {
    console.log("reservado");
} else {
    console.log("livre")
}


