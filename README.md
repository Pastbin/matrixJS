# matrixJS

Плагин для эффекта матрицы на javascript.

## Установка

Разместите скрипт в любом месте документа.  
Укажите атрибут data-matrix="20" на элементе (больше = медленно, меньше = быстро).  
Внутри элемента не должно быть других тегов. Кроме **br, b**. И возможно другие. Экспериментируйте! :)

```html
<!doctype html>
<html lang="en">
<head>
    ...
</head>
<body>
<section>
    <h2 data-matrix="30" class="title">Lorem ipsum dolor.</h2>
    <div data-matrix="20" class="description">Lorem ipsum dolor sit amet, consectetur adipisicing.</div>
</section>
<script src="matrix.js"></script>
</body>
</html>
```

### Стили

На элементе, с эффектом матрицы пропишите следующие стили: (пример)  
--matrix: 'цвет букв'  

```css
.title{
    color: rgba(0,0,0,0);
    --matrix: #f0f;
}
.description{
    color: rgba(0,0,0,0);
    --matrix: rgb(145,90,5);
}
```

Желаю удачи!