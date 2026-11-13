# Vitrine Jornada do Saber

Painel de apresentação (BI) do projeto Jornada do Saber, feito para um totem vertical ou uma TV horizontal. É um único arquivo, `index.html`, sem dependências.

## Como usar no totem (offline)
1. Baixe `index.html` (botão Raw > Salvar como, ou `git clone`).
2. Abra no navegador em tela cheia (F11). Funciona sem internet: as fontes (Bricolage Grotesque e Figtree, licença SIL OFL) estão embutidas no arquivo.
3. Os slides passam sozinhos; tocar na tela pausa por 60 s. Formatos testados: 1920x1080 (TV) e 1080x1920 (totem).

## Atualizar os dados
Os números ficam no objeto `D` dentro do `index.html`. As sugestões dos alunos entram em `D.sugestoes`, no formato `{d:"historia", t:"texto"}` (sem nomes nem RA).

## Aba "Futuras implementações"
Demonstração de uma aula de revisão (Iluminismo) montada por IA e revisada pelo professor, inspirada no projeto OpenMAIC (THU-MAIC, MIT). O conteúdo foi gerado antes da exposição; nada é gerado ao vivo e não há chave de API no repositório.

## Créditos
- Freeman e outros, PNAS, 2014: aprendizagem ativa em 225 estudos de CTEM.
- Fontes: SIL Open Font License.
