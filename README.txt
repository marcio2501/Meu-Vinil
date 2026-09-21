TOCA-DISCOS PWA

Arquivos:
- index.html
- manifest.json
- service-worker.js
- logo-192.png  <- coloque aqui o arquivo com este nome
- logo-512.png  <- coloque aqui o arquivo com este nome

A instalação PWA exige HTTPS (ou localhost). O index.html já referencia os dois logos pelos nomes acima.

Playlists:
- 19 playlists normais foram substituídas pelos IDs enviados.
- Os 2 links RD... enviados foram tratados como vídeos individuais, pois não são playlists públicas normais da YouTube Data API.

Instalação:
- Android Chrome/Edge: usa beforeinstallprompt quando o navegador liberar o PWA.
- iPhone/iPad Safari: mostra instruções para Compartilhar > Adicionar à Tela de Início.
- Instagram/Facebook: orienta abrir no navegador externo e permite copiar o link.
- Outros navegadores: mostra as opções equivalentes do menu.
