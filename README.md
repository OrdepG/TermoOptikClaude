# TermoOptik

Ferramenta visual para composições generativas com efeitos de **câmara térmica**, **motion blur** e **vidro canelado** sobre imagens, vídeo e tipografia. Tudo corre no browser (WebGL2), sem build nem servidor.

## Funcionalidades
- Fonte gerativa (blobs, arco, anéis, seda, fluxo) + imagem/vídeo próprio + camadas de texto (Google Fonts ou fonte própria)
- Motion blur linear / zoom / rotação / turbulento, distorção líquida
- Vidro canelado, anéis ou ondulado com dispersão cromática
- Câmara térmica: paletas Ironbow, Predator, Arctic…, isotermas, contornos, ruído, scanlines, HUD
- Randomizar leve (R) ou agressivo (Shift+R), com bloqueio por secção e desfazer
- Exportação PNG/JPG/WEBP até 4× e vídeo MP4 (H.264, frame-a-frame, loop perfeito)
- Estúdio de mockups: adaptação automática a 9:16, 4:5, 1:1 e 16:9, 8 mockups em cena e pacote .zip

## Usar
Abre `index.html` num browser recente (Chrome/Edge recomendados para exportar MP4), ou publica com GitHub Pages.

## Dependências (carregadas por CDN)
- [mp4-muxer](https://github.com/Vanilagy/mp4-muxer) — exportação MP4
- [JSZip](https://stuk.github.io/jszip/) — pacote .zip
- Google Fonts
