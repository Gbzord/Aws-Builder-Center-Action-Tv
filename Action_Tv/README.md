# AWS Builder Center TV Display

Tela promocional interativa criada para exibir anúncios e mensagens do AWS Builder Center em TVs ou displays digitais.

## Visão Geral

Este projeto entrega um banner de apresentação estilizado com:

- slide inicial com headline animada e recursos em destaque
- badge de "Inscrições Abertas"
- ticker de notícias em rodapé
- QR Code para direcionar o público ao Builder Center
- segundo slide com vídeo em loop
- fallback offline para exibição sem servidor

## O que está incluído

- `aws_builder_center_tv_display.html` — página principal do display
- `Fonte/` — fonte customizada usada no layout
- `image/` — ativos visuais, logo e QR Code
- `Video/` — vídeo de fundo para o segundo slide

## Principais recursos

- layout preparado para telas grandes e TV
- transição automática entre slides a cada 12 segundos
- animações de entrada elegantes e grid de fundo
- QR Code local com fallback para geração via CDN
- design compatível com exibição offline
- vídeo em loop para impacto visual adicional

## Como usar

1. Copie toda a pasta `Action_Tv` para o dispositivo ou servidor onde a tela será exibida.
2. Abra `aws_builder_center_tv_display.html` em um navegador compatível.
3. Ative o modo de tela cheia para melhor experiência.

> Recomendado: Chrome ou Edge no modo kiosk/tela cheia.

## Teste local rápido

- Para abrir diretamente: clique duas vezes em `aws_builder_center_tv_display.html`.
- Se o navegador bloquear o acesso local, use uma extensão como `Live Server` ou um servidor HTTP simples.

## Personalização rápida

- Edite o texto principal em `aws_builder_center_tv_display.html`
- Substitua `Video/Aws_Video.mp4` pelo seu próprio vídeo
- Troque `image/Qr_Code_2.png` para atualizar o QR Code
- Ajuste cores e tempos no CSS interno do HTML
- Atualize os cards do recurso e o ticker para mensagens personalizadas

## Compatibilidade

- Navegadores suportados: Chrome, Edge, Firefox modernos
- Requer suporte a HTML5, CSS3 e vídeo MP4
- Funciona offline quando os ativos locais estão presentes

## Notas importantes

- O QR Code tenta carregar `image/Qr_Code_2.png` primeiro.
- Se a imagem não estiver disponível, o display usa um gerador de QR Code via CDN.
- Se você quiser rodá-lo em um ambiente fechado, garanta que o arquivo de vídeo e as imagens estejam presentes.

## Licença

Use este projeto livremente para apresentações internas, eventos e ativações de marca. Caso queira compartilhar, mencione a fonte do material original.

