# notas-estudos-
minhas notas senac tec 
markdawn 

## Configurando git 


ormatação 👇

# 📘 Guia Básico de Git e JavaScript

## 🔧 Configurando o Git

Para utilizar o Git na sua máquina, é necessário configurar:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@email.com"
🌐 Configurando o GitHub

Ao configurar o GitHub para salvar e subir arquivos, podem surgir pequenas dificuldades no início.

❓ O que é Git?

O Git é uma ferramenta de controle de versão que:

Salva o estado dos arquivos

Registra alterações no código

Permite voltar para versões anteriores

Se o arquivo não for alterado, o Git não duplica ele, apenas cria uma referência.

💡 Exemplos importantes (prova)
// Funções importantes
// getElementById
// addEventListener
🧪 Exemplo prático
// ----------- Questão 1 ------------//
function questao1() {
  // Somar dois números
  const numero = Number(prompt("DIGITE UM NÚMERO:"))
  const numero2 = Number(prompt("DIGITE OUTRO NÚMERO:"))
  alert(numero + numero2)
}

const buttonquestao1 = document.getElementById("questao1")

buttonquestao1.addEventListener('click', () => {
  questao1()
})
📁 Como criar um repositório

Acesse o GitHub

Vá em repositórios

Clique em New repository

Após criar, você será redirecionado

Escolha a opção SSH

💻 Clonando o repositório

Abra o Git Bash:

cd Documents/
git clone <link-do-repositorio>
cd nome-do-repositorio

Se aparecer a branch main, está correto.

🧑‍💻 Abrindo no VS Code

Abra o VS Code

Pressione Ctrl + K + Ctrl + O

Procure o repositório

Clique para abrir

📝 Criando arquivos

Criar index.html

Criar script.js

Digitar ! + Enter no HTML para gerar estrutura básica


---

✅ Agora pode copiar direto — vai ficar certinho no VS Code  
Se quiser, posso te mandar versão **mais resumida pra prova** ou **com cores 

forma 2 de criar repositorio 
primeiro entre no git , repositorio copiar a chave ssh 
criar pasta
botao direito na pasta 
clicar em mostrar mais
selecionar OPEN GITBASH HERE
dá git clone <link do repositorio> 

// ===============================
// 01 - Soma de dois números
// ===============================
{
  const n1 = Number(prompt("Número 1:"))
  const n2 = Number(prompt("Número 2:"))
  alert("Soma: " + (n1 + n2))
}

// ===============================
// 02 - Salário mensal
// ===============================
{
  const valorHora = Number(prompt("Valor por hora:"))
  const horas = Number(prompt("Horas trabalhadas:"))
  alert("Salário: " + (valorHora * horas))
}

// ===============================
// 03 - Média de 5 pesos
// ===============================
{
  const p1 = Number(prompt("Peso 1:"))
  const p2 = Number(prompt("Peso 2:"))
  const p3 = Number(prompt("Peso 3:"))
  const p4 = Number(prompt("Peso 4:"))
  const p5 = Number(prompt("Peso 5:"))

  const media = (p1 + p2 + p3 + p4 + p5) / 5
  alert("Média: " + media)
}

// ===============================
// 04 - Celsius → Fahrenheit
// ===============================
{
  const c = Number(prompt("Celsius:"))
  const f = c * 1.8 + 32
  alert("Fahrenheit: " + f)
}

// ===============================
// 05 - Milhas → Km
// ===============================
{
  const milhas = Number(prompt("Milhas:"))
  const km = milhas * 1.60934
  alert("Km: " + km)
}

// ===============================
// 06 - Segundos → h:m:s
// ===============================
{
  const total = Number(prompt("Segundos:"))

  const h = parseInt(total / 3600)
  const resto = total % 3600
  const m = parseInt(resto / 60)
  const s = resto % 60

  alert(h + "h " + m + "m " + s + "s")
}

// ===============================
// 07 - Km → m e cm
// ===============================
{
  const km = Number(prompt("Km:"))
  const m = km * 1000
  const cm = km * 100000

  alert(m + " m e " + cm + " cm")
}

// ===============================
// 08 - Tabuada
// ===============================
{
  const n = Number(prompt("Número:"))
  let resultado = ""

  for (let i = 0; i <= 10; i++) {
    resultado += n + " x " + i + " = " + (n * i) + "\n"
  }

  alert(resultado)
}

// ===============================
// 09 - Peso ideal
// ===============================
{
  const sexo = prompt("Sexo (H/M):").toUpperCase()
  const altura = Number(prompt("Altura:"))

  if (sexo === "H") {
    alert("Peso ideal: " + (72.7 * altura - 58))
  } else if (sexo === "M") {
    alert("Peso ideal: " + (62.1 * altura - 44.7))
  } else {
    alert("Valor inválido")
  }
}

// ===============================
// 10 - Par ou ímpar
// ===============================
{
  const num = Number(prompt("Número:"))

  if (num % 2 === 0) {
    alert("Par")
  } else {
    alert("Ímpar")
  }
}

# 📘 Notas - Estudos

# ===============================
# 01 - Configurando Ambiente
# ===============================

## CMD (Windows)

```bash
git config --global user.name "nome"
git config --global user.email "email"

SSH (Git Bash)
Gerar nova chave SSH

ssh-keygen -t ed25519 -C "email"

Iniciar agente SSH

eval "$(ssh-agent -s)"

Adicionar chave ao agente

ssh-add ~/.ssh/id_ed25519

Copiar chave pública

👉 Colar em: GitHub → Settings → SSH and GPG keys

Testar conexão

ssh -T git@github.com

02 - Comandos Básicos
Clonar repositório

git clone <link-do-repositorio>

Atualizar repositório

git pull

Linkar CSS
<link type="text/css" rel="stylesheet" href="./css/tema.css">

Linkar JavaScript
<script src="./script.js"></script>

03 - Fórmulas
===============================
Porcentagem
valor * (1 + porcentagem / 100)
===============================
04 - DOM
===============================
Função + botão
function exercicio1() {

}

const buttonexercicio1 = document.getElementById("exercicio1")

buttonexercicio1.addEventListener("click", () => {
  exercicio1()
})
Botão no HTML
<button id="exercicio1">Executar Exercício 1</button>

//// function // getElementById // addEventlistners

function questao1() { 


}
const buttonquestao1 = document.getElementById("questao1") 
buttonquestao1.addEventListener('click', () => { questao1() })



function questao2() { 


}
const buttonquestao2 = document.getElementById("questao2") 
buttonquestao2.addEventListener('click', () => { questao2() })

function questao3() { 


}
const buttonquestao3 = document.getElementById("questao3") 
buttonquestao3.addEventListener('click', () => { questao3() })

function questao4() { 


}
const buttonquestao4 = document.getElementById("questao4") 
buttonquestao4.addEventListener('click', () => { questao4() })

function questao5() { 


}
const buttonquestao5 = document.getElementById("questao5") 
buttonquestao5.addEventListener('click', () => { questao5() })



