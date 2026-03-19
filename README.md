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