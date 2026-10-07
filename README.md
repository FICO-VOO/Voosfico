# Voos FICO

Ferramentas web para os vídeos de voo de drone da FICO.

## Gerador de legenda — https://fico-voo.github.io/Voosfico/

Converte a legenda `.SRT` de voos de drone DJI, cruza as coordenadas com a base de estacas da ferrovia e gera:

- nova legenda com km, pacote, segmento, cidade, corte/aterro (com extensão), OAE, PN, pátios, AMV, bueiros e passagens, e as ligações Norte e Sul com a Ferrovia Norte-Sul;
- vídeo com a legenda gravada, mini-mapa e logos, com velocidade variável em km/min;
- vários vídeos em sequência juntados num vídeo único, com corte automático das sobreposições, correção de km por vídeo e km inicial/final do vídeo final;
- os dados de km gravados no próprio vídeo e num arquivo `_KM.json`, para abrir no Player FICO.

A base de estacas da FICO (BD estacas, versão de 07/10/2026, incluindo a Alça Sul) já vem embutida na página.

## Player FICO — https://fico-voo.github.io/Voosfico/player.html

Reproduz os vídeos exportados pelo gerador com a barra de progresso em km, os pontos do trecho com filtros por tipo e um catálogo dos vídeos da pasta do Google Drive organizado por Pacote › Mês.

Os vídeos, legendas e logos de quem usa o gerador são processados no próprio navegador e não são enviados para nenhum servidor. Use Google Chrome ou Microsoft Edge atualizados.

Desenvolvido por Filipe Milani.
