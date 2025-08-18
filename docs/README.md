# jogo-da-velha-git25

# 🎮 Jogo da Velha no GitHub

## Como funciona
Este é um jogo da velha colaborativo jogado via **Git e GitHub**.  
Cada jogada é feita alterando o arquivo `jogadas/jogadas.txt` e enviando um commit.

## Regras
- Dois jogadores: **X** (Jogador 1) e **O** (Jogador 2). X começa.
- Sempre **puxe** as mudanças antes de jogar: `git pull --ff-only`.
- Edite apenas `jogadas/jogadas.txt`.
- Em cada jogada:
  1. Substitua o número escolhido (0–8) por sua marca (X ou O).
  2. Atualize `vez:` para o próximo jogador.
  3. Incremente `rodada:`.
  4. Anote no `historico:`.
- Vitória: 3 em linha/coluna/diagonal.
- Fim: preencha `resultado:` e trave o jogo (não jogue mais).