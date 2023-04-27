# Вопросы с собеседований для тестировщиков

[![Hexlet Ltd. logo](https://raw.githubusercontent.com/Hexlet/assets/master/images/hexlet_logo128.png)](https://hexlet.io/?utm_source=github&utm_medium=link&utm_campaign=ru-test-assignments)

This repository is created and maintained by the team and the community of Hexlet, an educational project. [Read more about Hexlet](https://hexlet.io/?utm_source=github&utm_medium=link&utm_campaign=ru-test-assignments).

See most active contributors on [hexlet-friends](https://friends.hexlet.io/).

----

## Как помочь?

Мы принимаем Pull Request'ы!

## Правила

* Для добавляйте вопросы с пояснениями

```html
<details>
<summary>Вопрос</summary>
Ответ/пояснение к вопросу
</details>
```

## Вопросы

<details>
<summary>Какие бывают требования?</summary>
По объекту требования:

* Функциональные – определяют действия, которые система должна быть способной выполнить
* Нефункциональные – определяют свойства, которые система должна демонстрировать, или ограничения, которые она должна соблюдать, не относящиеся к поведению системы
* По степени зафиксированности:

Явные или прямые – техническая документация, спецификация, юзер-стори, и т.д.
Неявные или косвенные – опыт, здравый смысл, стандарты
Производные – требования, вытекающие из явных требований
</details>

### Вопросы по теории тестирования, классификациям и видам тестирования

<details>
<summary>Что такое тестирование? Цель тестирования</summary>
</details>

<details>
<summary>Критерии начала и окончания тестирования</summary>
</details>

<details>
<summary>Что такое качество?</summary>
</details>

<details>
<summary>Разница между QA, QC и тестировщиком</summary>
</details>

<details>
<summary>Какие виды тестирования включает классификация по запуску кода?</summary>
статическое/динамическое.
</details>

<details>
<summary>Классификация по доступу к коду и архитектуре?</summary>
white/grey/black box
</details>

<details>
<summary>В чем отличие позитивного и негативного тестирования?</summary>
перечислите по несколько видов для позитивного и негативного тестрования
</details>

<details>
<summary>Что такое функциональное тестирование?</summary>
перечислите несколько видов
</details>

<details>
<summary>Что такое нефункциональное тестирование?</summary>
перечислите несколько видов
</details>

<details>
<summary>В чем отличие нагрузочного тестирования от стресс тестирования?</summary>
приведите по примеру на каждый вид
</details>

<details>
<summary>Как классифицируются виды тестирования по уровню?</summary>
Unit-тестирование, интеграционное, системное, приемочное
</details>

<details>
<summary>В чем отличие регрессионного тестрования от повторного?</summary>
</details>

### Вопросы по тестовой документации

<details>
<summary>Какие виды тестовой документации бывают?</summary>
Для чего и кем она используется?
</details>

<details>
<summary>В чем различия между тест-кейсом и чек-листом?</summary>
</details>

<details>
<summary>Что такое требования и для чего они нужны?</summary>
Перечислите атрибуты, которыми должны обладать требования
</details>

<details>
<summary>Что такое тест-дизайн и для чего он нужен?</summary>
Перечислите техники тест-дизайна?
</details>

<details>
<summary>Что такое дефект? Типы дефектов</summary>
</details>

<details>
<summary>Основные атрибуты баг-репорта</summary>
</details>

<details>
<summary>В чем отличие Severity от Priority?</summary>
Кто назначает каждый из параметров?
</details>

<details>
<summary>Результаты каких тестов приоритетнее?</summary>
</details>

<details>
<summary>Жизненный цикл баг-репорта (отчета о дефекте)</summary>
</details>

### Жизненный цикл ПО и этапы тестирования

<details>
<summary>Опишите жизненный цикл ПО</summary>
  Какова роль QA на каждом из этапов, и когда QA подключается к разработке?
</details>

<details>
<summary>Перечислите этапы жизненного цикла тестирования</summary>
</details>

<details>
<summary>Что такое методология разработки?</summary>
  Для чего она нужна?
</details>

<details>
<summary>Какие виды методологий разработки бывают?</summary>
  Назовите плюсы и минусы каждого вида
</details>

<details>
<summary>В чем отличие валидации от верификации?</summary>

* Верификация — проверка соответствия приложения прописанным требованиям.

* Валидация — проверка соответствия приложения всем остальным (подразумеваемым) требованиям.

  Например. Для входа на страницу веб-сайта, пользователю необходимо выполнить регистрацию или же войти в систему под своим аккаунтом.

  1. выполним верификацию: проверим наличие полей. Все поля должны быть валидными и соответствовать требованиям спецификации. Их количество, отображение и особенности определяются дизайнерами, которые создают макеты. Необходимые данные вносятся в техническое задание, а в случае отсутствия такового – необходимо иметь доступы к созданным макетам.
  При выполнении верификации необходимо понимать, что все поля изначально рабочие, и в них можно занести данные, согласно отображенным обозначениям и наименованиям.

  2. валидация: проверяются вводимые данные в поля информации, а также их соответствие утвержденной спецификации.
</details>

<details>
<summary>Что такое Agile?</summary>
</details>

### Опыт и рабочий процесс

<details>
<summary>Был ли коммерческий опыт QA?</summary>
  Если да, то что приходилось делать? Были ли действующие проекты с реальными пользователями?
  Если нет, то как ставились, выполнялись и проверялись задачи?
</details>

<details>
<summary>Почему именно QA?</summary>
QA - это интерес надолго или трамплин для чего-то большего?
</details>

<details>
<summary>Каким видится взаимодействие с разработчиками и менеджерами?</summary>
Если был опыт, поделитесь плюсами и минусами.
</details>

<details>
<summary>Опишите опыт работы до обучения/стажировки QA?</summary>
</details>

<details>
<summary>Какие инструменты используются для тестирования приложений?</summary>
</details>

### Тестирование веб-приложений

<details>
<summary>Что такое клиент серверная архитектура?</summary>
Клиент-серверная архитектура – это подход, при котором задания или сетевая нагрузка распределены между поставщиками услуг, называемыми серверами, и заказчиками услуг, называемыми клиентами. 

То есть клиент формирует запрос и отправляет его на сервер, после чего сервер обрабатывает данный запрос, формирует ответ и передаёт его обратно клиенту.
Один сервер может обрабатывать запросы от множества клиентов одновременно. 

В клиент-серверной архитектуре используется три компонента:
* Клиент — программа, c которой работает пользователь в браузере или с desktop-приложением и обеспечивает связь с сервером.
* Сервер — компьютер, на котором хранится сайт или приложение.
* База данных — хранилище данных, обеспечивающее сохранность данных, даже если в приложении что-то сломается.

Сервер может выполнять функции и приложения, и базы данных. Такая архитектура называется двухуровневой. 
</details>

<details>
<summary>Что такое HTTP и HTTPS?</summary>
Клиент и сервер общаются по правилам, то есть по протоколам. 
Для работы с сайтами используются два основных протокола: HTTP и HTTPS.

HTTP (HyperText Transfer Protocol) – протокол (или набор правил) передачи данных прикладного уровня модели TCP/IP.

HTTPS (HyperText Transfer Protocol Secure) — защищённый протокол передачи данных, работающий через шифрованные транспортные механизмы SSL (устарел в 2015г.) и TLS.

По умолчанию HTTPS использует 443 TCP-порт (для незащищённого HTTP используют TCP-порт 80). 

Основное отличие HTTP и HTTPS — шифрование данных. При использовании HTTP данные передаются в открытом виде, поэтому сайты, в основном, используют протокол HTTPS, который шифрует данные.

Протоколы HTTP и HTTPS описывают набор правил, в каком формате посылаются запросы от клиента, и что ожидается в ответ от сервера.

Каждое HTTP-сообщение состоит из трёх частей, которые передаются в указанном порядке:
* Стартовая строка (Request line) — определяет тип сообщения;
* Заголовки (Headers) — характеризуют тело сообщения, параметры передачи и прочие сведения;
* Тело сообщения (Body) — непосредственно данные сообщения. Обязательно должно отделяться от заголовков пустой строкой.

*Стартовая строка для запроса* включает в себя тип запроса, путь и версию протокола.
Например:
`HEAD / HTTP/1.0`

HEAD  — тип запроса (называют метод или «глагол», определяющий как реагировать на запрос);
/  - путь к ресурсу URI (в данном случае корень сайта);
HTTP/1.0 – версия протокола.

*Стартовая строка для ответа* представлена версией протокола, кодом состояния и пояснением к нему.

Например:
`HTTP/1.0 200 OK`

HTTP/1.0  – версия протокола;
200  – код состояния;
OK – пояснение.

*Заголовки* позволяют передавать дополнительную информацию, например браузеры предоставляют информацию о себе, чтобы было понятно откуда идет запрос. Кроме этого они указывают какие форматы сжатия поддерживают, в каком формате готовы принимать ответ и так далее. Количество стандартных заголовков достаточно большое, помимо них можно добавлять любые свои.
  Например:
* `Content-Type: text/plain; charset=windows-1251`
* `Content-Language: ru`

*Тело HTTP-сообщения* опционально.
Тело сообщения может быть добавлено в запрос, только когда метод запроса допускает тело объекта.
Тело сообщения в запросе сопровожается добавлением к заголовкам запроса поля заголовка Content-Length, в котором указывается длина тела запроса. 

Включается или не включается тело сообщения в сообщение ответа — зависит как от метода запроса, так и от кода состояния ответа. Все ответы на запрос с методом HEAD не должны включать тело сообщения, даже если присутствуют поля заголовка объекта (entity-header), заставляющие поверить в присутствие объекта. Никакие ответы с кодами состояния 1xx (Информационные), 204 (Нет содержимого, No Content), и 304 (Не модифицирован, Not Modified) не должны содержать тела сообщения. Все другие ответы содержат тело сообщения, даже если оно имеет нулевую длину.
</details>

<details>
<summary>Какие бывают виды методов HTTP (типы запросов)</summary>
Метод HTTP — последовательность из любых символов, кроме управляющих и разделителей, указывающая на основную операцию над ресурсом. 

Виды методов:
* *GET*
Используется для запроса содержимого указанного ресурса. С помощью метода GET можно также начать какой-либо процесс. В этом случае в тело ответного сообщения следует включить информацию о ходе выполнения процесса.
Клиент может передавать параметры выполнения запроса в URI целевого ресурса после символа «?»:
`GET /path/resource?param1=value1&param2=value2 HTTP/1.1`

* *HEAD*
Аналогичен методу GET, за исключением того, что в ответе сервера отсутствует тело. Запрос HEAD обычно применяется для извлечения метаданных, проверки наличия ресурса (валидация URL) и чтобы узнать, не изменился ли он с момента последнего обращения.

* *POST*
Применяется для передачи пользовательских данных заданному ресурсу. Например, в блогах посетители обычно могут вводить свои комментарии к записям в HTML-форму, после чего они передаются серверу методом POST и он помещает их на страницу. При этом передаваемые данные (в примере с блогами — текст комментария) включаются в тело запроса. Аналогично с помощью метода POST обычно загружаются файлы на сервер.

* *PUT*
Применяется для загрузки содержимого запроса на указанный в запросе URI. Если по заданному URI не существует ресурса, то сервер создаёт его и возвращает статус 201 (Created). Если же ресурс был изменён, то сервер возвращает 200 (Ok) или 204 (No Content). 
Фундаментальное различие методов POST и PUT заключается в понимании предназначений URI ресурсов. Метод POST предполагает, что по указанному URI будет производиться обработка передаваемого клиентом содержимого. Используя PUT, клиент предполагает, что загружаемое содержимое соответствует находящемуся по данному URI ресурсу.

* *PATCH*
Аналогично PUT, но применяется только к фрагменту ресурса.

* *DELETE*
Удаляет указанный ресурс.
</details>

<details>
<summary>Что такое код ответа HTTP?</summary>
Код состояний (код ответа) HTTP является частью ответа сервера. Он представляет собой целое число из трёх цифр. Первая цифра указывает на класс состояния. 
Клиент узнаёт по коду ответа о результатах его запроса и определяет, какие действия ему предпринимать дальше. Набор кодов состояния является стандартом, и они описаны в соответствующих документах RFC. 

В настоящее время выделено пять классов кодов состояния:
* 1хх – Информационный (Informational). Информирование о процессе передачи;
* 2хх – Успех (Success). Информирование о случаях успешного принятия и обработки запроса клиента;
* 3хх – Перенаправление (Redirection). Сообщает клиенту, что для успешного выполнения операции необходимо сделать другой запрос (как правило, по другому URI);
* 4хх – Ошибка клиента (Client Error). Указание ошибок со стороны клиента;
* 5хх – Ошибка сервера (Server Error). Информирование о случаях неудачного выполнения операции по вине сервера.
</details>

<details>
<summary>Что такое DNS? Как работает браузер?</summary>
DNS (Domain Name System или система доменных имён) - это автоматизированная система, которая связывает между собой доменное имя сайта, то есть его название, и IP-адрес — он нужен для «общения» компьютеров по сети. Благодаря DNS-серверу не нужно знать IP-адрес сайта, чтобы попасть на него.

Распределённая база данных DNS поддерживается с помощью иерархии DNS-серверов.
Система может работать внутри локальной и глобальной сетей. Когда компьютер посылает сообщение на другое устройство, то запрашивает IP-адрес получателя у DNS-сервера. 
Так это выглядит пошагово:
1.	Компьютер А_1 посылает запрос на DNS-сервер с просьбой сказать ему IP-адрес компьютера А_2
2.	DNS-сервер находит в записях компьютер А_2 и возвращает его IP-адрес на компьютер А_1
3.	Компьютер А_1 посылает информацию на адрес, который получил от DNS-сервера.

Рассмотрим, что такое браузер.
Браузер — это прикладное программное обеспечение, которое позволяет искать информацию в интернете, просматривать сайты, скачивать файлы любого формата, загружать аудио и видеофайлы.
Пошаговый механизм работы браузера:
1.	Пользователь открывает свой браузер и вводит адрес нужного сайта.
2.	Браузер ищет сервер.  Сначала - в кэше роутера, операционной системе или же в истории подключений, которая хранит информацию об IP-адреса сервера, если его уже посещали ранее. Если браузер там его не находит, он обращается к DNS.
3.	Браузер пытается установить соединение с сервером. Когда браузер нашёл нужный IP-адрес, он устанавливает с ним соединение с помощью специального протокола TCP/IP, который отвечает за передачу данных в интернете. 
4.	Браузер отправляет HTTP запрос на сервер. Таким образом он запрашивает информацию для того, чтобы отобразить страницу. Эта коммуникация осуществляется с помощью GET-запроса и POST-запроса.
5.	Сервер обрабатывает запрос и отправляет ответ браузеру. Сервер отправляет браузеру ответ с данными о файлах cookie, способах кэширования ну и, конечно же, контентом для отображения страницы.
6.	Браузер обрабатывает ответ и отображает запрашиваемый контент. Это называется рендерингом. Пока он происходит, браузер и сервер обмениваются данными. По завершении, пользователь видит загруженную страницу.
</details>

<details>
<summary>Что такое куки и кэш?</summary>
Куки (cookies) — это хранящиеся на компьютерах и гаджетах небольшие файлы, c помощью которых сайт запоминает информацию о посещениях пользователя.
Куки умеют запоминать:
1.	в какое время и с какого устройства человек заходил на страницу;
2.	предпочтения пользователей (например, язык, валюта или размер шрифта);
3.	товары, которые просматривались или добавлялись в корзину, даже если пользователь временно вышел из интернет-магазина;
4.	текст, который мы вводили на сайте раньше;
5.	IP-адрес и местоположение пользователя;
6.	дату и время посещения сайта;
7.	версию операционной системы и браузера;
8.	клики и переходы.

Выделяют два основных вида cookies:
* сессионные (временные) — данные о просмотренных страницах, записи форм заказов и другая информация, позволяющая клиентам упростить работу с сайтом. Существуют только в период времени, когда пользователь находится на сайте, и удаляются сразу же после прекращения сеанса, то есть вслед за тем, как закроется вкладка. После закрытия вкладки временные файлы автоматически удаляются;
* постоянные — хранят долгосрочную информацию в течение нескольких недель или месяцев, например логин от учётной записи. Они не удаляются после окончания взаимодействия с сайтом.

Кэш (cache) - это память программы или устройства, которая сохраняет временные или часто используемые файлы для быстрого доступа к ним. Это увеличивает скорость работы приложений и операционной системы. Процесс сохранения таких файлов в специальном месте называется кэшированием.
Типы кэш-памяти:
* аппаратная кэш-память — память системы. Свой кэш есть у жёсткого диска, графического ускорителя и процессора.
* программная кэш-память — это папки на диске устройства, в которых программы и сервисы сохраняют свои файлы для быстрого доступа. У каждой программы своя папка.
Размер программного кэша ограничивают, чтобы не ухудшалось быстродействие всей системы. Когда место заканчивается, то удаляется часть старой информации и записывается новая.
</details>

<details>
<summary>Что такое HTML и CSS?</summary>
  HTML (HyperText Markup Language) — это язык гипертекстовой разметки текста. Он нужен, чтобы размещать на веб-странице элементы: текст, картинки, таблицы и видео.
Когда вы заходите на сайт, браузер подгружает HTML-файл с информацией о структуре и контенте веб-страницы. HTML как бы выстраивает визуальный фундамент сайта, но не «запускает» сайт самостоятельно. Он всего лишь указывает, где располагаются элементы, какой у них будет базовый дизайн, откуда брать стили для элементов и скрипты.


CSS (Cascading Style Sheets) — это каскадные таблицы стилей. По сути — язык, который отвечает за описание внешнего вида HTML-документа. Подавляющее большинство современных веб-сайтов работают на основе связки HTML+CSS.

Таким образом, HTML структурирует контент на странице, а CSS позволяет отформатировать его, сделать более привлекательным для читателя.
</details>

<details>
<summary>Что такое API?</summary>
API (Application Programming Interface — программный интерфейс приложения, или интерфейс программирования приложений) — специальный протокол для взаимодействия компьютерных программ, который позволяет использовать функции одного приложения внутри другого.

Структуру интерфейса, как правило, рассматривают с позиций клиента и сервера.
API бывают 4 видов, каждый из которых предназначен для определённых целей и имеет свои особенности:
* SOAP API. Дословно переводится как «простой протокол доступа к объектам». Обмен информации между программой и сервером производится на языке XML. Сегодня он используется редко, так как существуют более гибкие интерфейсы.
* RPC API. Удаленный вызов процедур. Клиент запрашивает необходимое действие у сервера и получает ответ, что и приводит функцию приложения в исполнение.
* Websocket API. Очередная современная веб-версия. Для отправки информации клиенту или серверу применяется текстовый формат JSON. Особенность этого варианта API состоит в том, что у сервера есть возможность присылать сообщения обратного вызова, что повышает эффективность взаимодействия программ.
* REST API. Сегодня это самая востребованная версия. Программа присылает нужную информацию серверу, а тот в свою очередь производит выполнение встроенных функций и отправляет итоговые данные клиенту.

Примерами API может служить любая интеграция в сети: 
 - Быстрая регистрация на сайте через аккаунты социальных сетей и других сервисов. 
 - Сервис прогноза погода с актуальной информацией из внешний источников.
 - Сервис авиабилетов и т.п.
</details>

<details>
<summary>Каковы различия между идентификацией, аутентификацией, авторизацией?</summary>
  Идентификация — процедура, в результате выполнения которой для субъекта идентификации выявляется его идентификатор, однозначно определяющий этого субъекта в информационной системе. Проще говоря, сначала система запрашивает логин, пользователь его указывает, система распознает его как существующий — это и есть идентификация.

  Аутентификация — процедура проверки подлинности, например, проверка подлинности пользователя путём сравнения введённого им пароля с паролем, сохранённым в базе данных.

Авторизация — предоставление определённому лицу или группе лиц прав на выполнение определённых действий.
То есть предоставление пользователю право, например, читать письма в его почтовом ящике  — это авторизация.
</details>

### Задания

<details>
<summary>Покажи пример тест кейса</summary>
</details>

<details>
<summary>Покажи пример баг репорта</summary>
</details>
