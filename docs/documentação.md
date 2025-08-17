# Documentação das Jogadas por Branch

## Jogada 1 - Branch: jogador-1 (X)

- Jogadas realizadas:
	- Posição escolhida: 5 (meio do tabuleiro)
	- Estratégia: Ataque, iniciando pelo meio para abrir um leque de tentativas.
- Tabuleiro após jogada:
	```
	O | 2 | 3
	4 | 5 | 6
	7 | 8 | 9
	```

## Jogada 2 - Branch: jogador-2 (O)
- Jogadas realizadas:
	- Posição escolhida: 1 (Canto superior esquerdo)
	- Estratégia: Ataque, iniciando pelo canto para tentar formar linha.
- Tabuleiro após jogada:
	```
	O | 2 | 3
	4 | X | 6
	7 | 8 | 9
	```

## Jogada 3 - Branch: jogador-1 (X)
- Jogadas realizadas:
	- Posição escolhida: 6 (linha do meio á direita)
	- Estratégia: Ataque, para tentar formar linha em orientação horizontal pelo meio.
- Tabuleiro após jogada:
	```
	O | 2 | 3
	4 | X | X
	7 | 8 | 9
	```

## Jogada 4 - Branch: jogador-2 (O)
- Jogadas realizadas:
	- Posição escolhida: 3 (canto superior direito)
	- Estratégia: Ataque, para tentar formar linha em orientação horizontal pelo meio.
- Tabuleiro após jogada:
	```
	O | 2 | O
	4 | X | X
	7 | 8 | 9
	```

## Jogada 5 - Branch: jogador-1 (X)
- Jogadas realizadas:
	- Posição escolhida: 4 (linha do meio á esquerda)
	- Estratégia: Ataque, para finalizar o jogo.
- Tabuleiro após jogada:
	```
	O | 2 | O
	X | X | X
	7 | 8 | 9
	```
---

# Relatório de Dificuldades

## Dificuldades Encontradas
- Conflitos de merge ao tentar unir branches com históricos diferentes.
- Necessidade de usar `--allow-unrelated-histories` para forçar o merge.
- Erros ao tentar visualizar ou excluir branches existente/inexistentes.
- Sincronização das jogadas entre branches, exigiu atenção ao fluxo de git (fetch, pull, push).

## Defesa e Ataque

- **Defesa:** Jogador-2 focou em bloquear linhas do jogador-1, escolhendo posições estratégicas para impedir vitória rápida.
- **Ataque:** Jogador-1 priorizou cantos e centro para maximizar chances de formar linha e pressionar o adversário.