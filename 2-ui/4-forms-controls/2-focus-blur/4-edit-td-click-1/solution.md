<ol>
<li>При клике -- заменяем `innerHTML` ячейки на `<textarea>` с размерами "под ячейку", без рамки.</li>
<li>В `textarea.value` присваиваем содержимое ячейки.</li>
<li>Фокусируем посетителя на ячейке вызовом `focus()`.</li>
<li>По `keydown` отслеживаем нажатие с `keyCode = 13` ([key Enter]) с `shiftKey` и трансформируем ячейку обратно.</li>
</ol>

[edit src="solution"]Открыть в песочнице[/edit]