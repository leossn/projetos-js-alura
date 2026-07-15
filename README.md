# Meus Projetos de Lógica com JavaScript

Este repositório reúne os projetos práticos desenvolvidos para consolidar fundamentos de programação, manipulação do DOM e lógica aplicada.

> Nota de Autoria: Os layouts visuais, marcações HTML e estilizações CSS foram disponibilizados previamente pela plataforma Alura. Toda a lógica de funcionamento, interações e manipulação dinâmica em JavaScript foram desenvolvidas por mim.

---

## Languages e Tools 💻

<p align="left">
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

## Visão Geral dos Projetos

### 1. Jogo de Número Secreto (`/jogo de numero secreto`)
Jogo interativo onde o usuário tenta adivinhar um número secreto gerado aleatoriamente.
* Implementação do controle de tentativas, geração de números aleatórios sem repetição imediata e integração de voz para acessibilidade.

### 2. Sorteador de Números (`/sorteador-numeros`)
Ferramenta para realizar sorteios definindo um intervalo numérico personalizado.
* Lógica matemática de intervalo dinâmico, validações para evitar loops infinitos e controle de números já sorteados para impedir repetições.

### 3. AluGames (`/alugames`)
Página de locação e controle de devolução de jogos de tabuleiro.
* Refatoração para melhorar a performance. Aplicação de uma única função dinâmica com interpolação de strings para tratar múltiplos botões e jogos, reduzindo linhas de código repetitivas (conceito DRY / Clean Code).

### 4. Carrinho de Compras (`/carrinho-compras`)
Fluxo de e-commerce simples para somar produtos ao carrinho e calcular o valor final da compra.
* Tratamento de strings com .split() para extrair o valor financeiro do texto, manipulação do DOM para inserção de novos elementos na lista e cálculos de soma cumulativa.

### 5. Ingresso Online (`/ingresso`)
Painel de compra de ingressos para shows com controle de estoque integrado por setor (Pista, Cadeira Superior e Cadeira Inferior).
* Lógica de decréscimo de estoque em tempo real usando interpolação para buscar os IDs dos elementos HTML e travas de segurança para compras maiores que o estoque restante.

### 6. Amigo Secreto (`/amigo-secreto`)
Aplicação para cadastrar nomes e realizar o sorteio de amigo secreto de forma circular.
* Algoritmo de embaralhamento de arrays e laço de repetição com condicional para ligar o último sorteado de volta ao primeiro da lista, garantindo um ciclo completo de sorteio.