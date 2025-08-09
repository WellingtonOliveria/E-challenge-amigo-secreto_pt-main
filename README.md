
# 🎁 Jogo do Amigo Secreto

Este é um simples programa de **Amigo Secreto**, desenvolvido como parte de um projeto proposto no curso de desenvolvedor juntamente com a **Alura + One Oracle**.  
O sistema permite a inserção anônima de participantes e realiza o sorteio aleatório entre eles, garantindo que ninguém tire a si mesmo.

---

## 📌 Funcionalidades
- ✅ Inserção anônima dos participantes
- ✅ Armazenamento de nomes em uma lista
- ✅ Sorteio aleatório dos pares de amigo secreto
- ✅ Garante que uma pessoa não tire ela mesma
- ✅ Interface simples em HTML, CSS e JavaScript

---

## 💻 Tecnologias utilizadas
- ✅ HTML5
- ✅ CSS3
- ✅ JavaScript
- ✅ VSCode (como ambiente de desenvolvimento)

---

## 🚀 Como usar
1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` no navegador.
3. Insira os nomes dos participantes (um por vez).
4. Após adicionar todos, clique em **“Sortear”**.
5. Veja os pares de amigo secreto (modo privado ou público, dependendo da versão do programa).

---

## 📂 Estrutura dos arquivos
```bash
📁 amigo-secreto/
├── index.html       # Página principal
├── style.css        # Estilos do layout
└── script.js        # Lógica do jogo (inserção e sorteio)
📝 Exemplo de uso
javascript
Copiar
Editar
// Inserindo um participante
adicionarParticipante("João");

// Sorteando os pares
sortearAmigoSecreto();
### ⚠️ Regras do sorteio
    Cada participante só pode tirar uma pessoa.

    Nenhum participante pode tirar a si mesmo.

    O sorteio é aleatório a cada execução.

### 👨‍🏫 Projeto escolar
    Este projeto foi desenvolvido com fins educacionais juntamente com a Alura+One Oracle para praticar lógica de programação numa interação entre HTML e JavaScript.