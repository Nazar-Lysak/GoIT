
# 👩‍🏫 Адаптивний дизайн

---

> ⚠️ 96dpi — стандартна щільність. Для Retina/HiDPI — 192dpi (2x).
> 1x img (96dpi), 2x (192pdi), 3x (288dpi)

## 1. Адаптивна графіка

Адаптивні зображення та фонові зображення, що змінюються залежно від роздільної здатності екрану.

---

## 2. Респонсивні зображення
```html
<img 
  src="./images/kisspng-milk.png" 
  srcset="./images/milk.png 1x, ./images/nuts.png 2x"
  width="206" 
  height="160" 
  alt="Milk chocolate"
>

<picture>
  <source 
      media="(min-width: 1200px)" 
      srcset="../images/nazar.png 1x, ../images/how-its-made.jpg 2x"
  >
  <source 
      media="(min-width: 768px)" 
      srcset="../images/olena.png 1x, ../images/how-its-made.jpg 2x"
  >
  <source 
      media="(max-width: 767px)" 
      srcset="../images/viktoria.png 1x, ../images/how-its-made.jpg 2x"
  >
  <img src="../images/semi-sweet.png" alt="semi-sweet">
</picture>
```

---

## 3. Фонові зображення
```css
@media (min-resolution: 192dpi) {
  .box {
    background-image: url('photo@2x.png');
  }
}

@media screen and (min-width: 1200px) and (resolution: 192dpi) {
  .box {
    background-image: url('photo@2x.png');
  }
}

.box {
  background-image: image-set(
    url('photo.png') 1x,
    url('photo@2x.png') 2x
  );
  background-size: cover;
}
```

