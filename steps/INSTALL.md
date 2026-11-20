# Подключение Далисмана — по одному шагу

**Для ChatGPT:** эта таблица — внутренний маршрут, **не выводи её целиком владельцу**. На каждом ответе объясняй только одно действие, показывай или приводи прямую ссылку **только на иллюстрацию текущего шага**, проси «Готово». Текущий разговор с помощником не закрывай. Не начинай с Ctrl + T. Используй прямую ссылку на раздел плагинов. Не ищи заменяющих изображений в интернете.

Все ссылки ниже ведут на уже загруженные изображения GitHub.

| Шаг | Единственное ближайшее действие | Образец | Проверка |
|---|---|---|---|
| 1 | Нажать [**Открыть раздел Плагины**](https://chatgpt.com/plugins). Сохранить текущий разговор; если ссылка открылась в этой же вкладке — вернуться и открыть ссылку в новой вкладке через контекстное меню. | [Раздел Плагины](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/03-plugins-add-menu.png) | Открылся раздел «Плагины» |
| 2 | Открыть **Личные** и посмотреть «Установленные» и «Созданные вами». | [Список плагинов](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/03-plugins-add-menu.png) | Понятно, есть ли Далисман |
| 4a | **Если Далисман установлен:** не создавать повторно — перейти к шагу 11 или проверить `analytics_catalog`, если инструмент уже доступен. | [Установлен](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/09-installed.png) | Плагин установлен |
| 4b | **Если создан, но рядом +:** нажать +, затем «Подключить Далисман», перейти к шагу 9. | [Повторное подключение](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/12-reconnect.png) | Открылся экран авторизации |
| 4c | **Если Далисмана нет:** справа сверху «Добавить» → «Добавить пользовательский сервер MCP». | [Меню добавления](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/03-plugins-add-menu.png) | Открылась форма |
| 5 | Заполнить название **Далисман**, описание **Аналитика салона красоты**, URL `https://elklp.ru/api/mcp`, аутентификация **OAuth**. | [Основные поля](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/04-server-form.png) | Поля заполнены |
| 6 | Открыть «Расширенные настройки OAuth» и проверить **Динамическая регистрация клиента (DCR)**. Поля Client ID и Client Secret оставить пустыми. | [DCR](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/05-oauth-dcr.png) | DCR выбран |
| 7 | Проверить адрес, отметить «Я понимаю и хочу продолжить», нажать «Создать в виде плагина». | [Создание](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/06-create-plugin.png) | Окно Далисмана |
| 8 | Нажать «Подключить Далисман». | [Подключить](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/07-connect-dalisman.png) | Открывается `elklp.ru` |
| 9 | Выбрать собственные организации в «Показатели бизнеса» (при необходимости и «Оформленные записи и источники новых клиентов»), затем «Разрешить чтение». | [Разрешения](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/08-consent.png) | Возврат в ChatGPT |
| 10 | Проверить Далисман среди «Установленные». | [Проверка установки](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/09-installed.png) | Установлен |
| 11 | **Только во второй вкладке** «Попробовать сейчас» либо новый чат и `@Далисман`. | [Поле запроса](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/10-first-prompt.png) | Выбран Далисман |
| 12 | Отправить: «Покажи, как прошла последняя неделя в моём салоне. Сравни с предыдущей и расскажи простыми словами». | [Пример результата](https://raw.githubusercontent.com/Dmrs1977/dalisman-chatgpt-setup/main/screenshots/11-first-report.png) | Есть отчёт с реальными цифрами |

**Внимание:** скриншоты иллюстрируют конкретные состояния интерфейса. На некоторых показано несколько элементов. Не выдавай их за полностью идентичный экран пользователя. Кнопку «Новый чат» нельзя нажимать в первой вкладке.

Если при входе в Далисман потребуют логин и пароль — пользователь вводит их **только на сайте Далисмана**, не в диалоге. Если пункта добавления MCP нет, зафиксируй это и попроси скриншот.

Когда пользователь уже в чате с Далисманом, продолжи сценарий [первого отчёта](FIRST_REPORT.md).
