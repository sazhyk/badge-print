# Небольшое веб-приложение для печати бейджиков

Писалось строго для себя и под конкретные нужды. Должно уметь добавлять на страницу до 8 бейджиков и удалять случайно добавленные, сохроанить их в pdf.

## Примерный алгоритм работы:

1. Пользователь захотит на адрес ресурса.

2. Нажимает кнопку "Добавить бейдж" столько раз, сколько бейджей желает заполнить и распечатать.

3. Кликом по месту на бейдже, где должно быть изображение сотрудника, выбирает на на компьютере изображение сотрудника в открывшемся диалоговом окне.
При этом, скрипт преобразовывает изображение в base-64 на лету и пользователь видит превью выбранного изображения.

4. Затем пользователь заполняет соответствующие поля с Ф И О на бейдже.

5. Помле этого наживает кнопку "Сохранить документ", и на его компьютер скаживается *.pdf файл с бейджами. Файл после этого печатается на принтере.

## Что надо сделать?

Добавить на страницу кнопку "Добавить бейдж", которая добавит бейджик на страницу.

Добавть кнопку "Удалить последний бейдж", которая понятно что делает.

Самое главное - реализовать возможность добавления к каждому бейджу изображения.
