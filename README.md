# Batalha Naval em C

Este repositório apresenta um projeto prático de programação em linguagem C baseado no clássico jogo **Batalha Naval**, com o objetivo de aplicar e consolidar conhecimentos sobre vetores, matrizes, estruturas de repetição e condicionais.

O projeto é dividido em três níveis de dificuldade:

* **Novato**: posicionamento de navios horizontal e vertical.
* **Aventureiro**: inclusão de navios diagonais.
* **Mestre**: adição de habilidades especiais com áreas de efeito.

---

## 🎯 Objetivos

* Modelar um tabuleiro de batalha naval com matrizes.
* Posicionar navios de forma segura (sem sobreposição e dentro dos limites).
* Implementar habilidades especiais com formatos distintos (cone, cruz, octaedro).
* Utilizar loops aninhados e condicionais para manipular dados.

---

## 📚 Estrutura do Projeto

```bash
batalha-naval/
├── novato.c         # Código do nível novato
├── aventureiro.c    # Código do nível aventureiro
├── mestre.c         # Código do nível mestre
└── README.md        # Este arquivo
```

---

## 🧩 Níveis de Desafio

### 🟢 Nível Novato

* Tabuleiro 10x10 preenchido com 0 (água).
* Dois navios com 3 posições:

  * Um na horizontal.
  * Um na vertical.
* Representação dos navios: valor `3`.
* Impressão organizada do tabuleiro com loops aninhados.

### 🟡 Nível Aventureiro

* Manutenção do tabuleiro 10x10.
* Quatro navios:

  * Dois em linha/coluna.
  * Dois em diagonais (`[i][i]`, `[i][9-i]`).
* Validação de limites e sobreposição.
* Saída visual clara com `0` (água) e `3` (navio).

### 🔴 Nível Mestre

* Matrizes de habilidades especiais:

  * Cone (expansão para baixo).
  * Cruz (horizontal e vertical centrada).
  * Octaedro (formato de losango).
* Posições afetadas: valor `5`.
* Sobreposição no tabuleiro considerando origem da habilidade.
* Exibição do tabuleiro com água (`0`), navios (`3`) e áreas afetadas (`5`).

---

## ⚙️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/batalha-naval.git
cd batalha-naval
```

2. Compile e execute o nível desejado:

```bash
gcc novato.c -o novato && ./novato
gcc aventureiro.c -o aventureiro && ./aventureiro
gcc mestre.c -o mestre && ./mestre
```

---

## ✅ Requisitos Atendidos

### Funcionais

* Criação e exibição de tabuleiro.
* Posicionamento válido de navios.
* Cálculo e aplicação de habilidades especiais.

### Não Funcionais

* Código legível, comentado e organizado.
* Execução rápida e sem erros.
* Estrutura modular para fácil manutenção.

---
