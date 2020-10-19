# Офіційний посібник для модератора вільних кодів.

Це допоможе вам модерувати різні місця в нашій спільноті, у тому числі:

- Проблеми на GitHub & pull запитів
- Форум, чати кімнати, групи Facebook та інші онлайн місця для зустрічей
- У людини такі заходи, як навчальні групи, хакатони та конференції

**Всі модератори freeCodeCamp є загальнодержавними модераторами. А це значить, що ми довіряємо вам переглянути будь-яке з цих місць.**

Це означає, що ви можете служити модератором, в яких місцях найбільше цікавить вас. Деякі модератори просто допомагають на GitHub. Інші - допоможіть на форумі. Деякі модератори активні всюди.

Суть у тому, що ви хочете насолоджуватись модератором, та відзначайте свій дефіцитний час у місцях, які вас цікавлять.

> [!NOTE] "З великою силою приходить велика відповідальність." - Дядько Бен

Як модератор, темперамент важливіший, ніж технічний навик.

Слухати. Будь корисною. Не зловживай своєю силою.

freeCodeCamp - спільнота, і ми повинні залишити її таким чином.

У нас є єдиний код, який керує всім нашим громадою. Чим менше правил, тим легше їх запам'ятати. Ви можете прочитати ці правила і затвердити їх до пам'яті [тут](https://code-of-conduct.freecodecamp.org).

# Moderating GitHub

Модератори мають можливість закрити питання і прийняти або закрити пулл-реквести.

Модератори мають дві основні обов'язки щодо GitHub:

1. QA'ing і злиття злиття злиття запитів
2. Оцінка та відповідь на питання

## Модерування запитів на злиття

Запит на злиття (PRs) визначає, як вкладники вносять зміни у репозиторій freeCodeam. Важливо, щоб ми виконували функцію забезпечення якості (QA) на pull запитах, перш ніж ми вирішили, чи їх об'єднати чи закрити їх.

### Види запитів на злиття

1. **Киснева інструкція редагує** Це зміни у тексті викликів - Опис, інструкції або Тестування тексту. Ви також можете переглянути це прямо на GitHub і вирішити, чи їх об'єднати. Ми повинні бути трохи обережнішими з цим, тому що мільйони людей зіткнуться з цим текстом у безкоштовній програмі CodeCamp. Чи робить запит на злиття більш зрозумілим, не роблячи текст значно довшим? Чи є зміни актуальними та не надто педантичними? Пам'ятайте, що наша мета полягає в тому, щоб виклики були настільки чіткими та якомога коротшими. Це не місце для незрозумілих деталей. Крім того, учасники можуть додавати посилання на ресурси для викликів. Ви можете закрити ці запроси на злиття і відповісти на них так:

   > Дякуємо за ваш запит на злиття.
   > 
   > Я закриваю цей запит на злиття. Будь ласка, додайте посилання та інші деталі до відповідної статті посібника задачі.
   > 
   > Якщо ви думаєте, що я не в тому, що закриваю цю проблему, повторно відкрийте її і додайте подальше уточнення. Дякую та щасливе кодування.

2. **Challenge Code Редагує** Ось зміни в коді - Лист - Кисло, Киньте виклик вирішити та Тестові рядки. Ці запроси злиття необхідно витягнути з GitHub і протестувати на вашому локальному комп'ютері, щоб переконатися, що тести все ще можуть бути прийняті з поточного рішення та новий код не містить жодних помилок. Деякі учасники можуть спробувати додати додаткові тести, щоб покрити педантичні кейси кутів. Нам потрібно бути обережними, щоб не робити виклик занадто складним. Ці виклики та їх тести повинні бути настільки ж простими та інтуїтивними, як це можливо. Окрім алгоритмів викликів та попереднього розділу інтерв'ю, учні повинні мати можливість вирішити кожне завдання протягом приблизно 2 хвилин.

3. **Змінення коду змінюється** Цей код змінює функціональність самої платформи freeCodeCamp. Іноді розробники намагаються вносити зміни без особливих пояснень, але для того, щоб зміни в коді ми повинні впевнитися, що є справжня потреба у змінах. Таким чином, ці запроси на злиття мають посилатися на існуючу проблему з GitHub, де причини для змін обговорюються. Потім ви можете відкрити запит на злиття на своєму комп'ютері і перевірити його локально. Після того, як ви зробили це, якщо зміни виглядають добре, не об'єднайте їх повністю. Ви можете прокоментувати pull-запит, кажучи "LGTM", а потім згадати @raisedadead, щоб він міг поглянути на останній погляд.

### Як об'єднати або закривати pull запитів

Спершу, коли ви вибираєте pull request до QA, ви повинні призначити себе ними. Ви можете зробити це, натиснувши на посилання "призначити себе" під "виконавець" на правій колонці інтерфейсу GitHub.

Залежно від типу pull-запиту це виконуються відповідні правила, перелічені вище.

Перед тим, як об'єднати будь-який запит на злиття, переконайтеся, що GitHub має зелені позначки для всього. Якщо є які-небудь х, спочатку розслідувати їх і з'ясувати, як їх перетворили на зелені позначки спочатку.

Іноді буде Конфлікт об'єднання. Це означає, що інший запрос на злиття зробив зміну до тієї ж частини того ж самого файлу. У GitHub є інструмент для вирішення цих конфліктів злиття прямо на GitHub. Ви можете вирішити ці конфлікти. Просто дістайтесь найкраще рішення. Зміни на злиття будуть зверху, а зміни на головну гілку будуть знизу. Іноді тут буде надлишкова інформація, яку можна видалити. Before you finish, be sure to delete the `<<<<<<`, `======`, and `>>>>>>` that Git adds to indicate areas of conflict.

Якщо запит на злиття готовий до злиття (і не вимагає затвердження від @raisedadead), ви можете перейти вперед і перейти на злиття його. Переконайтеся, що ви використовуєте типові можливості "Squash та Merge" на GitHub. Це складе всі pull запитів коміти в один коміт, що значно полегшує читання історії Git.

Потім потрібно коментувати pull request, подякувати вкладу Ваш особистий спосіб.

Якщо автор запиту на злиття є "перший учасник", вам слід також привітати їх з першим злиттям запиту на репозиторій. Ви можете подивитися на верхній правий куточок тіла PR, щоб визначити першочергового виконавця.  Це покаже `першочерговий учасник` як показано нижче:

![Copy_edits_for_Java_arrays_article_by_karentobo_%C2%B7_Pull_Request__20615_%C2%B7_freeCodeCamp_freeCodeCamp|690x281](https://i.imgur.com/dTQMjGM.png)

Якщо запит на злиття не готовий до ввічливо відповісти, що повинен зробити, щоб він мене приготувався. Сподіваюсь, вони відповістимуть і підтягнуть запит ближче до готовості.

Часто запит на злиття буде очевидно низькими зусиллями. Ви часто можете відразу сказати це, коли автор не перевіряв прапорці Pull Request, або використано заголовок універсального пулл-запиту, як "зроблені зміни" або "Оновити індекс. д".

Також є ситуації, коли автор намагається додати посилання на свій сайт, або включаючи бібліотеку, яку вони самі створили, або має легковажний відредагування, який не допомагає нікому, окрім самих себе.

В обох ситуаціях вам слід закривати запит на злиття і відповісти стандартним повідомленням:

> Дякуємо за відкриття цього запросу.
> 
> Це стандартне повідомлення повідомляє вам, що ми переглянули ваш запит на злиття і вирішили не об’єднати його. Ми будемо раді вашим майбутнім запитам на злиття.
> 
> Дякую і щасливе кодування.

Якщо вам потрібна друга думка щодо pull request, залиште коментарі на pull request, а потім додати позначку "обговорювати" до пулл-реквесту.

## Модерування задач на GitHub

freeCodeCamp є активним проектом з відкритим вихідним кодом. Ми отримуємо нові задачі кожного дня, і все потрібне для вирішення та напруженості.

### Види задач на GitHub

1. **Запит про допомогу по коду**, на які люди помилково створили проблеми з GitHub. Якщо хтось просить допомоги, вставте наступне повідомлення, тоді закрийте проблему.

   > Дякуємо, що повідомили про цю проблему.
   > 
   > Це стандартне повідомлення, яке повідомляє вам, що ця проблема здається проханням допомогти. Замість того, щоб запитувати про допомогу тут, будь ласка, натисніть \*"Допомога"\*** на кнопку виклику freeCodeCamp, що допоможе вам створити питання у правій частині форуму. Волонтери на форумі зазвичай реагують на питання протягом декількох годин і можуть допомогти визначити, чи є проблема з вашим кодом або тестами на ваших задачах.
   > 
   > Якщо учасники форуму визнають що немає нічого поганого в своєму коді, ви можете запросити цю проблему для повторного відкриття. 
   > 
   > Дякую і щасливе кодування.

2. **Проблема з роз'ясненням або помилками** Спробуйте відтворити помилку самостійно, якщо зможете. Якщо ні, попросіть в них кроки відтворити жук, і чи є у них якісь скріншоти, відео або додаткові деталі, що можуть допомогти Вам відтворити проблему. Після того, як ви зможете відтворити задачу - або принаймні підтвердіть, що це задача - позначіть її `підтверджену`. Інша:

- Якщо це просте змінення на існуючий виклик, позначку `як <code> перші таймери`, в іншому випадку позначку на `допомогти`. Використовувати інші мітки як належне.
- Якщо проблема більш значна, позначте її `помилка`. &nbsp; Якщо існує двозначність щодо правильного курсу дії, ви можете помітити @raisedadead на проблемі, отримати свій власний погляд, а потім додати позначку `обговорення`.

3. **Дублювання проблем** Якщо проблема така ж як інша повідомлена проблема, попередня проблема повинна мати перевагу. Позначте `Дублікати`, вставте таку заміну повідомлення `#XXXXX` з номером проблеми та закрийте проблему.

   > Дякуємо, що повідомили про цю проблему.
   > 
   > Це стандартне повідомлення, яке повідомляє вам, що ця проблема дуже схожа на проблему #XXXXX, так що я закриваю її як копію.
   > 
   > Якщо ви думаєте, що я не в тому, що закриваю цю проблему, повторно відкрийте її і додайте подальше уточнення. Дякую і щасливе кодування.

4. **Виправлено у постановці** Деякі проблеми можуть бути виправлені на стадії, але в них немає проблеми з GitHub. Якщо у цьому випадку, ви можете вставити такі повідомлення, закрити це питання та додати статус `: вирішений/адреса` мітка:

   > Дякуємо, що повідомили про цю проблему.
   > 
   > Це стандартне повідомлення повідомляє про те, що проблема, яку ви згадали тут, присутня у виробництві, але це вже зафіксовано у постановці. Це означає, що наступного разу ми висуваємо гілку постановки до виробництва, цю проблему слід виправити. Через це я закриваю цю проблему.
   > 
   > Якщо ви думаєте, що я не в тому, що закриваю цю проблему, повторно відкрийте її і додайте подальше уточнення. Дякую і щасливе кодування.

### Закриття стадії, застарілі, неактивні проблеми та Pull запити

- Старі питання або ПР, які не бачили жодної діяльності в ОП протягом 21 днів (3 тижні з останньої діяльності), але лише після того, як модератор запитав більше інформації/змін.  Вони можуть бути закриті в автоматичному скрипті / боті або самі модератори.

- Діяльність визначається: Коментарі що запитують оновлення на PR і племена, такі як `статус: оновлення необхідної` мітки і т. д.

- Якщо ОП попросить додаткової допомоги або навіть часу, вище може бути розслаблений і переглянутий після наданої відповіді. У будь-якому випадку моди повинні використовувати своє найкраще рішення для вирішення видатного статусу PR.

### Інші рекомендації для модераторів на GitHub

Хоча ви будете писати доступ до безкоштовного репозиторію CodeCampy, **ви ніколи не повинні відправляти код безпосередньо для репозиторіїв freeCodeCamp**. Усе значення коду має ввести у довільну базу коду у вигляді запиту на злиття з репозиторію.

Крім того, ви ніколи не повинні приймати власні PR. Вони повинні бути QA'd іншим модератором, як і будь-який інший PR.

Якщо ви помітили, як хтось порушив [код перекладу](https://code-of-conduct.freecodecamp.org) на GitHub або відкрити запити на злиття із шкідливим вмістом або кодом, надішліть dev@freecodecamp. rg з посиланням на образливий пулл-реквест, і ми можемо розглянути можливість повної заборони йому в організації freeCodeCamp.

# Модерування форуму

Як модератор, ви допомагаєте нашій спільноті знайти приємне місце для всіх, щоб вчитися і отримати допомогу. Ви маєте справу з відзначеними повідомленнями та оброблятимете спам, з будь-якої теми та інші невідповідні розмови.

Зверніть увагу, що як тільки ви модератор форуму, ви почнете бачити підказки для синього модератора щодо учасників форуму, Наприклад, "це перший раз [person] опублікував(ла) - давайте привітаємо їх до спільноти! або "[person] не розмістили довго - давайте повернемось назад."

![Блакитне текстове повідомлення, в якому говорить "це перший раз [person] опублікували - давайте привітаємо їх до спільноти!](https://i.imgur.com/mPmVgzK.png)

Це можливості для вас, щоб вітати їх, і змусити їх почувати себе особливими. Ви ніколи не знаєте, яка людина, яка яка активно залучена може стати нашим наступним суперпомічником, допомагаючи багатьом іншим в дорозі з кодування. Навіть найменша доброта може викликати каскад добрих справ.

### Видалення повідомлень форуму

Модератори форуму можуть видаляти повідомлення користувача. Ви повинні зробити це лише для наступних екземплярів:

1. Хтось розмістив зображення порнографічної або графічно насильницької роботи.
2. Хтось розмістив посилання або код, який є шкідливим у природі і міг зашкодити іншим верблюдам, які клацнули по ній.
3. Хтось затопив тему великою кількістю спам-повідомлень.

### Запит зі спамом

Для першого спам-повідомлення користувача, надішліть їм повідомлення, що пояснює проблему, і видаліть посилання або повідомлення з відповідним записом. Залиште нотатку в профілі користувача, що пояснює дію, яку ви зробили. Якщо проблема повторюватиметься, тоді виконайте процес вище. Беззвучно заблокувати користувача додавання (використовуючи опцію тиші на панелі адміністратора користувача), а потім надіслати попередження з Кодом Поведінки. Відмітьте прапорець в приватному повідомленні, що означає, що ваше повідомлення — це "офіційне попередження."

Інциденти і повідомлень можна задавати питання і повідомляти в розділі [Співробітники](https://forum.freecodecamp.com/c/staff).

### Справа з відключеними бесідами

Пости або теми, які, здається, знаходяться в неправильному місці, можуть бути повторно категоризовані або перейменовані на те, що було б доречним.

За винятковими обставинами модератор може породити дискусію в кілька ниток.

Знову ж таки, якщо у вас є будь-які проблеми або питання, напишіть свої дії в категорії співробітників, і відмітьте іншого модератора, якщо бажаєте, щоб вони переглядали ваші модераційні дії.

### Застарілі користувачі

Наші Умови Надання Послуг вимагають від користувачів довільного CodeCamp не менше 13 років. У випадку виникнення користувача що він молодший 13 років, надішліть їм нижче повідомлення і видаліть їх обліковий запис на форумі (якщо видалення недоступне, зупинити достатній обліковий запис). Далі [Quincy](https://forum.freecodecamp.org/u/QuincyLarson) (quincy@freecodecamp.org) або [Mrugesh](https://forum.freecodecamp.org/u/raisedadead) (mrugesh@freecodecamp.org) щоб видалити обліковий запис користувача freeCodeCamp також .

```markdown
SUBJECT: Користувачам у віці до 13 років заборонено користуватися форумом через умови використання

. На нашу увагу дійшло не більше 13 років. В одній з [freeCodeCamp термінів](https://www.freecodecamp.org/news/terms-of-service), ви повинні мати принаймні 13 років, щоб використовувати сайт або форум. Ми будемо видаляти ваш безкоштовний обліковий запис CodeCamp і ваш обліковий запис форуму. Це обмеження обмежує нас у відповідності законам Сполучених Штатів.

Будь ласка, повторно приєднайтеся до принаймні 13 років.

Дякую за розуміння.
```

# Модерування Facebook

Якщо ви бачите що-небудь, що зламає наш [Код поведінки](https://code-of-conduct.freecodecamp.org/), ви повинні видалити його негайно.

Іноді люди поміщують речі, які, на їхню думку, смішні. Вони не розуміють, що те, що сказали вони чи те, що спільний їх можна трактувати як наступне. У цих випадках потрібно видалити їх повідомлення, але особа, яка його розміщує, не обов'язково забанена. Сподіваюсь, вони зрозуміють що розміщені повідомлення є недоречним.

Але якщо це кричущий образ, який не можна обґрунтовано віднести до культурної різниці чи нерозуміння англійської мови, тоді ви повинні розглянути можливість блокування учасника від групи у Facebook.

# Модерувати Discord

Ось як модератори стикаються з порушеннями нашого [коду поведінки](https://code-of-conduct.freecodecamp.org/) у Discord:

1. **Переконайтеся, що він призначений для порушення Кодексу Поведінки.** Не всі порушення КК були призначені як такі. Новий табір може відправити велику кількість коду для допомоги, не усвідомлюючи, що це можна вважати спамуванням. У цих випадках ви можете просто попросити їх вставити їхній код сервісами на кшталт Codepen або Pastebin.

2. **Якщо табір явно порушує кодекс поведінки, модератор продовжиться наступним чином:**

- Призупиніть верблюда, але не попереджай і не загрожуй їм. Натомість надайте їм підозрілу роль у Discord, а потім надішліть їм такі повідомлення:

```
Це стандартне повідомлення повідомляє вас, що я повинен був тимчасово призупинити вас для розмови з сервером freeCodeCamp Discord.

Я модератор, який діяв від імені нашої спільноти з відкритим вихідним кодом. Я можу видалити вашу напругу, але вам потрібно, щоб ви зробили наступні 3 кроки спочатку:

1. Прочитайте наш Код поведінки: https://code-of-conduct.freecodecamp.org/
2. Надішліть мені наступне твердження, що ви закінчили його читати.
3. Поясніть мені, чому ви думаєте, що я призупинив вас, і чому мені слід зняти вашу напругу.
```

- Повідомити про короткий огляд події та про те, як вони відповіли на нього у каналі #адміністратора. Ось приклад того, як може виглядати таке резюме:

```
Призупинено: _@username_
Reason(s): _Spamming, trolling_
Розділ: _Один або більше посилань на образливі повідомлення(и)_
Co: _Sent_
```

- Звіт про видалення підвіски повинен виглядати так:

```
Я видалив призупинення з ` @username `. Я надіслав їм Кодекс поведінки. Вони на сьогодні зрозуміли, що їх призупинено і вибачились за те, що вони зробили.
```

- На підставі правопорушників, модератор вирішить, чи видалити призупинення з образливого кампера. Якщо вони виглядають шанобливо і вибачливими, модератор зможе зняти призупинення. Як питання політики, модератори будуть ввічливі під час цього процесу, незалежно від того, наскільки погано поводився табір, що ображається. Якщо вони не є шанобливим або не бажають приймати CoC, за цим слід слідкувати призупинення з баном на Discord сервері. Використайте такий самий підсумок, що і вище, але замініть "Призупинено:" на "Забанений:".

3. **Як забанити та/або розблокувати**

- Щоб забанити когось, клацніть правою кнопкою миші на їх фото або профіль і виберіть "Заблокувати <username>". Ви будете задані опції видалення попередніх повідомлень - обрати варіант "Не видаляти", як повідомлення повинні залишатися актуальними як історичний запис.
- Якщо ви вирішили заборонити комусь, це означає, що вони не бажають дотримуватися нашого Кодексу поведінки. Тому безумство багаття рідко повинно відбуватися. Однак, якщо необхідно, ви можете зробити це натиснувши на назву сервера, вибравши "Налаштування сервера", обирайте "Бани", обравши користувача, якого ви хочете розблокувати, і натисніть кнопку "Відкликати Бан".

Бани Discord є глобальними - ви не можете забанити користувача у конкретному каналі, тільки з усього сервера.

4. **Видалення повідомлень** Модераторів може видаляти повідомлення в Discord. Вони повинні реалізовувати цю здатність лише у чотирьох дуже особливих ситуаціях:

- Хтось розмістив зображення порнографічної або графічно насильницької роботи.
- Хтось розмістив посилання або код, який є шкідливим у природі і міг зашкодити іншим верблюдам, які клацнули по ній.
- Хтось затопив чат великою кількістю спам-повідомлень в такому надзвичайному масштабі (зазвичай участь ботів), щоб відобразити в чаті абсолютно непридатним для використання.
- Хтось розмістив рекламу і / або повідомлення для самостійного просування / зображення (соціальні медіа).

У всіх інших ситуаціях - навіть ситуації, коли кодекс поведінки порушується - Модератори не повинні видаляти повідомлення, оскільки це важливий історичний запис. Коли ви видаляєте повідомлення, переконайтеся, що ви зробили знімок екрана для нього! Скріншот може бути ввійшов у #мод-журнал, але для #активності-журналу достатньо, щоб сказати, що доказ був "видалений через чутливий вміст". Примітка: Якщо повідомлення містить матеріал, який буде незаконним зробити знімок екрану, замість цього скопіюйте посилання на повідомлення - надайте це повідомлення посилання на @raisedadead до команди безпеки Discord.

5. **Ви не використовуєте @everyone або @here** Не використовуйте @everyone або @everyone за будь-яких обставин! Кожен учасник цієї кімнати отримає сповіщення. В деяких випадках, десятки тисяч людей. Замість цього, якщо ви хочете, щоб люди побачили оголошення, ви можете прикріпити його до каналу , щоб усі могли його прочитати.

6. **Не погрожувати бану чи призупиненню** Якщо табір порушує код поведінки, Не погрожуй заборонити або призупинити їх, і ніколи не попередити їх на публіці. Натомість, спілкуйтеся з ними приватно, або відправте їх DM і випускайте призупинення (в протоколі вище). Ніхто інший в цьому каналі не повинен знати, що ви забанили / призупинили людину - вербники можуть переглядати резюме в каналі #activity-logit, якщо вони хочуть продовжити цю інформацію. Якщо порушення було явно ненавмисне і не гарантує призупинення чи приватну розмову, змусити його ображеного табору усвідомлювати його / її дії, не показуючи їх як попередження. Наприклад:

- Сестра вставляє стіну коду, щоб подати запит допомоги

  Модератор: @username Будь ласка, використовуйте Codepen або Pastebin під час публікації великих обсягів коду.

- Або, якщо ви дійсно маєте пояснити, чому:

  Модератор: @username Будь ласка, використовуйте Codepen або Pastebin при розміщенні великих обсягів коду, оскільки він порушує чат для всіх і може вважатися спам відповідно до нашого Кодексу поведінки.

- Для легких і ненавмисних порушень кодексу поведінки

  Модератор: Це дружнє нагадування для всіх, хто дотримується коду поведінки: https://code-of-conduct.freecodecamp.org/

7. **Не турбуйтеся про те, що модератор** не сприймайте себе як над спільнотою. Ти спільнота. І громада довірила вам допомагати захистити щось рідке, з чим ми всі ділимось - _вітання_ місця для нових розробників. Якщо ви в'яжетеся з тим, що ви модератор, люди можуть почуватися неспокійно навколо вас, Так само, як люди можуть почуватись непростими навколо поліцейського, навіть якщо вони не роблять нічого поганого. Це лише людська природа.

8. **Не суперечить іншим модераторам** Якщо ви не погоджуєтеся з дією модератора, обговоріть з ними приватно або створіть його у каналі #мод-чаті. Ніколи не перевизначити заборону і ніколи не суперечать іншим модераторам. Натомість мають холодну дискусію в груповому чаті і і переконують модератора, що вони самі повинні скасувати заборону або змінити свою точку зору. Пам'ятайте: ми всі в одній команді. Ми хочемо гідні роль модераторів і представити єдиний фронт.

9. **Зв'яжіться з іншими модераторами** У нас є місце лише для модераторів. Використати! Якщо вам не здається, як впоратися з певною ситуацією, попросіть інших модераторів допомогти. Якщо ви думаєте, що щось треба обговорювати, зробіть це. Ви частина команди, і ми оцінюємо внесок кожного члена! Навіть якщо ви повністю не погоджуєтеся з чимось у цих інструкціях або Кодексом поведінки!

10. **Тимчасово неактивний** Якщо ви не будете активними як Модератор на деякий час у відпустці, Хвороба чи будь-яка інша причина, не забудьте повідомити інших на #мод-чаті. Таким чином, ми знаємо, що ми можемо розраховувати на вас регулярно активними на сервері, чи ні.

# Як стати модератором

Якщо ви допомагаєте людям у спільноті постійно з часом, наша команда модераторів з часом помітить, а один з них згадає вас як можливий модератор для [нашого персоналу](https://forum.freecodecamp.org/g/Team). Немає ярликів, щоб стати модератором.

Якщо ви будете затверджені, ми додамо вас до наших модераторів на [GitHub](https://github.com/orgs/freeCodeCamp/teams/moderators), [форум](https://forum.freecodecamp.org/g/moderators)і т. д.

> [!NOTE] > **Для GitHub:** Після того, як ви були прийняті як модератор, ви отримаєте запрошення на репозиторій на Github . Вам потрібно буде перейти до [freeCodeCamp GitHub Запрошення](https://github.com/orgs/freeCodeCamp/invitation) щоб мати можливість прийняти запрошення. Це необхідно для того, щоб ми могли дати вам доступ на запис у нашому репозиторії.

# Як ми виходимо на пенсію неактивних модераторів

Будь ласка, зверніть увагу, що ми часто видалимо моди, які, як ми вважаємо неактивними. Коли ми це зробимо, ми надішлемо наступне повідомлення:

> Це стандартне повідомлення повідомляє вам, так як вам, здається, не є активним модератором, ми видаляємо вас з команди модератора. Ми глибоко цінуємо вашу допомогу в минулому.

> Якщо ви думаєте, що ми зробили це в помилці, або коли ви готові повернутися і більше внести свій внесок, просто відповідайте на це повідомлення, яке мені повідомляє.

# Як працює наш учасник

Будь-хто вітає в [кімнаті учасників проекту нашого Discord](https://discord.gg/KVUmVXA). Це призначений чат для модераторів та інших верблюдів, які роблять свій внесок у нашу спільноту будь-якими способами, у тому числі, через навчальні групи.

Наше припущення в тому, що учасники прочитають щось у цій кімнаті, які безпосередньо згадують їх за допомогою `@username`. Все інше необов'язкове. Але не соромтеся читати будь-хто там дописи та взаємодіяти.

# Справа з адвокатами

Вас можуть звернутися до організацій, які хочуть піти на партнерство або співбренду з безкоштовним кодеком. Як тільки ви зрозумієте, що це те, що вони роблять, будь ласка, припиніть говорити з ними і повідомте їх електронною поштою quincy@freecodecamp.org. Він отримує подібні пропозиції постійно, і в найкращій позиції судити про те, чи варть такі стосунки для нашої спільноти (і це рідко буває).

# Зв'язок з (ментальними) питаннями здоров'я

Ви можете в різних ситуаціях, коли користувачі шукають медичних порад, або мають справу з питаннями психічного здоров'я і шукають підтримки. Що стосується політики, то ви повинні уникати розмови приватно про ці справи. Якщо ситуація в якийсь момент відбивається до fCC, ми хочемо мати розмови про запис. Зрозуміло, що ми не медичні працівники, і що ви заохочуєте користувача знайти професійну допомогу. Наскільки це важко іноді може бути, уникати порад або порад, відмінних від того, щоб вказувати користувача в напрямку професійної допомоги!

Якщо це відбувається у Discord: Призупинити користувача. Це не для їх покарання! Призупинення користувача створить приватний канал, який буде доступний тільки користувачем і командою. Це матиме користь і користувачеві, і ЗУД кількома способами:

- Користувач гарантує певну конфіденційність
- Публічний чат більше не порушений
- Інші члени команди можуть повернутись у цю справу, якщо вам не зручно працювати з самим ситуацією

> [!NOTE] Призупинення користувача автоматично надає їм повідомлення про читання нашого Кодексу поведінки. Переконайтеся, що ви інформуєте користувача, якого ви призупинили їм, щоб дати їм певну конфіденційність і що вони не покараються. Це дуже важливо! Ми абсолютно хочемо не дати користувачам ідею, що вони покараються за те, щоб отримати допомогу!

Якщо ви вважаєте, що користувач може приєднатися до спільноти, клацніть правою кнопкою миші на приватному каналі і скопіюйте ID. Покласти наступне повідомлення в #mod-log:

> Знижка з медичною підказкою: <channel ID> <username>

Після цього ви зможете зняти призупинення з користувача, як звично.

Корисні URL:

http://www.suicide.org/international-suicide-hotlines.html

# Вільна мовна нотатка

Іноді люди будуть захищати щось образливе чи запальне, що вони кажуть, як "вільна мова."

Цей метод XKCD чудово підсумовує більшість думок спільнот у вільному мовленні. І якщо хтось захищає щось, що говорить, як "вільне слово", не соромтеся відправити це їм.

<div align="center"><img src='https://aws1.discourse-cdn.com/freecodecamp/original/3X/4/3/43a8b2eafe4c8622e02838f66f1dc6227de32c70.png' width="400" height="400" /></div>

Дякуємо, що прочитали це, і дякуємо за допомогу спільноті розробників!