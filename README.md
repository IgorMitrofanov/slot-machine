# slot-machine

**Текст задания**

Вам нужно будет произвести расчеты для простой слот машины, и указать параметры, которые вы задали при проведении расчетов, и к каким показателям пришли. 

Ваш слот работает по правилам реальных физических слотов: каждый барабан представляет собой ленту, заполненную символами. Каждый спин ленты независимо и равновероятно останавливаются в одном из своих положений. Длина одной ленты должна быть до 200 символов.

Параметры вашей слот машины:

●	8 обычных символов.

●	Wild символ.

●	Символ Free Spins.

●	Сетка 3х3 (у слота 3 барабана, активная область барабана - 3 символа).

●	5 линий (можете взять произвольное расположение линий).

●	Комбинации выплачиваются за 3 последовательных элемента на линии.

●	При выпадении 3 символов фри спинов в любом месте вне зависимости от линий запустится фриспиновая игра с 10  бесплатными спинами. Во время бесплатных спинов, нельзя выиграть дополнительные бесплатные спины - используются другие ленты.

●	Payout: 90 - 95%

●	Ставка на игру 5 (по 1 фишке на каждую линию).

●	Wild выплачивается, а также может участвовать в комбинации, заменяя собой обычные символы, но не символы Free Spins.

В качестве ответа на это задание предоставьте:

●	Использованные линии.

●	Ленты (барабаны) слота.

●	Таблицу выплат

●	Payout каждой комбинации (обычные символы и Wild) для обычной игры.

●	Payout бесплатных спинов.

●	Частоту срабатывания в обычной игре фриспинов.

Расчеты произведите при помощи симуляции. Вы также можете произвести проверочные расчеты аналитически. Это приветствуется и оценивается дополнительно, но не обязательно. Предоставьте код вашей симуляции и excel/google документ с параметрами для проверки. Пример документа (здесь представлены случайные цифры). Код симуляции обязательно должен быть написан на Python.
