<div align="center">

# Disquetech

Site institucional da Disquetech, empresa fictícia de desenvolvimento criada por alunos da ETEC Basilides de Godoy.

[![Ver site](https://img.shields.io/badge/VER_SITE-0D0D0D?style=for-the-badge&logo=netlify&logoColor=FF003C)](https://disquetech.netlify.app)

![HTML5](https://img.shields.io/badge/HTML5-0D0D0D?style=for-the-badge&logo=html5&logoColor=FF003C)
![CSS](https://img.shields.io/badge/CSS-0D0D0D?style=for-the-badge&logo=css&logoColor=FF003C)

</div>

## Sobre

Site feito em 2023 para um trabalho do técnico em Desenvolvimento de Sistemas da **ETEC Professor Basilides de Godoy**. A Disquetech é uma empresa de software fictícia criada pelo grupo, e o site a apresenta com uma identidade retrô inspirada em pixel art: fontes pixeladas, cursores personalizados e GIFs animados.

O nome Disquetech acompanhou o grupo até o TCC, cuja apresentação virou o site [Windows XP](https://github.com/Lu1sR0/Windows-XP). Planos, depoimentos e a história da empresa são fictícios, criados para o exercício.

> A versão publicada no Netlify tem pequenos ajustes em relação a este repositório, como o slogan e o link direto para a [Retro Garage](https://retrogarage.netlify.app).

## Funcionalidades

- **Hero** com GIF animado de fundo, nome da empresa e botão para a seção "Sobre nós".
- **Sobre nós** contando a história da Disquetech.
- **Tabela de preços** com três planos: Básico, Intermediário e Avançado.
- **Depoimentos** de clientes.
- **Projetos**: card da loja de carros [Retro Garage](https://github.com/Lu1sR0/Retrogarage).
- **Contato**: formulário de e-mail e mensagem (apenas visual, sem envio configurado).
- **Identidade retrô**: fontes Pixel Miners e DP Comic e cursores em pixel art para navegação, clique e campos de texto.
- **Responsivo**: layout ajustado para telas menores e para o modo retrato, com GIF de fundo alternativo.
- Rolagem suave entre as seções.

## Tecnologias

- **HTML5** — estrutura da página única.
- **CSS** — layout, `@font-face` para as fontes pixel, cursores personalizados e media queries (sem JavaScript).
- **Netlify** — hospedagem.

## Estrutura

```
Disquetech/
├── index.html          # página única
├── logodisquetech.png  # logo / favicon
├── assets/
│   ├── css/styles.css  # estilos e media queries
│   └── img/            # imagens, ícones sociais e cursores pixel art
└── libs/fonts/         # fontes pixel (Pixel Miners, DP Comic, Press Start 2P)
```

## Como rodar localmente

```bash
git clone https://github.com/Lu1sR0/Disquetech.git
cd Disquetech
```

Abra o `index.html` no navegador ou use a extensão **Live Server** do VS Code.

## Equipe

Criadores do site e "fundadores" da Disquetech:

- [Luis Roberto](https://github.com/Lu1sR0)
- Sandy Cristina
- Roberto Junior

---

<div align="center">
Desenvolvido por <a href="https://github.com/Lu1sR0">Luis Roberto</a> · <a href="https://outframe.dev">Outframe</a>
</div>
