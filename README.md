Название проекта: Визуальная арифметика

Команда: АТ-05

Формат системы: Desktop приложение

Цель проекта: 
Создать приложение с различными технологиями визуального счета

Описание:
Обучающее мобильное приложение (сервис) которое обучит пользователей методу визуального счета, что в разы ускорит устные вычисления, а так же позволит производит операции над большими числами без использования калькулятора

Целевая аудитория:
Студенты и школьники 8+, которые увлекаются математикой.
Учителя и преподаватели, которые хотели бы изучить новые методики обучения счета

Основное преимущество:
Отсутствие подобных решений на рынке, простота и удобство использования.

Стек технологий: Adobe Photoshop, Unity 2018.4.34f1(С#)

Сценарий использования:
Установка приложения - отображение на главном экране кнопок “играть”, “выход”, настройки звука. Если пользователь нажимает кнопку “Играть”, он переходит на экран с выбором уровня - выбор уровня (доступного) - переход на обучение по данной методике (комикс) - переход на задание - обучение следующего уровня - уровень с заданием. 

Основные требования к ПО для пользования:
OS: Windows 7 SP1+, 8, 10, 64-bit versions only; Mac OS X 10.12+; Ubuntu 16.04, 18.04, and CentOS 7.
Графический процессор: видеокарта с поддержкой DX10 (версия шейдеров 4.0).

Порядок установки:
Скачивание архива с exe файлом приложения и запуск его

Структура приложения:

Визуальная арифметика.exe - Исполняемый файл проекта.
UnityPlayer.dll- эта DLL содержит весь собственный код движка Unity.
WinPixEventRuntime.dll- Эта DLL включает поддержку профилировщика Windows PIX.
UnityCrashHandler64.exe - обработчик сбоев
Визуальная арифметика_Data - Эта папка содержит все данные, необходимые для запуска проекта.
MonoBleedingEdge - папка с необходимыми библиотеками C # и MonoDevelop для запуска приложения 
Unity.gitignore - файл для скрытия файлов и папок от системы контроля версий Git
DontDestroy - скрипт для музыки, которая играет при переходе с сцены на сцену не прерываясь 
Rotate -  скрипт для вращения вертушки(сейфа) в задании
