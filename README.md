### A program for measuring memory bandwidth and a module for overclocking a PSP processor.

### MemSpeedTest
The program has no controls at all, just launched it and looked!)

- memory bandwidth using the main processor
   * Read from all memory types
   * Write to all types of memory
   * Copy
- PSP using VFPU
   * Read from all memory types
   * Write to all types of memory
   * Copy
- Approximate cpu frequency (very approximate) and is measured only once when the application starts. Bandwidth is measured in MB/s.

###OverClockPlugin
Plugin designed to overclock PSP. It is copied to the ms0:/seplugins/ folder of the memory card and activated in the recovery menu of the custom firmware. Or in the game.txt file add the line

* ms0:/seplugins/OverClockPlugin.prx 1

Controlled by a combination of LTrig + VDown to decrease the frequency and LTrig + VUp to increase it. A small number from 0 to 9 will blink in the upper left corner of the screen. 0 corresponds to 100MHz, step 33MHz,
9 - 366MHz.

### Программа для измерения пропускной способности памяти и модуль для разгона процессора psp.

### MemSpeedTest
Программа не имеет управления совсем, просто запустил, посмотрел!)

- ПСП средствами основного процессора
  * Чтение из всех типов памяти
  * Запись во все типы памяти
  * Копирование
- ПСП средствами VFPU
  * Чтение из всех типов памяти
  * Запись во все типы памяти
  * Копирование
- Примерная частота cpu (очень примерная) и измеряется только один раз при запуске приложения. ПСП измеряется в MB/s.

### OverClockPlugin
Плагин, предназначенный для разгона psp. Копируется в папку ms0:/seplugins/ карты памяти и активируется в рекавери меню кастомной прошивки. Либо в файле game.txt добавляем строку

* ms0:/seplugins/OverClockPlugin.prx 1

Управляется сочетанием LTrig + VDown для уменьшения частоты и LTrig + VUp для увеличения. В левом верхнем углу экрана мигнёт маленькая цыферка от 0 до 9. 0 соответствует 100MHz, шаг 33MHz, 
9 - 366MHz. 
