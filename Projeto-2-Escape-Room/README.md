# Projeto 2 — Escape Room de Análise Combinatória

Projeto acadêmico de Matemática Discreta (UTFPR).

## Jogar

Abra `index.html` no navegador para executar o jogo com a interface completa. Para utilizar um único arquivo sem dependências, abra `JOGAR_OFFLINE.html`.

## Arquivos

- `index.html`: página principal do jogo.
- `style.css`: estilos e adaptação para celulares.
- `app.js`: lógica de fases, sorteios, acertos, erros e cronômetro.
- `questoes.json`: versão independente do banco de 50 questões (o jogo traz o mesmo banco embutido no HTML para funcionar offline).
- `JOGAR_OFFLINE.html`: versão completa em um só arquivo.
- `BANCO_DE_QUESTOES.md`: enunciados, respostas e resoluções.
- `APRESENTACAO.md`: roteiro da apresentação.

## Regras

Cinco fases, com 1, 2, 2, 3 e 4 acertos necessários, respectivamente (12 ao todo); 10 questões por fase; sorteio sem repetição até esgotar a fase; limite de 15 minutos ou 8 erros; opção de reiniciar.

## Publicação

Para disponibilizar na internet, ative o GitHub Pages em **Settings → Pages → Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`, caso a página esteja na raiz de um repositório dedicado. Como este projeto está em uma subpasta de um repositório de disciplina, o caminho do jogo após a ativação do Pages na raiz será `/Projeto-2-Escape-Room/`.

Este trabalho foi desenvolvido como auxílio acadêmico. A equipe deve compreender, testar e validar as questões e o funcionamento antes da entrega.
