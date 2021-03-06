# Глава 1: Данные в современном мире

## Вместо вступления

Привет! Если тебе не терпится приступить к деятельности более активной, чем чтение, то переходи сразу к главе 2. Глава, которую ты сейчас читаешь, в большей степени предназначена для погружения в контекст и утоления графомании автора.

Перед тем, как углубиться в подробности описания профессии дата-аналитика, хочется написать несколько слов о том, что такое данные, какие в работе с данными существуют профессии и подходы, как с данными в принципе можно работать и зачем это нужно.

Также хотелось бы сразу договориться: речь в этих материалах пойдёт про анализ данных в коммерческой деятельности. Если ты хочешь узнать про применение анализа данных для научных или любых других целей, нужно обязательно держать в голове, что специфика этих целей может значительно влиять на процесс обучения и трудоустройства.

Что ж, приступим! 🎉

## Данные

В общем смысле данные — это любая информация, представленная в цифровом формате: электронная книга, ваш любимый фильм в стриминговом сервисе, картинки, музыка и т. д.

### Минутка интересных фактов

Общий объём данных в сети на 2018 год составлял 33 [зеттабайта](https://ru.wikipedia.org/wiki/%D0%97%D0%B5%D1%82%D1%82%D0%B0%D0%B1%D0%B0%D0%B9%D1%82) (1 зеттабайт — это 1 млн. петабайт), за один 2019 год объём данных вырос на 4.4 ЗБ, а к 2025 году *аналитики* прогнозируют прохождение отметки в 175 ЗБ. Конечно, сами по себе эти цифры мало что значат, но вот другой интересный факт для сопоставления: мозг человека способен вместить объём данных, примерно эквивалентный 2.5 петабайт цифровой информации. Это значит, что для хранения всей цифровой (только цифровой!) информации нужно примерно 13.2 миллиона экземпляров человеческого мозга, и количество необходимых мозгов неуклонно растёт! Так что если тебя когда-то преследовала навязчивая идея не упустить ни капельки информации — расслабься, битва уже проиграна.

Помимо определения, которое я привёл выше, в словарях можно встретить и другое описание термина «данные» — *Сведения, необходимые для какого-н. вывода, решения.* Это весьма актуально для профессии аналитика, потому что данные не могут существовать сами по себе — в первую очередь они нужны именно для того, чтобы принимать какие-то решения.

### Данные и бизнес

В наше время трудно представить коммерческую организацию, которая не генерирует цифровые данные. Управление почти всеми процессами компьютеризировано, существует немыслимое количество систем для учёта и обработки информации. Помимо очевидной пользы от автоматизации процессов цифровизация приводит к тому, что любой бизнес обрастает гигабайтами информации, которую можно и нужно анализировать.

Аналитика помогает бизнесу массой разных способов, вот лишь некоторые из задач, выполнение которых трудно представить без участия аналитики:

- (Привести этот список в порядок)
- Оптимизация операционной (внутренней) деятельности компании.
- Организация проведения экспериментов.
- Анализ эффективности работы сотрудников и подразделений, рекламных кампаний и т. д.
- Финансовое, кадровое и любое другое планирование.
- Прогнозирование спроса, выручки, пользовательского поведения, и др.

Грамотно выстроенная аналитика помогает бизнесу всегда «держать руку на пульсе», увеличивать выручку, сокращать расходы, и так далее. Верно и обратное утверждение: плохо выстроенная аналитика или её отсутствие могут не только не дать бизнесу расти, но и серьёзно навредить за счёт неправильных стратегических решений, неправильного понимания реального финансового положения компании и т. д.

### Данные бывают разные

Возможно, тебе уже приходилось погружаться в теорию и ты думаешь, что анализ данных — это про числа. В реальности аналитик может столкнуться с данными любого типа:

- Числа — работа с финансовой аналитикой.
- Текст — речевой анализ отзывов о компании, разговоров отдела продаж и т. д.
- Видео — computer vision, автоматизированная премодерация контента в соц. сетях и прочее.
- Картинки — снова премодерация, снова computer vision, алгоритмы поиска по картинкам и другое.
- Табличные данные, состоящие внутри себя из других типов данных.
- Любой другой тип данных.

Тем не менее, в подавляющем большинстве случаев основной тип данных, генерируемых бизнесом — это действительно или таблицы, или данные, которые можно представить в виде таблиц. Так уж сложилось, что почти все бизнес-процессы порождают множество мономорфных (имеющих неизменную внутреннюю структуру) одномерных данных: это и списки клиентов с кучей полей, и информация о заказах, и банковские операции, и многое-многое другое. Такие данные удобно представлять в виде таблиц. Почему это так, ты подробнее узнаешь из более поздних глав, на данный момент важно осознать, что таблица — это ключ ко всему (и источник всех проблем 🙂).

## Работа с данными

### Что вообще можно делать с данными?

Итак, представь, что перед тобой откуда-то материализовалась таблица заказов из магазина одежды.

(добавить таблицу)

В таблице содержится информация о том, когда был сделан заказ, на какую сумму, оплачен ли заказ, и так далее. Какую информацию мы можем получить из этой таблицы?

(кратенько написать про разную стату, которую можно извлечь)

Числа и таблицы — это отлично. Можно получить массу инсайтов, по-разному аггрегируя информацию и выводя её на экран, но в инструментарии аналитика есть ещё один крутой инструмент, который позволяет упростить человеческому мозгу процесс восприятия. Имя ему — визуализация.

(какой-нить график)

Как видишь, данные, представленные в виде графика, позволяют за долю секунды оценить, как идут дела в компании. Кроме того, на визуализациях гораздо проще отследить закономерности: например, на нашем графике отлично видны всплески продаж перед новогодними праздниками. Это в общем-то и так достаточно очевидный факт, но в иной ситуации такие открытия могут стать толчком для пересмотра подхода к планированию нагрузки сотрудников и объёмов закупок.

Итак, давай подведём некий итог. Что мы только что делали с данными? Мы их:

- изучали
- обрабатывали
- визуализировали

Можно много всего написать про математическое моделирование, machine learning и другие [дата дривны](https://t.me/sorta_datadriven), но по большому счёту вся деятельность дата-аналитика состоит из этих базовых функций.

### Культура работы с данными

Кирилл, напиши общие слова про то, почему данными должны управлять не аналитики, а бизнес.

Когда дело доходит до работы с данными, в разных компаниях ситуация выглядит абсолютно по-разному. В попытке классифицировать подходы к работе с данными можно выделить несколько уровней «зрелости» компании в плане аналитической культуры.

### Уровень 1. Всё плохо

(картиночка)

Работа с данными в компании из-за специфики бизнеса или по другим причинам отстутвует в принципе или никак не оцифрована.

В наши дни такое встречается уже достаточно редко, так как в наши дни как минимум финансовая отчётность подразумевает необходимость вести финансы не в блокноте. Тем не менее, так тоже бывает, и это **очень плохо**, о чём я вкратце писал выше.

### Уровень 2. Всё плохо, но надежда есть

(картиночка)

Работа с данными имеет «стихийный» характер, нет системного подхода и понимания, зачем нужна аналитика.

Вероятнее всего, в таких компаниях работа с данными локализована вокруг сотрудников, которым либо не нравится пребывать в информационном ваккууме, либо жизненно необходимо работать с оцифрованными данными, например, вокруг бухгалтерии. При этом на организационном уровне осознание того, что нужно выстраивать аналитику, отстутсвует.

### Уровень 3. Таблицы как религия

(картиночка)

Работа с данными поставлена на поток. Возможно, под задачи аналитики даже выделен отдельный сотрудник, при этом всё ограничивается простейшими инструментами и подходами:

- Google Sheets или Excel как основной инструмент.
- Простейшие преобразования на уровне незатейливых формул, в лучшем случае — ВПР и сводные таблицы.

Нельзя сказать, что это ужасно, потому что хорошо известно, что мешает плохому танцору, да и для отдельных задач вполне хватит функционала Excel, но это в достаточной степени ограничивает возможности анализа и интерпретации данных.

Обычно на этом уровне уже есть понимание, чем данные могут помочь бизнесу, но нет бюджета на выделение аналитики в отдельное направление (или понимания, зачем это нужно делать). Из этого состояния уже достаточно просто выйти на нормальный уровень.

### Уровень 4. Крепкий середнячок

(картиночка)

Доработать

В штатном расписании есть как минимум один полноценный аналитик или человек, в основном выполняющий фукнцию аналитика.

Используются готовые инструменты (маркетинговые кабинеты, roistat) или что-то более специальное (простые BI-решения и тд).

Бизнес понимает, зачем нужны данные, и часто ходит к аналитике.

### Уровень 5. Отлично, продолжаем в том же духе

(картиночка)

Доработать

Средняя или большая команда аналитики.

Есть или наклёвывается хранилище и пайплайны.

Кульутра работы с данными на хорошем уровне, бизнес в полной мере управляет метриками и процессами

### Уровень 6. Суровый enterprise

(картиночка)

Кирилл, помоги :(

### Что важно понимать

Это деление в целом достаточно условное, и в реальности какие-то вещи непременно будут пересекаться, но я почти уверен, что большую часть бизнесов вполне можно «разложить» по этим уровням.

## Профессии

Так как работа с данными выделились в отдельное направление деятельности не так давно, профессиональная среда всё ещё находится на этапе формирования, что подтверждается в первую очередь тем, насколько по-разному выглядит состав аналитических команд в разных компаниях с сопоставимыми оборотами.

### Кто работает с данными?

На самом деле работает с данными как правило не только аналитик. Вокруг данных есть множество задач помимо анализа, и с ростом объёмов данных и количества задач любая компания неизбежно приходит к необходимости более узкой специализации отдельных сотрудников. Давай пройдёмся по основным специальностям в работе с данными.

- тут типа списочек с краткими описаниями DE, CDO, DQM, DA, DS, и тд.

В рамках этих материалов я буду держать фокус на профессии дата-аналитика, но важно понимать, что в реальности функционал дата-аналитика может быть шире за счёт частичного или полного перенятия функционала

### Такие разные аналитики

Написать про разницу или её отсутствие между аналитиком, дата-аналитиком, аналитиком данных, финансовым аналитиком, продуктовым аналитиком и т. д.

