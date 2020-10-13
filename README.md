![alt text](https://github.com/nehilo/kp3s/blob/master/logo%20kp3s.png?raw=true)

Прошивка Marlin 2.0.7.2 для KP3S

⭕️ Автоматическое включение/выключение вентилятора хотенда при достижении температуры в 100% (выключение происходит когда температура опускается ниже 100%) Чтобы активировать эту функцию, нужно подключить вентилятор к выводам HE1. ОБЯЗАТЕЛЬНО СОБЛЮДАТЬ ПОЛЯРНОСТЬ!!

![alt text](https://github.com/nehilo/kp3s/blob/master/photo_2020-10-13_15-37-47.jpg?raw=true)

⭕️ В прошивке включен Junction Deviations (0.036)

⭕️ Показывает процент печати: сколько времени печататает и сколько осталось времени печати (настраивается через плагин CuraPlugin_AddPctComplete.py который нужно поместить в C/Ultimaker Cura/plugins после в CURA через расширения пост-обработки добавить скрипт Display Progress On LCD)

⭕️ Показывает сколько затрачено пластика в "мм"

⭕️ Активирован Linear Advance (значение настраивается через слайсер)

⭕️ Добавлена компенсация калибровки стола по 9 точкам. Меню - Движение по осям - Выровнять стол

⭕️ Есть небольшая проблема с переэкструзией пластика.  Лечится заменой драйвера экструдера, либо настройкой потока в CURA

⭕️ Дисплей к сожалению развернут в альбомном отображении, лечится печатью переходника(можно использовать без переходника) https://www.thingiverse.com/thing:4578390

⭕️ После установки прошивки инициализировать EEPROM ( Меню- Конфигурация- Другие настройки- Инициализация EEPROM )

⭕️ Провести калибровку Pid экструдера - запустить в печать PidCalibration.gcode. После зайти в Меню-Конфигурация-Сохранить настройки

Другую полезную информацию можно найти в чате  https://cutt.ly/Cgow7vL

![alt text](https://github.com/nehilo/kp3s/blob/master/photo_2020-10-06_00-54-15.jpg?raw=true)
