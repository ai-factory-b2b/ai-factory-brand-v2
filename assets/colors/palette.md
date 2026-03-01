# AI Factory - Color Palette

## Primary Colors

| Name | HEX | RGB | HSL | Usage |
|---|---|---|---|---|
| AI Black | `#0A0A0F` | 10, 10, 15 | 240°, 20%, 5% | Основной фон |
| AI White | `#F5F5F7` | 245, 245, 247 | 240°, 9%, 96% | Светлый фон, текст на тёмном |
| AI Blue | `#4F8EF7` | 79, 142, 247 | 217°, 91%, 64% | Акцент, CTA |

## Accent Colors

| Name | HEX | RGB | HSL | Usage |
|---|---|---|---|---|
| AI Violet | `#7B5CF0` | 123, 92, 240 | 255°, 84%, 65% | Градиент, иконки |
| AI Cyan | `#00D4FF` | 0, 212, 255 | 191°, 100%, 50% | Технологичные акценты |
| AI Gray | `#1C1C24` | 28, 28, 36 | 240°, 13%, 13% | Карточки, секции |

## Gradients

```css
/* Основной градиент */
background: linear-gradient(135deg, #4F8EF7 0%, #7B5CF0 100%);

/* Тёмный градиент (фон) */
background: linear-gradient(180deg, #0A0A0F 0%, #12121E 100%);

/* Сияние (glow effect) */
box-shadow: 0 0 40px rgba(79, 142, 247, 0.3);

/* Cyan glow */
box-shadow: 0 0 20px rgba(0, 212, 255, 0.4);
```

## Opacity Variants

```
AI Blue / 10%  - #4F8EF71A  - Тонкие подложки
AI Blue / 20%  - #4F8EF733  - Hover-состояния
AI Blue / 50%  - #4F8EF780  - Disabled states
AI White / 10% - #F5F5F71A  - Разделители
AI White / 60% - #F5F5F799  - Вторичный текст
```

## CSS Variables

```css
:root {
  --color-black: #0A0A0F;
  --color-white: #F5F5F7;
  --color-blue: #4F8EF7;
  --color-violet: #7B5CF0;
  --color-cyan: #00D4FF;
  --color-gray: #1C1C24;
  
  --gradient-primary: linear-gradient(135deg, #4F8EF7, #7B5CF0);
  --gradient-dark: linear-gradient(180deg, #0A0A0F, #12121E);
  
  --glow-blue: 0 0 40px rgba(79, 142, 247, 0.3);
  --glow-cyan: 0 0 20px rgba(0, 212, 255, 0.4);
}
```
