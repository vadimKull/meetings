Бот для команды и встреч
-----
Задачи бота:
Напоминании о звонках:
---
- При создании встречи бот присылает уведомление «Создано (Название звонка) 
- Бот за час до звонка присылает подобное смс: «(Название звонка) через час» 
- За 10 минут до звонка Бот присылает уведомление «(Название звонка) через 10 минут»
- В напоминании за 10 мин должна быть кнопка «Захожу». (Кнопка внутри интерфейса, в клавиатуре, не внутри смс)
- За 5 минут до встречи Руководителю осуществляется отправка сообщений на почту. Пуш длится 10 мин.
- «Встреча через 5 минут!»  это уведомление и последующие будут длится минуту, 120 напоминаний (в секунду по 2 смс)

Описание 
---
- «Встреча началась!» это напоминание будет длится 5 минут, также по 120 смс в минуту
- Каждое смс спама имеет срок жизнь 5 секунд
- После нажатия кнопки в любой момент, пуш останавливается, и удаляются все смс спама выше.
- В случае, если Руководитель не присоединился к звонку за 3 минуты до звонка Ассистенту осуществляется Пуш спама «Руководитель не зашёл на звонок!»

Напоминание о Днях рождения:
---
Бот парсит и мероприятия с почты, начинающиеся на “День рождение…”  отправляет напоминание Руководителю в 00:00 по МСК в формате «Сегодня (Название задачи)» с кнопкой «Поздравил”

