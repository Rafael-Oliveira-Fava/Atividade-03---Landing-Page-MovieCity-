# 🎬 MovieCity - Landing Page de Filmes

O **MovieCity** é uma aplicação web desenvolvida em React para apresentação de um catálogo de filmes. O projeto conta com um layout responsivo, menu de navegação dinâmico e uma interface moderna para exibição de destaque de filmes.

---

## 🚀 Tecnologias Utilizadas

- **React** (Biblioteca JavaScript para construção de interfaces)
- **JavaScript (ES6+)**
- **CSS3** (Estilização e responsividade)
- **HTML5**

---

## 📁 Estrutura do Projeto

```text
src/
├── components/
│   ├── Header.jsx   # Cabeçalho com logo, navegação e controle de menu mobile
│   ├── Home.jsx     # Página principal que organiza o Header e o Main
│   └── Main.jsx     # Seção principal com textos e grid de cards de filmes
├── App.jsx          # Componente raiz da aplicação
├── index.css        # Estilos globais da aplicação
└── index.js / main.jsx
```

---

## 🧩 Componentes

### 1. `App.jsx`
Componente principal que serve como ponto de entrada da aplicação, renderizando o componente `Home`.

### 2. `Home.jsx`
Estrutura a página inicial unindo o cabeçalho (`Header`) e a área principal de conteúdo (`Main`).

### 3. `Header.jsx`
- Exibe o logotipo da marca **MovieCity**.
- Menu de navegação com links para: *Filmes*, *Categoria*, *Sobre* e *Contato*.
- Botão de **Login**.
- Suporte a menu hambúrguer para dispositivos móveis com estado reativo (`useState`).

### 4. `Main.jsx`
- **Coluna Institucional / Chamada:** Apresenta um título, descrição curta e um botão "Mais" para explorar o catálogo.
- **Coluna de Cards:** Grid exibindo os cards dos filmes em destaque.

---

## 🔧 Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter o **Node.js** e o **npm** (ou **yarn**) instalados em sua máquina.

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/moviecity.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd moviecity
   ```

3. **Instale as dependências:**
   ```bash
   npm install
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   # ou npm start (dependendo do bundler utilizado, como Vite ou CRA)
   ```

5. **Acesse no navegador:**
   Abra [http://localhost:5173](http://localhost:5173) ou a URL indicada no seu terminal.
