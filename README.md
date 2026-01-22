# 📌 Модуль 3.2: Блокова модель та флексбокс

## 🔹 1. План заняття

- Блокова модель елемента
- Властивості `width` та `height`
- Модель візуального форматування: `box-sizing`
- Геометрія елемента
- Рамки та заокруглені рамки
- "Схлопування" і випадіння вертикальних маржинів
- Горизонтальне центрування блокових елементів
- Типи боксів: блокові, рядкові та рядково-блокові елементи. Властивість `display`

---

## 🔹 2. Flexbox

### Властивість display:

- **display:** — flex | inline-flex


### Властивості flex контейнера:

- **gap:** — відступ між flex елементами
- **flex-direction:** — row | row-reverse | co column-reverselumn |
- **justify-content:** — flex-start | flex-end | center | space-between | space-around | space-evenly
- **align-items:** — stretch | flex-start | flex-end | center | baseline
- **flex-wrap:** — nowrap | wrap | wrap-reverse
- **align-content:** — flex-start | flex-end | center | space-between | space-around | space-evenly | stretch

- **CSS-функція calc():** — calc((100% - 20px * 2) / 3);


### Властивості flex елементів:
- **flex-basis:** — auto | значення
- **flex-grow:** — значення
- **flex-shrink:** — значення 
- **align-self:** — auto | flex-start | flex-end | center | baseline | stretch 
- **order:** — позиція 


## 🔹 3. Структурні псевдокласи
**Стани елементів** (інтерактивні):

- **:hover** — коли курсор на елементі
- **:focus** — коли елемент у фокусі (наприклад, інпут)
- **:active** — під час кліку
- **:visited** — для відвіданих посилань

**Положення в DOM**:
- **:first-child** — перший елемент у батьківському
- **:last-child** — останній
- **:nth-child(n)** — n-ий за рахунком (number | odd | even)

** Фільтрація**:
- **:not(selector)** — все, крім вказаного
- **:empty** — елемент без дітей
- **:is()** — групування селекторів (новіший синтаксис)


### Оформлення переповнення:
- **overflow**: visible | hidden | scroll | auto 

| Значення  | Опис                                                                 |
|-----------|----------------------------------------------------------------------|
| `visible` | 🔹 **За замовчуванням.** Вміст виходить за межі контейнера і **видимий**. |
| `hidden`  | 🔒 Вміст, що виходить за межі, **обрізається** і **не видно**.        |
| `scroll`  | 📜 Завжди додає **прокрутку**, навіть якщо вона **не потрібна**.     |
| `auto`    | ⚙️ Додає **прокрутку лише при потребі**, якщо вміст **не вміщується**. |

### Типи елементів:
- **display**: block, inline, inline-block, none — управління відображенням елементів


### Налаштування "Гумові картинки":
- display: block;
- max-width: 100%;
- height: auto;

#### Альтернативний спосіб:
- display: block;
- max-width: 100%;
- height: 100%;
- object-fit: cover;

