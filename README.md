# Mundo Disney — Integração com API

## Autor

* **Nome:** Letícia Ribeiro Heidericke
* **Ano:** 2026

## 1. Identificação do projeto

* **Nome do projeto:** Meu Disney
* **Instituição de ensino:** 
* **Unidade curricular:** UC8 - Desenvolver Aplicações Mobile
* **Professor(a):** Rafaela Pessin

---

## 2. Sobre o projeto

> O projeto é uma página chamada Meu Disney que busca personagens da Disney em uma API e mostra cada um em um card com imagem e nome.

## 3. Estrutura do projeto

Apresente a organização dos arquivos e pastas do seu projeto.

**Exemplo:**

```text
mundo-disney/
│
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── img/
│   └── sem-imagem.png
├── fonts/
│   └── waltograph42.otf
└── README.md
```

### Descrição dos arquivos

| Arquivo      | Descrição                                                        |
| ------------ | ---------------------------------------------------------------- |
| `index.html` | É a estrutura principal da página. |
| `style.css`  | Cuida do visual e da responsividade da página. |
| `script.js`  | Faz a conexão com a API e cria os cards. |
| `README.md`  | Contém as informações do projeto. |

> **Caso seu projeto possua outras pastas ou arquivos, apresente-os também na estrutura acima.**

---

## 💻 4. Tecnologias utilizadas

Liste as tecnologias utilizadas no desenvolvimento do projeto.

* HTML5
* CSS3
* JavaScript

---

## 5. API utilizada

### Nome da API

**Disney API**

### Endpoint utilizado

```text
https://api.disneyapi.dev/character
```

### Para que a API foi utilizada?

> A API foi usada para buscar os personagens da Disney e mostrar as informações deles na página.

### Quais informações foram consumidas?

> Foram usados principalmente o nome, a imagem e os dados de paginação dos personagens.

---

##  6. Como executar o projeto

Explique passo a passo como outra pessoa pode executar seu projeto em outra máquina.

### Pré-requisitos

Informe se é necessário instalar algum programa ou ferramenta para executar o seu projeto em outr máquina

### Passo a passo

* Passo 1: Baixe os arquivos do projeto.
* Passo 2: Mantenha as pastas e arquivos organizados.
* Passo 3: Abra o `index.html` no navegador.

---

## 7. Como funciona a integração

Explique de forma objetiva e em até 10 passos como sua aplicação se comunica com a API.

1. O JavaScript define o endereço da API.
2. A URL é montada com a página atual e 50 personagens.
3. O `fetch()` faz a requisição para a API.
4. A resposta é transformada em JSON.
5. Os personagens são acessados no resultado.
6. O código percorre os personagens.
7. Um card é criado para cada personagem.
8. O nome e a imagem são colocados no card.
9. O botão carrega a próxima página sem apagar os anteriores.
10. O contador e a página são atualizados.

## 8. Desafios encontrados

Registre pelo menos um problema ou dificuldade que você encontrou durante o desenvolvimento e como resolveu

### Desafios encontrados

**Problema:**

> 1. Os personagens da API não apareciam ma página
> 2.

**Como identifiquei o problema:**

> 1. Percebi quando executei o código
> 2.

**Como resolvi:**

> 1. Revisei o código e corrigi a parte dos cards no HTML
> 2.

---

## 9. Aprendizados

> Aprendi a usar `fetch()`, criar cards com JavaScript e fazer uma página responsiva. Também aprendi um pouco mais sobre como organizar os arquivos do projeto.

---
