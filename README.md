# grid-lesson

grid-template-columns - длинна строк
grid-template-rows - высота колонок(задается конкренто каждой)
grid-auto-rows - высота колонок по умолчанию(задается для всех по умолчанию)
grid-column-gap - отступ между колонками(справа)
grid-row-gap - отступ между строками (Снизу)
grid-gap - одновременный отступ между колонками и строками
grid-template-columns: repeat(4, 1fr) - = 4 раза 1fr
grid-template-columns: minmax(100px, 200px) repeat(3, 1fr) - можно задать диапазон для колонки
grid-auto-rows: minmax(90px, auto)
grid-auto-flow - по умолчанию row, можно column
grid-column-start: 2 - переносит на 2 позицию колонки(вправо)
grid-row-start: 2 - переносит на 2 позицию строки(вниз)

grid-column-start: 1;
grid-column-end: 3;
// grid-column-end: -1; -1 - это до конца\*\*\*
От 1 до 3 линии растягивам элемент в колонке (вправо)

grid-column: 1 / -1; - сокращенная запись

justify-items: start; - элемент центрируется по горизонтали по контеньту start, center, end

align-items: start; - элемент центрируется по вертикали по контеньту start, center, end

align-self: start; для 1 элемента по горизонтали

justify-self: start; для 1 элемента по вертикали
