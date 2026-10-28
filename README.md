# ❤️ manu-first-project

**O primeiro site da Manu.** Uma página em HTML e CSS com um coração que bate. Feita para aprender o básico do desenvolvimento web de um jeito leve e divertido.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Nível](https://img.shields.io/badge/n%C3%ADvel-iniciante-0058ff?style=flat-square)

[O que aprendemos](#-o-que-aprendemos) · [Tecnologias](#-tecnologias-utilizadas) · [Como executar](#%EF%B8%8F-como-executar-o-projeto) · [Estrutura](#-estrutura-do-projeto) · [Créditos](#-créditos-do-projeto)

---

## Em resumo

| | |
| --- | --- |
| **O que é** | Página estática com um coração vermelho pulsando e a palavra *Amor* |
| **Para quem** | Quem está começando a programar agora |
| **Tempo para rodar** | Menos de 1 minuto |
| **Arquivos** | 3, um HTML, um CSS e uma imagem |

---

## 🧠 O que aprendemos

O projeto é pequeno, mas cobre as três camadas de uma página web.

### 1. Estrutura · HTML

O HTML diz **o que** aparece na tela.

| Conceito | No código | Para que serve |
| --- | --- | --- |
| Esqueleto da página | `<html>` `<head>` `<body>` | Organiza o documento em cabeça (configurações) e corpo (conteúdo) |
| Responsividade | `<meta name="viewport">` | Faz a página se ajustar bem no celular |
| Conteúdo principal | `<main>` | Indica a parte mais importante da página |
| Imagem | `<img src="..." alt="...">` | Mostra o coração. O `alt` descreve a imagem para quem usa leitor de tela |
| Texto | `<p>` | Mostra a palavra *Amor* |

### 2. Estilo · CSS

O CSS diz **como** as coisas aparecem.

| Conceito | No código | Resultado |
| --- | --- | --- |
| Cor de fundo | `background-color: #0058ff` | Fundo azul |
| Cor do texto | `color: #fff` | Texto branco |
| Alinhamento | `text-align: center` | Conteúdo no meio da tela |
| Espaçamento | `margin: 100px 0` | Respiro em cima e embaixo |
| Fonte externa | `font-family: "Tangerine"` | Letra cursiva vinda do Google Fonts |
| Tamanho | `width` / `height` / `font-size` | Coração de 300px e texto de 80px |

### 3. Movimento · Animação CSS

A parte mais legal: o coração **bate**. 💓

```css
img {
    animation: pulse 1s infinite; /* nome · duração · repetição */
}

@keyframes pulse {
    0%   { transform: scale(1);   } /* normal  */
    25%  { transform: scale(1.1); } /* cresce  */
    50%  { transform: scale(1);   } /* normal  */
    75%  { transform: scale(1.1); } /* cresce  */
    100% { transform: scale(1);   } /* normal  */
}
```

<details>
<summary><strong>Como isso funciona?</strong> (clique para abrir)</summary>

<br>

- `@keyframes` cria uma animação e dá um nome para ela, aqui `pulse`.
- As porcentagens são **momentos** da animação. `0%` é o começo e `100%` é o fim.
- `transform: scale(1.1)` deixa o coração **10% maior**. `scale(1)` volta ao tamanho original.
- `1s infinite` faz a animação durar 1 segundo e repetir para sempre.

Como o coração cresce **duas vezes** em cada segundo, o movimento lembra o *tum-tum* de um coração de verdade.

</details>

---

## 🛠 Tecnologias utilizadas

| Tecnologia | Para que serve |
| --- | --- |
| **HTML** | Estrutura da página |
| **CSS** | Cores, tamanhos, fonte e animação |
| **Google Fonts** | Fonte cursiva Tangerine |

---

## ⚙️ Como executar o projeto

### 1️⃣ Baixar os arquivos

Clique em **Code → Download ZIP** aqui no GitHub, ou use o terminal:

```bash
git clone https://github.com/lunajulia107/manu-first-project.git
```

### 2️⃣ Abrir no navegador

Dê dois cliques no arquivo `index.html`. Pronto! 🎉

> [!TIP]
> Usando o VS Code? Instale a extensão **Live Server**. A página recarrega sozinha toda vez que você salvar um arquivo.

---

## 📁 Estrutura do projeto

```
manu-first-project/
├── index.html        → a estrutura (o que aparece)
├── style.css         → o estilo (como aparece)
└── coracao-gif.png   → a imagem do coração
```

---

## 🤝 Créditos do projeto

Feito com carinho, em dupla. 💙

| Papel | Responsável |
| --- | --- |
| 👧 Aluna | Manuela Luna |
| 👩‍💻 Prima professora | Julia Gomes |

Dúvidas ou sugestões: [rodriguesjuliaw23@gmail.com](mailto:rodriguesjuliaw23@gmail.com)
