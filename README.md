# Jogo da Velha

Clone funcional do clássico jogo da velha, desenvolvido com **Angular 10+**, **TypeScript**, **HTML5** e **SCSS**.  
O projeto organiza o tabuleiro e os componentes de forma modular, separando **lógica do jogo** e interface, garantindo manutenção e escalabilidade.

---

## Funcionalidades

- Tabuleiro interativo 3x3 com suporte a dois jogadores
- Detecção automática de vitória e empate
- Feedback visual para jogadas e resultados
- Estrutura modular de componentes Angular
- Testes unitários cobrindo a lógica do jogo e comportamento dos componentes

---

## Link de Acesso

Veja o jogo funcionando online: [Jogo da velha clássico](http://adriano-albuquerque-jogo-da-velha.s3-website.us-east-2.amazonaws.com/#)

---

## Tecnologias Utilizadas

- **Angular 10+** (via Angular CLI)
- **TypeScript**
- **HTML5 / SCSS**
- **Node.js** e **npm** para execução e gerenciamento de dependências

---

## Mapa do Projeto

Estrutura principal do repositório:

````bash
jogo-da-velha/
│
├─ src/
│ ├─ app/
│ │ ├─ components/
│ │ │ ├─ board/ # Tabuleiro do jogo
│ │ │ └─ cell/ # Células individuais
│ │ ├─ services/ # Serviços para lógica do jogo
│ │ └─ app.module.ts
│ ├─ assets/ # Imagens e recursos
│ └─ styles.scss # Estilos globais
│
├─ angular.json
├─ package.json
└─ README.md
````
---

## Instalação

Clone o repositório:

```bash
git clone https://github.com/adrianoalbuquerque/jogo-da-velha.git
cd jogo-da-velha
````

Instale as dependências:

```bash
npm install
````

## Execução

Para rodar o projeto localmente:

```bash
ng serve
````

## Próximos Passos / Melhorias Futuras

- Adicionar modo contra a máquina (IA simples ou algoritmo Minimax)
- Salvar histórico de partidas localmente
- Implementar multiplayer online via WebSocket ou Firebase
- Melhorias de interface e animações adicionais

## Contribuição

Contribuições são bem-vindas! Abra issues ou envie pull requests para colaborar com melhorias.

## Licença

Este projeto está sob a licença MIT.
