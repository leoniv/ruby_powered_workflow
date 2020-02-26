# Ruby Powered Workflow (RPW)

RPW "Ruby Powered Workflow" или "1С:Предприятие на рельсах Ruby"

## Идея

**Дать мощь языка Ruby в помощь 1С разработчикам и специалистам сопровождения**

## Зачем это нужно?

1. Для построения автоматизированного процесса разработки, тестирования и доставки кода известного так же как CI/CD.
2. Для автоматизации задач связанных с сопровождением и тех. обслуживанием систем на платформе 1С.
3. Для создания внешних API или прочих инструментов для доступа и манипуляции данными хранящимися в учетных системах 1С.

[Вот тут есть очень простой пример](https://github.com/leoniv/hackathon/tree/master/ones)

## Почему Ruby?

Потому, что на 1С нельзя сделать того, что написано в выше. Я пытался это сделать на 1С. Я отчаялся и хотел уж было
плюнуть на все но мне в руки попался Ruby и я его полюбил. Вы его тоже полюбите!

Но если серьёзно, Ruby очень выразительный динамический язык, который нравится
и вдохновляет многих. На Ruby можно писать лаконичные, хорошо структурированные и масштабируемые инструменты. Особым коньком Ruby
является его непревзойдённая "подходящесть" для создания доменно-специфичных языков - DSL. Мощная экосистема богатая коллекция
gem-ов на все случаи жизни позволяет создавать сложные вещи не прилагая больших усилий.

## Что вклбчает в себя RPW?

Несколько библиотек и утилиты уже разработано:

- [ass_launcher](https://github.com/leoniv/ass_launcher) - это хребет [RPW](https://github.com/leoniv/ruby_powered_workflow);
- [ass_ole](https://github.com/leoniv/ass_ole) - отлично походит для Ruby скриптинга с доступом к 1С рантайму
и данным и кластеру серверов 1С по средствам OLE. Библиотека берет на себя много рутинной работы оставляя время для создания
полезного кода.
- [ass_maintainer-info_base](https://github.com/leoniv/ass_maintainer-info_base) - абстракция над экземпляром приложения 1С
известного как "Информационная база". Будет полезна как для мейнтейнеров так и для специалистов DevOps исповедующих принцип
"Инфраструктура как код"

Некоторые недоделаны, имеют статус рабочих, но находятся в состоянии не пригодном для релиза и требуют серозного рефакторинга

Вот пара из них:
- [ass_devel](https://github.com/leoniv/ass_devel) - для автоматизации процесса разработки ПО 1С:Предприятие;
- [ass_tests](https://github.com/leoniv/ass_tests) - для тестирования ПО 1С:Предприятие;


И некоторые другие штуки которые можно найти [в этом профиле github](https://github.com/leoniv) с общим префиксом "ass_"

> к слову "ASS" это не то, что вы подумали, а это аббревиатура от Automated Aupport Aystem, и еще созвучно со словом "Один Эс"

## Опыт использования

Опыт использования этого инструментария небольшой но он есть. Есть опыт разработки приложения (конфигурации)
и его покрытия тестами. Есть опыт разработки внешних отчетов и обработок так же с покрытием тестами.

Опыт в целом положительный и позволил с минимальными затратами труда создавать 1С софт который взлетал в с первой попытки
с парой минорных багов.

**Пользуйтесь с удовольствием :)**
