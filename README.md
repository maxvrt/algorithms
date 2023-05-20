# Проектная работа. МБОУ АЛГОСОШ им. Фибоначчи

В проектной работе был создан визуализатор алгоритмов. Эта проектная работа заточена на анимацию и поэтапное отображение работы алгоритма, чтобы детальнее понять каждый шаг его работы. Цвета и раскадровка были представлены в фиде проекта дизайна в Figma.

## Ссылка

https://algorithms-delta.vercel.app/

## Строка

На этом экране разворачиваем строку.

Начальное состояние страницы

Введите текст в инпут и нажмите развернуть. 

**Визуализация**

Сначала на экране должно появиться слово, буквы которого записаны в синие кружки. 

Строка в исходном виде

Промежуточный этап разворота строки

---

## Последовательность Фибоначчи

На этом экране генерируется `n` чисел последовательности Фибоначчи. 

Перед тем как приступить к визуализации, на страницу надо добавить основные компоненты:

Начальное состояние страницы

Например, вы ввели 4, тогда на экране должен появиться ряд 1, 1, 2, 3, 5. 

Сгенерированная последовательность

---

## Сортировка массива

На этом экране визуализируются алгоритмы сортировки выбором и пузырьком

Начальное состояние страницы

**Визуализация**

Когда вы нажмёте «По убыванию» или «По возрастанию», должен запуститься процесс сортировки в зависимости от выбранного способа: выбором или пузырьком.

---

## Стек

На этом экране визуализируется удаление и добавление элементов в структуру данных стек

Начальное состояние страницы

**Визуализация добавления** 

Если ввести в инпут значение и нажать «Добавить», в стеке должен появиться первый элемент, который необходимо отрисовать на странице.

**Визуализация удаления**

Если нажать «Удалить», из стека должен извлекаться только верхний элемент. Удаляемый элемент выделяется цветом, надпись `top` перемещается на его левого соседа. 

---

## Очередь

На этом экране визуализировано удаление и добавление элементов в структуру данных «очередь».

Начальное состояние страницы

**Визуализация**

Если ввести в инпут значение 2 и нажать «Добавить», элемент должен отобразиться под индексом 0. Также добавьте на элемент указатели `head` и `tail`. Инпут при этом очищается.

Очередь с одним элементом

Очередь из трёх элементов в момент добавления

Очередь после `dequeue();`

---

## Связный список

На этом экране необходимо реализовать удаление и добавлениеэлементов в связный список. 

Начальное состояние страницы

### Визуализация

**При добавлении в head** элемент должен появиться над первым элементом вместо надписи head.

Добавление в head

Затем он занимает первое место в списке и на долю секунды выделяется зелёным цветом. Теперь над новым элементом написано head, и он указывает на предыдущий head-элемент.

Отображение нового элемента в head

Добавление по индексу. Поиск индекса

После успешного добавления 10 стоит под порядковым номером 2 и указывает на 34.

Добавление по индексу. Новый элемент в списке

Удаление элемента под индексом 2

**При удалении элемента из tail** кружок замещает надпись tail.

Удаление элемента из tail
