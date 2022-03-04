# Intelligent Placer

## Постановка задачи
### Общее описание
Необходимо по поданной на вход фотографии одного или нескольких расположенных на листе бумаги предметов на фоне горизонтальной поверхности, и заданном на другом листе бумаги многоугольнику, определить, можно ли расположить одновременно все эти предметы на плоскости так, чтобы они влезли в этот многоугольник. Предметы и горизонтальная поверхность (фон), которые могут оказаться на фотографии, заранее известны

### Ввод \ вывод
Ввод: картинка предметов с многоугольником в формате .png без сжатия

Вывод: ответ "yes" \ "no" в текстовый файл answer_<имя поданой картинки на вход>.txt

## Требования
### Общие к фотографиям
- Многоугольник задавается фигурой, нарисованной красным маркером на белом листе бумаги, сфотографированной вместе с предметами
- Толщина нарисованной линии не превышает 5мм
- Фотографии сделаны с камеры расположенной перпендекулярно к поверхности, на высоте 35 сантиметров, при одинаковом освещении
- Предметы и поверхность должны быть равномерно и хорошо освещены - отсутствие пересвеченных и серо-черных областей
- На фотографии нет лишних предметов, кроме тех, которые заранее были известны
### К поверхности
- Горизонатльная (без выпуклостей и впадин)
- Однородная (без сильно выделяющихся объектов: узоров, пятен)
- Одна для всех фотографий
- Предметы распологаются на одном белом чистом листе бумаги
- Многоугольник нарисован на отдельном чистом белом листе бумаги, Лист бумаги с многоугольником всегда расположен справа от листа бумаги с предметами
- Листы с предметами и нарисованым многоугольником не пересекаются и не имеют общих границ
### К предметам на поверхности
- Предметы видны на листе бумаге
- Предметы не перекрывают друг друга
- Предметы не выходят на фон (т.е. предмет может не быть виден целиком на фотографии, но не может выходить на фон)
- Не имеют общих границ (т.е. предметы не могут лежать "впритык" к друг другу)

## Датасет
[Примеры](https://github.com/MekhailS/intelligent-placer/tree/dev/examples)
