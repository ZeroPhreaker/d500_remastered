# d500_remastered
Прошивка кодграббера на брелок Pandora d500

Братцы, фрикеры и взломщики автомобильных сигнализаций, здорово!
С вами Зеро на связи. Решил я тут тряхнуть стариной и выпустить очередное обновление прошивки, создателем которой я являюсь. 
Данную прошивку, как и обновления по ней вы можете скачать с github. 
Прошивка на брелок Pandora d500 старого образца. 
Включаем по кнопке SOS - без пин кода. Если помните у прошивки был глюк, когда при включении стиралась нулевая ячейка. Так вот, эту фишку я изящно убрал. Просто при включении ячейка выбирается первая, а не нулевая )))))
10 ячеек памяти, переключаем по кнопке SOS. Очистка ячейки по кнопке F. Переключение режимов - кнопка Check.
Да вот собственно и все. Данный проект называется d500 remastered, поскольку я частично переписал код, а также добавил некоторые штатные сигналки.

Что изменилось? Обозначения сигналов. Давайте по порядку.

EE - килог, около 100 мануфактурных кодов
AL - старлайн, порядка 30 мануфактурных кодов
CF - шерифы
5H - шерханы, про 1 и про 2, включая удары по лапке и так далее
Au:01 - старые ауди, по 2005 кажется год. Давайте сразу по сигналам штаток. Итак, как открыть ауди. Во первых, когда вы поймали сигнал ауди, у вас на брелке должен отобразиться закрытый замок или открытый, т.е. поймали вы открытие или закрытие. Нам конечно же нужно открыть автомобиль, поэтому нажимаем на вторую кнопку и смотрим на реакцию автомобиля. Если автомобиль открылся и в дальнейшем нам нужно закрыть тачку, тогда правильный сигнал на открытие нужно сохранить в памяти брелка. Для этого держим кнопку Check пару секунд. После этого вы можете закрыть машину нажав уже закрытие (первая кнопка на брелке)
5u:01 - субару, старый код, даже не знаю рабочий он или нет
Hu:01, Hu:02 - это все коды корейских авто, такие же как и в кодграббер Pandora v.2.4, кроме этого сюда добавлен ключ ILOAD NEW ZEALAND - не ебу что это такое, но в программаторе ключей он так обозначается. Ключ iload на первом режиме
H0:03 - старые хонды, в ASK модуляции - обязательно должно отобразиться открытие или закрытие. Ни в зуб ногой открывается или нет, надо проверять
F0:01 - старые форды в ASK. ТЕСТОВЫЙ РЕЖИМ
d0:09 - какая то статика
5С:01 - старые шкоды, не проверял. ТЕСТОВЫЙ РЕЖИМ
b9:99 - старые бмв, без замочка. Нужно записать два сигнала. Т.е. сначала пишем закрытие, затем открытие и пробуем открывать по первой кнопке. ТЕСТОВЫЙ РЕЖИМ

Отдельная благодарность всем кто когда то помогал мне в создании этой прошивки. Немец, Мафия и парень с фрикерклаба (я забыл твой ник, старость не радость), а также всем кто донатил на развитие прошивки.

Данная прошивка выпускается как есть без каких либо гарантий. Всем фарту, живите как хотите, не будьте рабами системы!
