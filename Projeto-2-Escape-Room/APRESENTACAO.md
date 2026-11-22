# Roteiro de apresentação — Projeto 2

**Duração sugerida:** 5 a 7 minutos, ajustável às orientações do docente.

## 1. Introdução
O projeto é o jogo *O Código das Cinco Câmaras*. O objetivo é escapar de um laboratório, resolvendo desafios de Análise Combinatória em cinco fases.

## 2. Conteúdo matemático
- Fase 1: Princípio Fundamental da Contagem — multiplicação de escolhas independentes.
- Fase 2: Permutações simples e com repetição — anagramas.
- Fase 3: Arranjos simples — escolhas ordenadas, sem repetição.
- Fase 4: Combinações simples — grupos sem ordem.
- Fase 5: Restrições — elementos juntos, separados ou composição obrigatória de equipes.

Exemplo da fase 5: para n pessoas distintas, se A e B devem ficar juntos, tratamos (AB) como um bloco, o que gera 2(n−1)! sequências.

## 3. Tecnologia
O HTML estrutura a página, o CSS cria os cenários responsivos e as animações, e o JavaScript administra o sorteio das perguntas, validação matemática, progresso, pontuação, limite de erros e cronômetro. Os sons são gerados pelo próprio navegador, sem arquivos externos.

## 4. Demonstração
1. Mostrar a tela inicial e iniciar a partida.
2. Resolver um desafio, observar a explicação e o progresso.
3. Errar propositalmente uma questão e mostrar que o acerto anterior permanece.
4. Mostrar como a pergunta é substituída por outra questão inédita.
5. Explicar a distribuição de acertos entre as cinco fases.
6. Mostrar o banco de questões e o código-fonte no GitHub.

## 5. Conclusão
A matemática não aparece somente como exercício isolado: os problemas acionam mecanismos de cada sala. O jogador aplica diferentes estratégias combinatórias para liberar as câmaras. O projeto demonstra lógica de programação, validação de respostas, sorteio sem repetição, gerenciamento de estados e desenvolvimento de interface.

## 6. Perguntas que podem surgir
**Por que arranjo e não combinação na fase 3?** Porque ocupar funções diferentes depende de quem ocupa cada posição.

**Por que combinação na fase 4?** Porque selecionar um mesmo conjunto em outra ordem não muda a escolha.

**O jogador pode perder os acertos ao errar?** Não. Erros são contabilizados separadamente.

**O jogo exige internet?** Não para jogar localmente. Internet é necessária para publicação e acesso ao GitHub Pages.
