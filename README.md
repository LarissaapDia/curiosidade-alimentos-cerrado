# 🌱 Alimentos do Cerrado e Saúde do Coração

Este projeto é uma página simples criada com **HTML e CSS** para divulgar a importância dos frutos do Cerrado para a saúde do coração.  
O site foi publicado usando **GitHub Pages**.

👉 Acesse o site aqui: 

---

## Estrutura do Projeto

- **index.html** → arquivo principal do site, contém todo o conteúdo e estrutura da página.
- **assets/images/** → pasta que armazena as imagens usadas no site (frutas e cabeçalho).
- **README.md** → este documento, que explica o projeto.

---

## Explicando o código (`index.html`)

### 1. Estrutura básica
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alimentos do Cerrado</title>
  <style>
    <!-- Aqui ficam os estilos CSS -->
  </style>
</head>
<body>
  <!-- Aqui fica o conteúdo da página -->
</body>
</html>
<!-- ===== Cabeçalho ===== -->
<header>
  <h1>Alimentos do Cerrado que fazem bem ao coração</h1>
  <p>A importância da alimentação para a saúde cardiovascular</p>
</header>
<!-- ===== Conteúdo Principal ===== -->
<main>
  <h2>Frutas e seus benefícios</h2>
  <div class="grid">
    <!-- Aqui entram os cards das frutas -->
  </div>
</main>
<!-- ===== Card Pequi ===== -->
<div class="card">
  <img src="assets/images/pequi.jpg" alt="Pequi">
  <div class="card-content">
    <h3>Pequi</h3>
    <p>Rico em antioxidantes e gorduras boas. Protege os vasos sanguíneos.</p>
  </div>
</div>
<!-- ===== Rodapé ===== -->
<footer>
  <p>🌱 Projeto de conscientização - Alimentação saudável e coração forte</p>
</footer>
/* ===== Grid de Cards ===== */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

/* ===== Efeito no Card ===== */
.card {
  background: white;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  transition: transform 0.2s;
}

.card:hover {
  transform: scale(1.05); /* aumenta um pouco no hover */
}

