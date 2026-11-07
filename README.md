# uma-animacao-explosiva-por-favor

Skill do Claude Code para filmes de tipografia cinética em alta energia (palavras enormes a cada batida, chicotes de câmera, trocas de cor, letras em 3D). O filme é uma especificação em blocos sobre a grade de batidas da música; o motor transforma isso numa página em que cada quadro é função do tempo, e os scripts renderizam com desfoque de movimento real e checam o resultado.

## Origem
Adaptação da skill `scenario-kinetic-film`, que usa o Scenario MCP para música, efeitos e imagens. Esta versão foi ajustada para rodar numa máquina sem o Scenario MCP: Python por um ambiente uv descartável (`scripts/py`), efeitos sintetizados localmente (`scripts/synth_kit.py`) e notas sobre filmes mais calmos.

## Instalar
Copie a pasta para `~/.claude/skills/uma-animacao-explosiva-por-favor/`.

Precisa de Node 18+ com Playwright, ffmpeg/ffprobe e Python 3 com numpy e opencv (ou `uv`).

As fontes em `engine/fonts` são da licença SIL Open Font License (os textos da licença estão na pasta).
