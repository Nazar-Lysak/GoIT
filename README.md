# 👩‍🏫 Заняття 9: Форми і таблиці

## 🎯 Ціль заняття
- Ознайомитись з основними HTML-тегами для створення форм
- Розібрати атрибути форм та їх поведінку
- Навчитись працювати з валідацією та псевдокласами
- Продовжити роботу над проєктом, додавши форми

---

## 📌 1. Вступ
**Що розглянемо:**
- Теги `form`, `label`, `input`, `textarea`, `select`, `fieldset`, `optgroup`, `datalist`
- Атрибути: `type`, `name`, `placeholder`, `checked`, `required`, `disabled`, `autofocus`, `minLength`, `maxLength`, `step`, `value`, `min`, `max`
- Псевдокласи: `:focus-within`, `:placeholder-shown`, `:checked`
- Стилизування `textarea` — властивість `resize`

---

## 🙋‍♂️ 2. Відповіді на питання студентів
(з файлу питань — буде заповнюватись на уроці)

---

## 🧩 3. Продовження проєкта

### 📄 Базові теги форм:
| Тег       | Призначення |
|-----------|-------------|
| `<form>`        | Контейнер для форми |
| `<label>`       | Підпис до елемента форми |
| `<input>`       | Поле вводу (вказується тип через `type`) |
| `<textarea>`    | Багаторядкове текстове поле |
| `<select>`      | Випадаючий список |
| `<optgroup>`    | Група опцій у `<select>` |
| `<datalist>`    | Варіанти підказок до `<input>` |
| `<fieldset>`    | Групування пов’язаних елементів форми |

---

### ⚙️ Важливі атрибути `input`:
| Атрибут       | Пояснення |
|---------------|-----------|
| `type`        | Тип поля (див. нижче) |
| `name`        | Ім’я поля (важливо для обробки даних) |
| `placeholder` | Підказка у полі |
| `checked`     | Встановлює обране значення (для `checkbox`, `radio`) |
| `required`    | Поле обов’язкове для заповнення |
| `disabled`    | Поле вимкнене |
| `autofocus`   | Фокус при завантаженні сторінки |
| `min`, `max`, `step`, `value` | Для числових полів |
| `minLength`, `maxLength` | Для текстових/парольних полів |

---

### ⌨️ Типи `input`:
```html
<input type="text">
<input type="email">
<input type="checkbox" checked>
<input type="radio" name="choice">
<input type="number" value="0" min="18" max="120" step="0.5">
<input type="date">
<input type="time">
<input type="datetime-local">
<input type="tel">
<input type="password" minLength="6" maxLength="20">
```
## 🔹 Додаткові ресурси 📚
- 🖼 [dashly-theme](https://dashly-theme.com/account.html) – приклад використання форм  
- 🖼 [ant.design](https://ant.design/components/overview/) – одна з популярних js бібліотек з різними компонентами  


