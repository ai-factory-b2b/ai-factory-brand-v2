# AI Factory - Typography System

## Font Families

### Primary: Inter
```
Source: Google Fonts
URL: https://fonts.google.com/specimen/Inter
Import: @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;900&display=swap');
```

### Secondary: Space Grotesk
```
Source: Google Fonts  
URL: https://fonts.google.com/specimen/Space+Grotesk
Import: @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;600&display=swap');
```

---

## Type Scale

```css
/* H1 - Hero заголовок */
.h1 {
  font-family: 'Inter', sans-serif;
  font-weight: 900;
  font-size: clamp(48px, 8vw, 96px);
  line-height: 1.05;
  letter-spacing: -0.03em;
}

/* H2 - Секционный заголовок */
.h2 {
  font-family: 'Inter', sans-serif;
  font-weight: 700;
  font-size: clamp(32px, 5vw, 56px);
  line-height: 1.1;
  letter-spacing: -0.02em;
}

/* H3 - Подзаголовок */
.h3 {
  font-family: 'Inter', sans-serif;
  font-weight: 600;
  font-size: clamp(20px, 3vw, 32px);
  line-height: 1.2;
  letter-spacing: -0.01em;
}

/* Body - Основной текст */
.body {
  font-family: 'Inter', sans-serif;
  font-weight: 400;
  font-size: 17px;
  line-height: 1.6;
  letter-spacing: 0;
}

/* Caption - Подписи */
.caption {
  font-family: 'Space Grotesk', sans-serif;
  font-weight: 400;
  font-size: 13px;
  line-height: 1.4;
  letter-spacing: 0.01em;
}

/* Label - Теги, лейблы */
.label {
  font-family: 'Space Grotesk', sans-serif;
  font-weight: 600;
  font-size: 12px;
  line-height: 1;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

/* CTA Button */
.btn {
  font-family: 'Inter', sans-serif;
  font-weight: 700;
  font-size: 16px;
  line-height: 1;
  letter-spacing: -0.01em;
}
```

---

## Примеры применения

### На тёмном фоне (#0A0A0F)
```
Заголовок:    #F5F5F7  (AI White)
Подзаголовок: rgba(245,245,247,0.7)
Текст:        rgba(245,245,247,0.6)
Лейбл:        #4F8EF7  (AI Blue)
CTA:          #0A0A0F на градиентной кнопке
```

### На светлом фоне (#F5F5F7)  
```
Заголовок:    #0A0A0F  (AI Black)
Подзаголовок: rgba(10,10,15,0.7)
Текст:        rgba(10,10,15,0.6)
Лейбл:        #7B5CF0  (AI Violet)
```
