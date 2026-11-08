KIMURA PRIME TIMER — protótipo inicial
=====================================

COMO TESTAR
1. Extraia o ZIP.
2. Abra index.html no navegador para testar o cronômetro.
3. Para instalar como PWA no Android, publique a pasta em um endereço HTTPS e use "Adicionar à tela inicial" no Chrome.

O QUE JÁ FUNCIONA
- Cronômetro de luta e descanso.
- Configuração de duração e quantidade de rounds.
- Alternância automática entre luta e descanso.
- Iniciar, pausar e reiniciar.
- Sinais sonoros gerados pelo navegador.
- Layout responsivo para celular e tela horizontal.
- Logo Kimura Prime incorporada como marca d'água.

SPOTIFY
Os botões e a área visual estão preparados, mas a conexão ainda não está ativada.
Para ativar:
1. Criar um app em https://developer.spotify.com/dashboard
2. Obter o Client ID.
3. Cadastrar a URL HTTPS publicada como Redirect URI.
4. Implementar o fluxo OAuth Authorization Code com PKCE e os escopos necessários.
5. Para controle remoto de reprodução, a conta normalmente precisa de Spotify Premium e um dispositivo Spotify ativo.
6. Para reprodução dentro do app via Spotify Web Playback SDK, também é necessário atender aos requisitos atuais do Spotify.

IMPORTANTE
Este é um protótipo funcional do cronômetro, não a versão final publicada. A integração Spotify e o processo de publicação/instalação precisam ser concluídos e testados em um domínio HTTPS.
