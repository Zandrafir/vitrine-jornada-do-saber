# Vitrine Jornada do Saber

Painel de apresentação (BI) do projeto Jornada do Saber, feito para um totem vertical ou uma TV horizontal. É um único arquivo, `index.html`, sem dependências.

## Como usar no totem (offline)
1. Baixe `index.html` (botão Raw > Salvar como, ou `git clone`).
2. Abra no navegador em tela cheia (F11). Funciona sem internet: as fontes (Bricolage Grotesque e Figtree, licença SIL OFL) estão embutidas no arquivo.
3. Os slides passam sozinhos; tocar na tela pausa por 60 s. Formatos testados: 1920x1080 (TV) e 1080x1920 (totem).

## Atualizar os dados
Os números ficam no objeto `D` dentro do `index.html`. As sugestões dos alunos entram em `D.sugestoes`, no formato `{d:"historia", t:"texto"}` (sem nomes nem RA).

## Aba "Futuras implementações"
Mostra a gravação (sem áudio, 46 s, embutida no próprio `index.html`) de uma aula de revisão de Iluminismo gerada de verdade com o OpenMAIC (THU-MAIC, licença MIT) a partir de um único pedido. O professor revisaria antes de publicar. Nada é gerado ao vivo na página e não há chave de API no repositório. O arquivo original da gravação está em `demo/openmaic.mp4`.

## Créditos
- Freeman e outros, PNAS, 2014: aprendizagem ativa em 225 estudos de CTEM.
- Fontes: SIL Open Font License.
