# Quebra-Cabeça Fofossauros

Quebra-cabeça infantil com bichinhos de pelúcia, dinossauros, Dia das Bruxas e fundo do mar. Roda direto no navegador, no celular, no tablet ou no computador, e pode ser instalado como app.

## O que tem

- 46 desenhos: 8 bichinhos de pelúcia, 8 dinossauros, 10 de Dia das Bruxas, 10 do fundo do mar e 10 do Cantinho Fofo (traço grosso, estilo livro de colorir), todos vetoriais (nítidos em qualquer tela).
- 4 níveis: 4, 9, 16 ou 25 peças. Cada nível montado vale uma estrela (184 no total).
- Peças que encaixam sozinhas quando chegam perto do lugar certo, com um brilho mostrando o lugar.
- Dica (lâmpada) que mostra onde vai uma peça, desenho de fundo que liga e desliga, e botão de embaralhar.
- Jogo em andamento salvo sozinho: dá para sair e continuar depois de onde parou.
- Tempo de cada montagem e melhor tempo por desenho.
- Sem anúncios, sem compras e sem coleta de dados. Tudo fica salvo só no aparelho.

## Como jogar

Escolha quantas peças, toque em um desenho e arraste cada peça até o lugar dela. Toque na miniatura do desenho, no alto, para ver a imagem inteira ou começar de novo.

## Instalar no celular

1. Abra o endereço do jogo no navegador do celular.
2. Android (Chrome): menu ⋮ → **Adicionar à tela inicial** / **Instalar app**.
3. iPhone (Safari): botão Compartilhar → **Adicionar à Tela de Início**.

Instalado, o jogo abre em tela cheia e funciona sem internet depois da primeira abertura.

Sem instalar, no Android o jogo entra em tela cheia ao tocar em um desenho; o botão no canto da tela inicial liga e desliga isso. No iPhone a tela cheia só existe na versão instalada.

## Rodar no computador

Não precisa instalar nada. Sirva a pasta com qualquer servidor estático, por exemplo:

```
python3 -m http.server 8000
```

e abra `http://localhost:8000`.

## Arquivos

| Arquivo | Para que serve |
| --- | --- |
| `index.html` | O jogo inteiro: desenhos, regras e visual |
| `manifest.webmanifest` | Nome, cores e ícones do app instalável |
| `sw.js` | Guarda o jogo no aparelho para abrir sem internet |
| `icons/` | Ícones do app |
