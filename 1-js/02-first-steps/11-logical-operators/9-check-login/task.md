importance: 3

---

# Проверка логина

Напишите код, который будет спрашивать логин с помощью `prompt`.

Если посетитель вводит "Admin", то `prompt` запрашивает пароль, если ничего не введено или нажата клавиша `key:Esc` – показать "Canceled.", в противном случае отобразить "I don't know you".

Пароль проверять так:

- Если введён пароль "TheMaster", то выводить "Welcome!",
- Иначе – "Wrong password",
- При отмене – "Canceled".

Блок-схема:

![](ifelse_task.png)

Для решения используйте вложенные блоки `if`. Обращайте внимание на стиль и читаемость кода.

Подсказка: передача пустого ввода в приглашение возвращает пустую строку `''`. Нажатие клавиши `ESC` во время запроса возвращает`null`.

[demo]