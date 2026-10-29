# Sandra: Fuga da Ilha das Cobras

Jogo de plataforma 2D educativo desenvolvido para a disciplina de Desenvolvimento de Jogos, ambientado na Ilha da Queimada Grande (conhecida como a Ilha das Cobras), no litoral do estado de São Paulo.

> **Deploy:** [sandra-fuga-da-ilha-das-cobras.netlify.app](https://sandra-fuga-da-ilha-das-cobras.netlify.app)

---

## Destaque Académico

O projeto foi classificado no **Top 10** entre mais de 60 trabalhos apresentados pelos cursos de **Sistemas de Informação** e **Análise e Desenvolvimento de Sistemas (ADS)**. A avaliação considerou a viabilidade técnica, o design das fases e a contextualização pedagógica com o património regional da Baixada Santista.

---

## Visão Geral

A proposta consistiu na criação de um jogo focado na divulgação de um ponto turístico ou histórico da região de Santos e arredores. 

O cenário escolhido foi a Ilha da Queimada Grande, reserva ecológica célebre pela presença da jararaca-ilhoa (*Bothrops insularis*). O jogador controla a personagem Sandra, enfrentando obstáculos de terreno e elementos da fauna local, com mecânicas desenhadas para reforçar a consciencialização ambiental e a preservação do ecossistema costeiro.

---

## Especificações Técnicas

- **Engine:** Scirra Construct (arquitetura baseada em eventos).
- **Frontend & Execução:** Exportação Web padrão HTML5, folhas de estilo CSS3 e JavaScript modular (ES Modules).
- **Recursos Offline & PWA:** Registo de Service Worker (`sw.js`) e manifesto de aplicação (`appmanifest.json`) para suporte a execução local em cache.
- **Hospedagem:** Netlify (integração contínua e distribuição estática).

---

## Estrutura do Repositório

```text
├── icons/            # Ícones do manifesto PWA
├── images/           # Spritesheets e texturas dos cenários
├── media/            # Efeitos sonoros e faixas de áudio
├── scripts/          # Módulos JavaScript de suporte e lógica do motor
├── appmanifest.json  # Configuração de Progressive Web App
├── index.html        # Ponto de entrada da aplicação
└── style.css         # Reset e contentor de visualização
