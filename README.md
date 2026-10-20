# Traço Estúdio

Protótipo de app de desenho e animação que roda direto no navegador, feito para usar com mesa digitalizadora (Wacom, XP-Pen, Huion, Apple Pencil). A meta do projeto é ser prático como o ibisPaint, com a pintura do Procreate e da Adobe e, nas próximas versões, as ferramentas vetoriais do CorelDRAW.

**Usar agora:** https://eddcortinas.github.io/traco-estudio/

## O que já funciona

- Pincéis caneta, lápis, marcador e aerógrafo com sensibilidade à pressão
- Borracha, inclusive pela ponta traseira da caneta (se a mesa enviar)
- Conta-gotas (tecla I ou Alt + clique)
- Camadas com visibilidade e opacidade
- Estabilizador de traço e simetria espelhada
- Linha do tempo de animação com papel vegetal (onion skin) e velocidade ajustável
- Desfazer e refazer, inclusive com toque de 2 e 3 dedos
- Exportar o quadro em PNG e a animação em vídeo
- Leitura da caneta em tempo real (pressão, inclinação, amostras por segundo) para testar a mesa

## Atalhos

| Tecla | Ação |
| --- | --- |
| B / E / I | Pincel / borracha / conta-gotas |
| 1 a 4 | Caneta, lápis, marcador, aerógrafo |
| [ e ] | Diminuir / aumentar o pincel |
| , e . | Quadro anterior / próximo |
| P | Tocar / parar |
| N / D | Novo quadro / duplicar quadro |
| O | Ligar / desligar papel vegetal |
| Ctrl+Z / Ctrl+Shift+Z | Desfazer / refazer |

## Se a pressão da caneta não funcionar

No Windows, abra o driver da mesa e ative a opção **Windows Ink**. Use Chrome, Edge ou Firefox atualizados.

## Rodar localmente

É um único arquivo: abra `index.html` no navegador. Não precisa instalar nada.
