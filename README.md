# BullBotArb

A basic bot to find arbitrage oppotunities on brazilian crypto exchanges.

Um robô simples para encontrar oportunidades de arbitragem em exchanges (bolsas) de criptomoedas brasileiras.

## Instalação

### Pré-requisitos
Você precisa ter Node 6 ou superior instalado

### Como instalar

1. Clone ou baixe o zip desse projeto.
2. Entre no diretório do projeto no terminal e instale as dependências usando o npm install:

`$ npm install`

## Usando

Entre no diretório do projeto no terminal e execute o index.js

`$ node index`

## To do
Esse projeto pode ser muito melhorado. Algumas funcionalidades que podem ser implementadas no futuro:
- Toda a automatização de um estratégia que execute essas ordens de arbitragem
-- Autenticação com chave de API nas exchanges
-- Analisar balanço das contas nas exchanges (R$ e BTC)
-- Abrir ordens com tamanhos diferentes dependo da "profundidade" dos livros de oferta em consideração. 

Esse projeto usa essa excelente biblioteca: [CCXT – CryptoCurrency eXchange Trading Library](https://github.com/kroitor/ccxt)