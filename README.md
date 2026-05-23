# 💣 Campo Minado (Minesweeper)

Um jogo clássico de **Campo Minado (Minesweeper)** desenvolvido com **HTML, CSS e JavaScript puro (Vanilla JS)**, executado diretamente no navegador sem dependência de bibliotecas, frameworks ou tecnologias externas.

Este projeto foi desenvolvido durante o curso **“Inteligências Artificiais Generativas Aplicada à Programação – ChatGPT”**, realizado pelo **SENAI**, com foco no uso de inteligência artificial como apoio ao desenvolvimento de software.

---

## 📌 Sobre o projeto

O objetivo deste projeto foi desenvolver uma versão funcional do clássico **Campo Minado**, implementando sua lógica principal utilizando apenas tecnologias nativas do navegador.

O jogo foi criado em um **arquivo único `.html`**, contendo:

- **HTML** → estrutura da interface;
- **CSS** → estilização e responsividade;
- **JavaScript** → lógica do jogo e interações.

A proposta foi construir uma aplicação simples, funcional e organizada, reforçando conceitos de:

- Manipulação do DOM;
- Eventos do JavaScript;
- Estruturas condicionais;
- Matrizes e lógica bidimensional;
- Algoritmos de expansão de células;
- Responsividade;
- Organização de código front-end.

---

## 🎮 Funcionalidades implementadas

O jogo possui as seguintes funcionalidades:

✅ Tabuleiro no modo **fácil (9x9)**  
✅ **10 minas** distribuídas aleatoriamente  
✅ Clique esquerdo para revelar células  
✅ Clique direito para adicionar/remover **bandeiras 🚩**  
✅ Sistema de números indicando minas adjacentes  
✅ Expansão automática de áreas vazias  
✅ Primeira jogada segura (**não explode no primeiro clique**)  
✅ Sistema de vitória e derrota  
✅ Cronômetro de partida ⏱️  
✅ Contador de bandeiras restantes 🚩  
✅ Botão de reiniciar partida  
✅ Interface responsiva para desktop e mobile  
✅ Visual moderno com animações simples

---

## 🛠️ Tecnologias utilizadas

O projeto foi desenvolvido utilizando apenas tecnologias nativas do navegador:

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla JS)**

Não foram utilizadas bibliotecas ou frameworks externos.

---

## 📂 Estrutura do projeto

Como o projeto foi desenvolvido em um único arquivo, sua estrutura é simples:

```bash
campo-minado/
│── index.html
│── README.md
```

O arquivo `index.html` contém toda a aplicação:

- Estrutura da interface;
- Estilos do jogo;
- Lógica do Campo Minado.

---

## ▶️ Como executar o projeto

Você pode executar o projeto de duas formas:

### 1. Abrindo diretamente no navegador

Basta baixar o arquivo `index.html` e abrir no navegador:

1. Faça o download do projeto;
2. Localize o arquivo `index.html`;
3. Clique duas vezes no arquivo.

O jogo será iniciado automaticamente.

---

### 2. Executando localmente com VS Code (recomendado)

Para melhor experiência de desenvolvimento:

#### Passo 1 — Clone o repositório

```bash
git clone https://github.com/annaagabi/campo-minado.git
```

#### Passo 2 — Entre na pasta do projeto

```bash
cd campo-minado
```

#### Passo 3 — Abra no VS Code

```bash
code .
```

#### Passo 4 — Execute com Live Server

Caso tenha a extensão **Live Server** instalada no VS Code:

1. Clique com o botão direito no arquivo `index.html`;
2. Clique em **"Open with Live Server"**.

---

## 📥 Como baixar o projeto pelo GitHub

### Opção 1 — Download ZIP

1. Acesse o repositório no GitHub;
2. Clique no botão verde **Code**;
3. Clique em **Download ZIP**;
4. Extraia os arquivos;
5. Abra o `index.html`.

---

### Opção 2 — Clonando com Git

Caso tenha Git instalado:

```bash
git clone https://github.com/annaagabi/campo-minado.git
```

Depois:

```bash
cd campo-minado
```

Abra o arquivo `index.html`.

---

## 🎯 Como jogar

### Objetivo

O objetivo do jogo é revelar todas as casas seguras do tabuleiro sem clicar em uma mina.

---

### Controles

#### Clique esquerdo do mouse

Revela uma célula.

#### Clique direito do mouse

Adiciona ou remove uma bandeira 🚩.

Use bandeiras para marcar possíveis minas.

---

### Sistema de números

Quando uma célula é aberta, ela pode mostrar um número.

Esse número representa **quantas minas existem ao redor daquela célula**.

Exemplo:

- `1` → existe 1 mina adjacente
- `2` → existem 2 minas adjacentes
- `3` → existem 3 minas adjacentes

---

### Vitória

Você vence quando todas as células seguras forem reveladas.

---

### Derrota

Você perde ao clicar em uma mina 💣.

---

## 🧠 Conceitos aplicados

Durante o desenvolvimento do projeto foram aplicados diversos conceitos de programação front-end:

### Manipulação do DOM

Criação dinâmica do tabuleiro e atualização dos elementos HTML.

### Eventos JavaScript

Uso de:

- `click`
- `contextmenu`

Para controlar interações do usuário.

### Matrizes bidimensionais

O tabuleiro foi estruturado utilizando arrays bidimensionais.

### Recursividade

A expansão automática das áreas vazias utiliza um algoritmo recursivo.

### Responsividade

O layout foi adaptado para diferentes tamanhos de tela.

---

## 🚀 Possíveis melhorias futuras

O projeto pode ser expandido com novas funcionalidades, como:

- [ ] Adicionar níveis:
  - Fácil
  - Médio
  - Difícil
- [ ] Sistema de recordes
- [ ] Ranking de tempo
- [ ] Tema escuro/claro
- [ ] Sons do jogo
- [ ] Efeitos visuais mais elaborados
- [ ] Animações avançadas
- [ ] Suporte completo para mobile touch
- [ ] Sistema de pause
- [ ] Salvamento de progresso

---

## 🤝 Como contribuir

Contribuições são muito bem-vindas!

Caso queira melhorar o projeto:

### 1. Faça um fork

Clique em **Fork** no GitHub.

---

### 2. Clone o repositório

```bash
git clone https://github.com/annaagabi/campo-minado.git
```

---

### 3. Crie uma branch

```bash
git checkout -b minha-melhoria
```

---

### 4. Faça suas alterações

Implemente melhorias e testes.

---

### 5. Faça commit

```bash
git commit -m "feat: adiciona nova funcionalidade"
```

---

### 6. Envie para o GitHub

```bash
git push origin minha-melhoria
```

---

### 7. Abra um Pull Request

Explique sua melhoria e envie um Pull Request 🚀

---

## 📖 Aprendizados do projeto

Este projeto permitiu aprofundar conhecimentos em:

- Lógica de programação;
- JavaScript puro;
- Estruturação de jogos no navegador;
- Organização de código front-end;
- Manipulação dinâmica da interface;
- Uso de IA generativa no apoio ao desenvolvimento.

Também foi uma oportunidade de explorar o uso do **ChatGPT como ferramenta auxiliar no processo de desenvolvimento**, desde a estruturação da lógica até refinamentos da interface.

---

## 👩‍💻 Desenvolvido por

**Anna Gabriela**

Desenvolvido durante o curso:

**Inteligências Artificiais Generativas Aplicada à Programação – ChatGPT**  
**SENAI**

---

## 📄 Licença

Este projeto está sob a licença **MIT**.

Sinta-se livre para estudar, modificar e utilizar o código.
