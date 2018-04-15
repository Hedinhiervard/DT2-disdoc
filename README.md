# Dwarf Tower 2 (DT2)

В данном документе собраны ключевые отличия планируемой второй версии DT. Предполагается, что читатель ознакомлен с игровой механикой DT.

# Общие замечания

Игра становится коллекционной. Игроки собирают уникальные карты, а также могут торговать ими и ставить на кон в партиях. 

# Карты

Карты будут сделаны двухсторонними. На рубашке карты изображаются конструктивные элементы:
 * блоки
 * купол
 * забор
 * броня
 
 Доступны следующие виды блоков:
 * 4-блок (имеет выходы во все стороны)
 * 3-блок (3 выхода, может вращаться)
 * 4 вида 3Ф-блоков (3 выхода, не может вращаться)
 * 2 вида 2-блоков (Г-образный и прямой, 2 выхода, могут вращаться)
 * 12 видов 2Ф-блоков (имеют 2 выхода, не могут вращаться)
 * 1-блок (тупиковый блок, может вращаться)
 * 4 вида 1Ф-блоков (фиксированный тупиковый блок, не может вращаться)
 * 0-блок (не имеет выходов)
 

На лицевой стороне карты изображаются содержательные элементы:
 * комнаты
 * левитрон
 * заклинания
 * инструменты гномов

Также вводятся новые типы карт:
 * карты гномов (добавляют гномов) 
 
Каждая карта может быть сыграна либо рубашкой (тогда она образует новый блок башни), либо лицом (тогда она образует то или иное наполнение). 

Рубашка карты доступна для просмотра оппонентом в то время, когда карты находятся на руке. Кроме того, оппонент видит рубашку верхней карту колоды.
 
Таким образом сочетание рубашка + лицевая сторона определяет уникальную карту. Таких комбинаций можно предусмотреть очень много (порядка тысяч). 

## Упраздняются карты

*Покои Архимага*, *Жилище Гномов*

## Новые карты

* *Гном* - добавляет одного гнома в выбранную комнату.
* *Антиплесень* - устраняет плесень в одной комнате и предотвращает ее появление (действует до затопления комнаты).

## Модификация существующих карт

*Обсерватория* при строительстве высвечивает лучом одну комнату вражеской башни (ее содержимое становится видимым). Каждый ход на этапе Разведки игрок может переместить луч на соседнюю клетку. *Обсерватория* всегда выдает свое местоположение (видно источник луча, цель луча, но содержимое комнаты с *Обсерваторией* не раскрывается противнику). Является хрупкой комнатой (ее запрещено переносить с помощью карты *Перенос комнат*, любое повреждение блока уничтожает *Обсерваторию*.

*Лаборатория*. Позволяет скидывать **N** карт с руки в ход (на этапах Строительства и Ремонта) и набирать новые. Карты скидываются по одной. Каждый раз после скидывания карты с вероятностью 50% происходит взрыв, если взрыв произошел, то с вероятностью 25% начинается пожар. Если взрыв произошел, новая карта на руку не набирается.

# Персонажи

Вводятся новые сущности: персонажи. Их 2 типа: *Гном* (сколько угодно) и *Архимаг* (ровно один). Оба типа в каждый момент времени пребывают в одной клетке. Обладают скоростью (1 клетка). Каждый ход на этапе Строительства и Ремонта могут переместиться на количество клеток, равное своей скорости. Применять защитные заклинания можно только в клетках, где находится 1 или более *Гномов*. Сила действия заклинаний зависит от положения *Архимага* (базово - высота над уровнем моря, но не менее 1). Каждое применение заклинания выдает положение *Архимага* противнику и раскрывает содержимое комнаты (до момента его перемещения).

# Подготовка к партии

Игроки выбирают **20** карт из имеющихся у них в наличии. Каждый игрок набирает руку из 6 карт. При необходимости сбрасывать руку и набирать на 1 карту меньше, вплоть до 0 (*муллиган*). 

# Генерация ландшафта

Перед игрой игроки могут модифицировать свой или чужой ландшафт. Напр., подложить бомбу в одну из подземных клеток или сделать землю неудобной для строительства высокой башни. Находится на этапе разработки идеи.

# Плесень

Затопленные комнаты на следующий ход плесневеют. Заплесневевшая комната распрострает плесень в соседние комнаты раз в ход. Заплесневеть могут только комнаты подземелья. Карта *Антиплесень* устраняет плесень в одной комнате и предотвращает повторное заплесневение комнаты (эффект действует до затопления комнаты). Заплесневевшие комнаты не работают. Двери предотвращают распространение плесени.

# Ход игры

Игра также делится на ходы. В каждый ход включается 8 основных фаз: 
 * начало хода
 * строительство
 * разведка
 * подготовка к бою
 * бой
 * ремонт
 * гибель
 * бедствия
 * конец хода

Рассмотрим фазы подробно.

## Начало хода

Происходит одновременно. Игроки тянут по карте каждый из своей колоды.

## Строительство

Происходит одновременно. Игроки могут сыграть любое количество карт из руки рубашкой (достраивая башню) или лицевой стороной (наполняя башню). Запрещено играть разведывательные карты (напр., *Глаз*) и боевые карты (напр., *Фаерболл*). Разрешается играть *Ремонт*, *Огнетушитель* и другие карты, видоизменяющие башню игрока. В этой фазе каждый персонаж (*Гном* или *Архимаг*) могут переместиться согласно своей скорости в соседнюю комнату. Также, на первом ходу игры игрок обязан выставить своего *Архимага* на любую доступную клетку. Играть ремонтные карты можно только в тех комнатах, где находятся 1 или более *Гномов*.

## Разведка

Происходит одновременно. Игроки могут сыграть любое количество карт, открывающих часть информации о вражеской башне (напр., *Глаз*). Кроме того, игроки могут применить специальные способности комнат разведки (*Обсерватория* может сместить луч на одну клетку).

## Подготовка к бою

Игрок одновременно и в тайне друг от друга добавляют в очередь заклинания. 

## Бой

Происходит по очереди. Сначала играются заклинания первого игрока, затем второго. Каждое применение заклинания выдает положение *Архимага* противнику (комната становится доступной для просмотра). Каждое перемещение *Архимага* впоследствии снова скрывает комнату (если она не раскрыта другими средствами, напр., заклинанием *Глаз* или *Обсерваторией*).

## Ремонт

Происходит одновременно. Игроки снова могут играть строительные, защитные и ремонтирующие карты (запрещено играть боевые и разведывательные карты). Напр., допустимо сыграть заклинание *Антиглаз*, чтобы скрыть раскрытые на этапе Разведки комнаты. Персонажи могут снова переместиться согласно своей скорости.

## Гибель

Погибают персонажи:
 * оказавшиеся в затопленных комнатах
 * оказавшиеся в горящих комнатах
 
## Бедствия

* непотушенные пожары распространяются
* плесень распространяется

## Конец хода

Если погиб *Архимаг*, игроку засчитывается поражение.

# Онлайн-игра

Вводятся лиги. Попасть в лигу можно, обладая определенными картами, картами определенного качества или по иным критериям.
