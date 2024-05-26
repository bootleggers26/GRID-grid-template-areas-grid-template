**grid-template-areas** - определяет шаблон сетки ссылаясь на _имена областей_, которые заданы с помощью свойства **grid-area**.

Повторение названия области приводит к тому, что содержимое охватывает эти ячейки.

Точка означает _пустую ячейку_.

Синтаксис предоставляет _визуализацию_ структуры сетки.

![grid-area-example](/pic/Grit%20Area.png)

Если мы добавим код медиа запроса `@media screen and(max-width:500px)` с шириной экранов 500px соответственно мы получим сетку, которая при уменьшени своего размера, **автоматически будет сдвигаться**, до тех пор пока не станет столбцом.

![grid-area-example](/pic/grid%20area%20media.png)
