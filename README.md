# PIT WALL · GP de São Paulo

Landing page temática inspirada no Grande Prêmio de São Paulo de Fórmula 1, desenvolvida como projeto de estudo utilizando **HTML5** e **CSS3** puros.

## Sobre o projeto

O **PIT WALL** simula uma página oficial de evento para o GP de São Paulo (Interlagos), reunindo informações da pista, destaque de pilotos, tabela de classificação e uma área de reserva de ingressos.

O objetivo principal foi praticar estruturação semântica, estilização moderna com variáveis CSS, layouts responsivos e design de interfaces esportivas.

## Seções da página

- **Topo (Navbar):** Navegação rápida entre as seções e botão de chamada para ação (*Comprar ingresso*).
- **Hero & Dados da Pista:** Destaque principal do evento com informações técnicas do Autódromo de Interlagos (71 voltas, 4.309 km e 15 curvas) e estilização inspirada nas zebras da pista.
- **01 · Grid de Pilotos:** Cards individuais para pilotos do grid (Charles Leclerc, Oscar Piastri, George Russell e Gabriel Bortoleto) identificados pelas cores de suas respectivas equipes.
- **02 · Classificação:** Tabela de pontuação com destaque para o líder do campeonato e formulário visual de busca e filtro por equipe.
- **03 · Ingressos:** Tabela de valores por setor (*Arquibancada A*, *Setor da Reta* e *Box VIP*), alerta de disponibilidade e formulário completo para reserva e envio de recados/fotos para o telão.

## Tecnologias utilizadas

- **HTML5:** Estrutura semântica (`<header>`, `<main>`, `<section>`, `<article>`, `<table>`, `<form>`, `<footer>`).
- **CSS3:** Flexbox, variáveis CSS (`:root`), gradientes lineares/repetitivos, transições e responsividade com `@media queries`.
- **Google Fonts:** Tipografia *Titillium Web*.

## Estrutura de arquivos

```text
├── index.html      # Estrutura principal da página
├── style.css       # Estilização e regras de responsividade
└── img/
    └── piloto.jpg  # Imagem de fundo da seção Hero (adicionar localmente)
