1) Дан длинный текст, в нём встречаются слова длиннее 7 символов! Если слово длиннее 7 символов, то необходимо: оставить первые 6 символа и добавить звёздочку. Остальные символы вырезаются. Шаблон: "я купил бронетранспортер вчера" . Результат: "я купил бронет* вчера"

1) Необходимо вывести дату ближайшей доставки в формате: "30 ноября". Алгоритм следующий: если сегодня времени меньше, чем 20-00, то доставка завтра, если более 20-00, то послезавтра! Если день доставки попадает на праздничный день, то доставка переносится на следующий день после праздника. Праздники записываются в массиве в формате: "месяц-день": '01-01' - 1 января.

1) Создаём скрытую страницу "module=control" , в ней выводим весь массив куки и сессии. Добавляем 2 кнопки: "очистить куки" и "очистить сессию", которая должна выполнять указанные действия по нажатию. Кроме главного подраздела по управлению куки и сессией добавляем ещё 2: страницу с выводом phpinfo и страницу с выводом $_SERVER. Данный раздел защищаем паролем. Можно воспользоваться отдельной формой для входа, можно дать доступ админу сайта

1) Создаем массив координат 10х10, для этого подойдет любой многомерный массив по виду $array[y][x] = status , где status - доступность ячейки (если 1 - значит существует преграда и её необходимо обойти, 0 - можно проходить). Необходимо составить путь, как добраться из точки А в точку Б обходя преграды. Точки А и Б задаются произвольные: А ($a = array("x"=>2,"y"=>3);), Б ($b = array("x"=>9,"y"=>1);). Важное примечание, необходимо генерировать поле (10х10 или иное) при первом запуске скрипта, после массив сохраняется в БД или в ФАЙЛ для дальнейшей работы с ним. Цель - найти самый короткий путь.

1) Есть строка: {Пожалуйста,|Просто|Если сможете,} сделайте так, чтобы это {удивительное|крутое|простое|важное|бесполезное} тестовое предложение {изменялось {быстро|мгновенно|оперативно|правильно} случайным образом|менялось каждый раз}. Необходимо раскрыть фигурные скобки и получить строку. | значит, что допустимо одно из указанных значений, то есть {крутое|простое} значит, что выведется ТОЛЬКО крутое или ТОЛЬКО простое. Вложенные фигурные скобки так же должны раскрываться, значит: {простое|очень {сложное|удачное}} в итоге получим на выходе один из трёх вариантов: "простое", "очень сложное", "очень удачное". Важно, что вложенность может быть бесконечной. Сюда же добавлю, что есть вторая интерпретация этой задачи, необходимо составить массив со всеми возможными вариантами строки, то есть не случайное раскрытие, а все допустимые варианты.

1) Есть длинный текст и есть форма поиска по этому тексту. При вводе слова в форму поиска необходимо найти все упоминания этого слова в тексте и выделить (подсветить) цветом, жирным или другим настраивающим способом. В случае, если указываются 2 слова, то каждое должно искаться индивидуально, если словосочетание указывается в кавычках,то ищется как единое словосочетание. Помимо грубого поиска так же должно находить слова с разными окончаниями: пиво, пива, пивом.
