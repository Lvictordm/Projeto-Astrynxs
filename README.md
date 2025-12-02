📘 README – Efeito de Barra Animada (Preto → Branco)

Este projeto demonstra um layout moderno para uma home page, utilizando HTML e CSS, com foco em uma barra superior (navbar) que possui um efeito de transição animada, indo de preto → branco, deslizando suavemente para a direita.

🎨 Destaques do Projeto

🔹 Layout escuro elegante

🔹 Barra de navegação com gradiente animado

🔹 Efeito moderno usando apenas CSS puro

🔹 Design responsivo e limpo

🔹 Não utiliza bibliotecas externas

🧩 Estrutura do Projeto
/
├── index.html
└── style.css

📄 index.html

Arquivo responsável pela estrutura do conteúdo da página (HTML).

Contém:

Cabeçalho (navbar)

Área principal (hero)

Botões, título e imagem

🎨 style.css

Arquivo que define todo o estilo da página, como cores, fontes e animações.

Inclui o efeito animado da barra usando:

background: linear-gradient(90deg, #000000, #2a2a2a, #7a7a7a, #ffffff);
background-size: 300% 100%;
animation: moverBarra 6s linear infinite;


E a animação:

@keyframes moverBarra {
    0% {
        background-position: 0% 0%;
    }
    100% {
        background-position: 100% 0%;
    }
}

🚀 Como executar

Basta abrir o arquivo index.html em qualquer navegador:

Clique duas vezes no index.html

A página irá carregar com o efeito funcionando

Não é necessário instalar nada

🛠 Tecnologias Utilizadas

HTML5

CSS3

Animações CSS (keyframes)

📌 Observações

O efeito animado aparece apenas na barra superior (header).

Nenhum outro elemento da página foi alterado.

Código leve, rápido e compatível com todos os navegadores modernos.

📷 Exemplo do Efeito

✨ A barra vai de preto → branco deslizando continuamente da esquerda para a direita.
