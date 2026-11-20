# Mini Knobz: identidade visual

Referência visual oficial do **Mini Knobz** (5 plugins de um botão: BITE, PHAT, KICKSIDE, WIDE, GASP). Atualizado em 20/11/2026; cores conferidas no código (`Source/Dsp/Spec.cpp` e `Source/Common/Editor.cpp`). Imagens em [`img/`](img/).

![As 5 janelas lado a lado](img/telas-todas.png)

## Regras que não mudam

- As 5 janelas são **idênticas** na estrutura; só a cor de destaque muda.
- Fundo **quase preto**, sem textura. Nada de texto explicativo na janela: a explicação fica no popup **i**.
- Rodapé sempre com **"by audiomakers"** e versão.
- Tamanho de design 300x480 (mostrado a 125%).

## Cor de cada plugin

| Plugin | Cor | Hex |
|---|---|---|
| BITE | laranja-vermelho | `#FF5A36` |
| PHAT | rosa | `#FF4D9A` |
| KICKSIDE | verde-limão | `#B6F23A` |
| WIDE | ciano | `#3DD6FF` |
| GASP | violeta | `#A98BFF` |

Nas peças do pacote, os 5 aparecem juntos sempre nessa ordem (BITE, PHAT, KICKSIDE, WIDE, GASP) e as 5 bolinhas coloridas viram o símbolo do pacote ("●●●●● 5 PLUGINS · 1 KNOB CADA").

| BITE | PHAT | KICKSIDE | WIDE | GASP |
|---|---|---|---|---|
| ![](img/bite.png) | ![](img/phat.png) | ![](img/kickside.png) | ![](img/wide.png) | ![](img/gasp.png) |

## Cores de base da interface

| Token | Hex |
|---|---|
| Fundo (topo → base, gradiente vertical) | `#121318` → `#08080B` |
| Poço do knob / áreas fundas | `#060608`, borda `#1B1C23` |
| Chips e botões | `#111217`, borda `#262833` |
| Texto | `#ECEDF3` |
| Texto suave | `#C9CBD8` |
| Texto apagado | `#8B8EA0` |
| Desligado | `#4A4C58` |
| OK / mono seguro | `#3DE08A` |
| Aviso | `#FFD23F` |

## Fontes

- **Space Grotesk Bold**: nome do plugin (BITE, GASP...) e títulos com letras espaçadas.
- **Space Grotesk Medium**: opções e rótulos (TAPE, DEPTH, 1/4).
- **Inter Bold / Regular**: números do knob, textos de ajuda, rodapé.

Todas em `Assets/Fonts/` (SIL Open Font License).

## Anatomia da janela (de cima para baixo)

1. Topo: ícone de power + "knobz", botões **i** (ajuda) e engrenagem (configurações).
2. Nome do plugin grande, na cor dele.
3. Barra de opções (TAPE/TUBE/DRIVE/CLIP etc.); a escolhida fica com caixa e brilho na cor.
4. **Knob grande**: anel de traços que acendem na cor conforme gira, número no centro (45, 40, 70, 50, 1/2), rótulo embaixo (DRIVE, AMOUNT, DEPTH, WIDTH, SIZE).
5. Linha extra: slider MIX / MONO BASS, seletor de tempo (KICKSIDE) ou forma de onda + play + botão **WAV** arrastável (GASP).
6. Rodapé: bypass (power), "by audiomakers", versão.

No KICKSIDE as opções são **desenhos de curva** (não texto), gerados pela mesma função que processa o áudio.

Popup de ajuda (**i**) e o GASP antes de receber áudio:

![Popup de ajuda e GASP vazio](img/popup-ajuda-e-gasp-vazio.png)

## Peças prontas

### Story 1080×1920 (molde aprovado pelo Ed)

![Story Mini Knobz](img/story-1080x1920.png)

De cima para baixo, tudo centralizado:
1. Topo livre (~250 px) para a barra do Instagram.
2. Pílula com as **5 bolinhas** nas cores dos plugins + "5 PLUGINS · 1 KNOB CADA".
3. **MINI KNOBZ** gigante, branco, Bold.
4. "Um knob. Som pronto." em gradiente rosa → violeta → ciano.
5. As **5 janelas em leque**, KICKSIDE no meio e maior, laterais inclinadas e escurecidas, glow suave nas cores.
6. Nomes dos plugins na cor de cada um: BITE PHAT KICKSIDE WIDE GASP.
7. **"Os 5 por R$17"** grande + "Pagamento único · Windows e Mac".
8. "TOQUE NO LINK" + seta. Rodapé livre (~340 px) para o campo de resposta.

Esse molde foi reaproveitado no story do Chord Code Pro (R$37).

### Capas da loja

![Capa 1920x1080](img/capa-1920x1080.png)

Também em 1200×1200 ([`img/capa-1200x1200.png`](img/capa-1200x1200.png)) e sem fundo ([`img/capa-transparente.png`](img/capa-transparente.png)).

### Marca

![Audio Makers](img/logo-audiomakers.png)

Lista completa de imagens: [README.md](README.md).
