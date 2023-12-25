# bit-chess

Olá! Nós somos a bit-chess. Temos como objetivo finalizar um projeto que teve inicio em 2020. Vamos construir um robô que joga xadrez!

## Atuais Objetivos
Os principais objetivos são:

- Reescrever a I.A. em C++;
- Desenvolver um tabuleiro interativo para visualizar a situação do tabuleiro(identificação das peças);
- Desenvolver uma estação de comunicação entre _desktop_ e o sistema embarcado;
- Implementar um braço robótico(objetivo final).

## Projetos
A equipe vivência este projeto desde 2020, tendo uma pausa nos anos 2021 e 2022. Aqui encontra-se listado o histórico das versões dos nossos projetos:

- (2020 - 2020) v1.0: https://github.com/SageScroll18144/Last-chess-ai (I.A. consolidada com representação em matriz de caractere + Antigo sistema robótico)
- (2020 - 2023) v1.1: https://github.com/bit-chess/chess-ai-v1 (I.A. consolidada com representação em matriz de caractere + Novo sistema robótico)
- (2023 - atual) v1.2: https://github.com/bit-chess/A.I.N.B (I.A. consolidada com representação em matriz de caractere + uma metodologia de pontuação baseada em naive bayes + Novo sistema robótico)
  
- (2020 - 2020) v2.0: https://github.com/lightTuring/chess-ai (I.A. consolidada com representação em Bitboard + Antigo sistema robótico)
- (2020 - 2023) v2.1: https://github.com/bit-chess/chess-ai-v2/ (I.A. consolidada com representação em Bitboard + Novo sistema robótico)
  
- (2023 - atual) v3.0: Refere-se aos trabalhos encontrados em [A.I](https://github.com/bit-chess/A.I.), [Board](https://github.com/bit-chess/Board) e [GUI_chess](https://github.com/bit-chess/GUI_chess). Versão está em construição, entretanto propõe uma versão mais eficiente do quê as anteriores e mantem a mesma abordagem computacional.

Para entender os trabalhos de 2020 recomendamos ler o nosso TDP, Disponivel em: https://drive.google.com/file/d/1rTdJqFt6BltWr87E1yHgR3u4hoA96uiU/view?usp=sharing.

## Subprojetos
A equipe desenvolve aplicações voltadas para a produtividade do trabalho e também softwares que compõe mais de um micro projeto.

### App
Aplicativos desenvolvidos pela equipe!

#### rank-file
Web site escrito em C que gera Bitboard

-  Link: https://bit-chess.github.io/rank-file/index.html

### Submodulos
Os submodulos são scripts que compõe mais de um projeto. São implementandos em repositórios a parte, assim facilitando a coerencia da manutenção de código.

#### C/C++
Submodulos da terceira versão do projeto

- [analyser_](https://github.com/bit-chess/analyzer_) : FSM de análise da jogada vinda do tabuleiro fisico.
- [serial](https://github.com/bit-chess/serial): Comunicação serial C-Desktop e Sistema embarcado.

#### Java
Submodulos para as primeiras versões do projeto

- [Analyser](https://github.com/bit-chess/Analyzer) : FSM de análise da jogada vinda do tabuleiro fisico.
- [Communication](https://github.com/bit-chess/Communication): Comunicação serial Java-SE e Sistema embarcado.

## Referências

- Chess Programming Wiki. Página Principal. Disponível em: https://www.chessprogramming.org/Main_Page. Acesso em 2020.

## Membros

- 2020 - presente: [Felipe Santos](https://github.com/SageScroll18144), [Pedro Barros](https://github.com/lightTuring), [Lucas Absalão](https://github.com/LightAsh04).
- 2023 - presente: [Victor Mendonça](https://github.com/Mend25/), [Welton Felix](https://github.com/weltonfelix).
