# Представление результатов

| ID | Назначение/название | Сценарий | Ожидаемый результат | Фактический результат | Оценка |
|:---:|:---:|:---|:---|:---|:---|
|1|Выбор контакта|Нажать на элемент выбора контакта|Всегда должен отображаться тот контакт, который выбрал тестировщик| Контакт, который был выбран отображается | Задание полностью выполнено|
|2|Добавление контакта|Нажать на кнопку "+" , ввести все данные о контакте, нажать кнопку "Добавить"|Всегда должен добавляться контакт, который ввел тестировщик| После ввода контакт и нажатии на "+" контакт успешно добавляется | Задание полностью выполнено |
|3|Вывод|Выбрать контакт в элементе выбора|Всегда должны правильно отображаться данные о контакте| При выборе контакта, контакт отображает  данные правильно | Задание полностью выполнено |
|4|Соответствие шрифта не менее 14 пт|Открыть приложение в среде Android Studio, открыть файл activity_main, нажать левым щелчком мыши на элемент GUI, в котором написан какой-либо текст, проверить в свойстве Font размер шрифта, Повторить пункты 3-4 для всех элементов GUI с текстом|По умолчанию должен быть шрифт не менее 14pt| Отображается нужный шрифт | Задание полностью выполнено |
|5|Корректная работа приложения|Нажать на кнопку "+", не вводить данные, нажать кнопку "добавить"|Не должно реагировать на нажатие при пустых полях| при попытке добавления пустых данных ничего не происходит | Задание полностью выполнено |
|6|Контрастность фона окна функциональным элементам окна|Проверить, являются ли функциональные элементы контрастными фону окна|Функциональные элементы должны быть контрастны фону окна.| Функциональные схемы являются контрастными фону окна | Задание полностью выполнено |
|7|Корректный ввод данных|При добавлении контакта ввести возраст больше 100|Не должно вносить данные в базу с таким возрастом| При добавлении контакта с возрастом более 100 происходит обычное добавление контакта | Задание не выполнено |

  Вывод: Приложение выполнено хорошо, но не совершенно. Требуется доработка в добавлении контакта с возрастом больше 100. Кроме этого данное приложение следует проверить на адаптивность. Нужно протестировать его на разных версиях андроида с различным размером экрана. Также требуется проверка  touch-интерфейса и корректную реакцию на SMS, MMS, звонки, оповещения других приложений, выключение устройсва, изъятие аккумулятора, разрядка устройства. Кроме того требуется проверка поля ввода приложения на количество возможных вводимых символов.

Успешно выполненные тесты: 6 из 7
