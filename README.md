## 📸 Screenshots  

### Cadastro de Livro
![Cadastro de Livro](https://i.postimg.cc/hv7Xkg6N/cadastrar-livro.png)

### Operações
![Operações](https://i.postimg.cc/dQ7nsCYc/operacoes.png)

### Biblioteca
![Biblioteca](https://i.postimg.cc/ThMKGFX1/biblioteca.png)

### Relatório
![Relatório](https://i.postimg.cc/zBvbkTjz/relatorio.png)

# 📚 BibliotecaJS  

Um sistema simples de **gerenciamento de biblioteca** feito em **JavaScript puro**, utilizando arquivos `.js` modulares e um `index.html` para interface.  

Permite **cadastrar, listar, excluir e gerar relatórios de livros**, armazenando os dados em um arquivo JSON.  

---

## 🚀 Funcionalidades  

- **Cadastrar Livros** → adiciona novos livros ao acervo.  
- **Listar Livros** → mostra todos os livros registrados.  
- **Excluir Livros** → remove livros pelo identificador.  
- **Gerar Relatório** → cria um resumo dos livros cadastrados.  
- **Calcular Total** → número total de livros cadastrados.  
- **Armazenamento** → gerencia os dados no `biblioteca.json`.  

---

## 📂 Estrutura do Projeto  

```
BibliotecaJS/
├── biblioteca.json          # Base de dados dos livros
├── main.js                  # Arquivo principal que integra as funções
├── funcoes/                 # Módulos de funções da biblioteca
│   ├── armazenamento.js
│   ├── cadastrarLivros.js
│   ├── calcularTotal.js
│   ├── excluirLivros.js
│   ├── gerarRelatorio.js
│   └── listarLivros.js
└── html/
    └── index.html           # Interface básica para rodar no navegador
```

---

## ⚙️ Como Rodar  

### 🔹 Opção 1 — Navegador  
1. Abra a pasta `BibliotecaJS/html/`.  
2. Clique duas vezes em `index.html`.  
3. O sistema irá carregar no navegador.  

### 🔹 Opção 2 — Node.js  
1. Instale o [Node.js](https://nodejs.org).  
2. No terminal, navegue até a pasta do projeto:  
   ```bash
   cd BibliotecaJS
   ```
3. Execute o arquivo principal:  
   ```bash
   node main.js
   ```
---

