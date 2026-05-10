# Paleta de Cores — Simone Clezar Decoradora

## Cores principais

| Nome | Hex | Uso |
|---|---|---|
| Rosa (primária) | `#ff4e79` | Seções hero, cabeçalho, rodapé, fundo principal |
| Azul (secundária) | `#51c0dd` | Botões CTA, seções de serviços e depoimentos |
| Amarelo (destaque) | `#f5c904` | Elementos de destaque, ícones, acentos |

---

## Variantes de contraste

### Rosa `#ff4e79`

| Variante | Hex | Uso |
|---|---|---|
| Hover | `#e63d69` | Hover/active do botão primário |
| Escuro 1 | `#cc2a52` | Fundos escuros, dark-2 |
| Escuro 2 | `#bd2049` | Hover do dark-2 |
| Muito escuro | `#2d0a14` | Background dark-3 (menus, offcanvas) |
| Máximo escuro | `#250a12` | Hover background dark-3 |

### Azul `#51c0dd`

| Variante | Hex | Uso |
|---|---|---|
| Hover | `#3aadc9` | Hover do botão secundário |
| Médio | `#5ec5e1` | Variação mid |
| Claro | `#7dd4ea` | Elementos sutis, bordas |
| Mais claro | `#99dff0` | Fundos suaves |
| Tom pastel | `#bbecf6` | Backgrounds muito sutis |
| Pastel suave | `#c9f0f8` | Fundos ultra leves |
| Ultra leve | `#e8f8fc` | Quase branco azulado |

### Amarelo `#f5c904`

| Variante | Hex | Uso |
|---|---|---|
| Hover/escuro | `#c9a403` | Hover do elemento de destaque |
| Escuro 2 | `#dcb504` | Variação intermediária escura |
| Escuro 3 | `#d4b004` | Alternativa escura |
| Tom 2 | `#f6d004` | Variante próxima ao base |
| Tom 3 | `#f7d620` | Variante mais clara |
| Tom 4 | `#f7d635` | Variante levemente mais clara |
| Tom 5 | `#f8dc55` | Médio claro |
| Tom 6 | `#f9e050` | Claro |
| Tom 7 | `#f9e270` | Mais claro |
| Tom 8 | `#fae870` | Claro suave |
| Pastel 1 | `#fcf098` | Pastel |
| Pastel 2 | `#fdf3b3` | Pastel claro |
| Ultra leve | `#fefae5` | Fundo quase branco amarelado |
| Off-white | `#fefde8` | Variante off-white |

---

## Cores de suporte (neutras)

| Hex | Uso |
|---|---|
| `#111111` | Texto principal |
| `#ffffff` | Fundo branco / texto em fundos escuros |
| `#f5f7fa` | Fundo cinza ultraclaro |
| `#e0e5eb` | Divisores, bordas sutis |
| `#b3bec9` | Texto secundário |
| `#808080` | Texto desabilitado |

---

## Como as cores são aplicadas nas seções

| Seção | Cor de fundo | Classe CSS |
|---|---|---|
| Header | Transparente sobre Rosa | `u-palette-1-base` |
| Hero (1) | Rosa `#ff4e79` | `u-palette-1-base` |
| Sobre (2) | Cinza claro | `u-grey-5` |
| Serviços (3) | Azul `#51c0dd` | `u-palette-3-base` |
| Galeria (4) | Rosa `#ff4e79` | `u-palette-1-base` |
| Processo (5) | Branco | (padrão) |
| Depoimentos (6) | Azul `#51c0dd` | `u-palette-3-base` |
| Contato (7) | Rosa `#ff4e79` | `u-palette-1-base` |
| Rodapé | Rosa `#ff4e79` | `u-palette-1-base` |

---

## Referência rápida (CSS variables sugeridas para futuro)

```css
:root {
  --color-primary:       #ff4e79;
  --color-primary-dark:  #cc2a52;
  --color-primary-hover: #e63d69;

  --color-secondary:       #51c0dd;
  --color-secondary-dark:  #3aadc9;
  --color-secondary-light: #7dd4ea;

  --color-accent:       #f5c904;
  --color-accent-dark:  #c9a403;
  --color-accent-light: #f9e270;

  --color-text:       #111111;
  --color-text-light: #ffffff;
  --color-bg:         #ffffff;
  --color-bg-soft:    #f5f7fa;
}
```
