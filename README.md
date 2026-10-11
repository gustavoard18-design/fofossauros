# Quebra-Cabeça Fofossauros

Quebra-cabeça infantil com bichinhos de pelúcia e dinossauros. Roda direto no navegador, no celular, no tablet ou no computador, e pode ser instalado como app.

## O que tem

- 16 desenhos: 8 bichinhos de pelúcia e 8 dinossauros, todos vetoriais (nítidos em qualquer tela).
- 4 níveis: 4, 9, 16 ou 25 peças.
- Peças que encaixam sozinhas quando chegam perto do lugar certo.
- Desenho de fundo como ajuda (liga e desliga), botão de embaralhar e som.
- Progresso salvo no próprio aparelho.

## Como jogar

Escolha quantas peças, toque em um desenho e arraste cada peça até o lugar dela.

## Instalar no celular

1. Abra o endereço do jogo no navegador do celular.
2. Android (Chrome): menu ⋮ → **Adicionar à tela inicial** / **Instalar app**.
3. iPhone (Safari): botão Compartilhar → **Adicionar à Tela de Início**.

Depois da primeira abertura o jogo funciona sem internet.

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
