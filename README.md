# Vitrine Jornada do Saber

Painel de apresentação (BI) do projeto Jornada do Saber, feito para um totem vertical ou uma TV horizontal. É um único arquivo, `index.html`, sem dependências.

## Como usar no totem (offline)
1. Baixe `index.html` (botão Raw > Salvar como, ou `git clone`).
2. Abra no navegador em tela cheia (F11). Funciona sem internet: as fontes (Bricolage Grotesque e Figtree, licença SIL OFL) estão embutidas no arquivo.
3. Os slides passam sozinhos; tocar na tela pausa por 60 s. Formatos testados: 1920x1080 (TV) e 1080x1920 (totem).

## Atualizar os dados
Os números ficam no objeto `D` dentro do `index.html`. As sugestões dos alunos entram em `D.sugestoes`, no formato `{d:"historia", t:"texto"}` (sem nomes nem RA).

## Aba "Futuras implementações"
Toca um vídeo de divulgação (91 s, com narração) mostrando a Jornada do Saber (mesa de investigação, salão de jogos, chefão, painel do professor e aula de IA) e, em futuras implementações, o Estúdio do Professor (que orienta a criação de plano de aula, prova e atividade adaptada). O vídeo termina com o logo Jornada do Saber + OpenMAIC, que gera as aulas de IA. As cenas foram gravadas no modo Apresentação do jogo (dados fictícios) e no ambiente de teste do Estúdio. A narração foi gerada com ElevenLabs (voz Nassif); nenhuma chave de API fica neste repositório. A versão anterior (68 s, OpenMAIC) está em `demo/divulgacao-antigo.mp4`. O vídeo está embutido no `index.html`, então o arquivo continua único e funciona offline. Cópia solta em `demo/divulgacao.mp4`.

Tempo: ao entrar na aba, espera 5 s, toca o vídeo e, 10 s depois que ele termina, o rodízio segue.

Som no totem: o Chrome só toca áudio sozinho se for aberto com `--autoplay-policy=no-user-gesture-required`, por exemplo:
`chrome.exe --kiosk --autoplay-policy=no-user-gesture-required "caminho\\index.html"`
Sem essa opção o vídeo toca mudo; um toque na tela liga o som.
O botão pequeno de som no canto do vídeo liga e desliga o áudio e lembra a escolha (útil para o caso de a sala ficar vazia).

Narração: voz neural pt-BR gerada com edge-tts (AntonioNeural). Nada é gerado ao vivo e não há chave de API no repositório.

## Créditos
- Freeman e outros, PNAS, 2014: aprendizagem ativa em 225 estudos de CTEM.
- Fontes: SIL Open Font License.
- Aula de exemplo: OpenMAIC (THU-MAIC), MIT.
