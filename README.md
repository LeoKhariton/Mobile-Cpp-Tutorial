# OPRIC - ОПРИС - Электронное учебное пособие по программированию на языке С/С++
## Аннотация
Это кроссплатформенное приложение, представляющее собой электронное учебное пособие (ЭУП) по основам языка С/С++.  
В приложении собраны лекции, тесты и практики.  
Есть возможность вести статистику прохождения тестов.  
![](https://github.com/LeoKhariton/Opric/blob/main/Test/видео.gif)  
## Установка
Начиная с версии 2.0, приложение разрабатывалось с помощью кроссплатформенных фрейморков, поэтому его можно запустить на широком круге устройств:
| Версия | Поддерживаемые платформы<br/>(минимальная версия) |
| :--: | -- |
| 0 | Windows 7 |
| [1](https://github.com/LeoKhariton/Mobile-Cpp-Tutorial/releases) | &#9989;**Android** 6.0 (API 23)<br/>**iOS** 10<br/>&#9989;**Windows** 8.1 (необходима поддержка **UWP**)<br/>**macOS** Mojave (10.14) |
| 2 | **Android** 5.0 (API 21)<br/>**iOS** 11<br/>&#9989;**Windows** 10<br/>**macOS** 10.15 |
### Android
Скачайте установочный файл `.apk` и запустите его на устройстве Android.  
Возможно, при установке приложение потребует дополнительное разрешение - доступ в интернет.  
### Windows 11
1. Загрузить файл-установщик с расширением `.msix`.
#### Установка сертификата
2. Для того, чтобы установить приложение, необходимо сначала установить сертификат. Для этого откройте окно свойств установочного файла и перейдите к вкладке "Цифровые подписи". Выберите единственную подпись из списка и нажмите "Сведения":  
![w1](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w1.png)  
3. В открывшемся окне "Состав цифровой подписи" выберите "Просмотр сертификата":  
![w2](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w2.png)  
4. В открывшемся окне нажмите "Установить сертификат":  
![w3](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w3.png)  
5. Выберите установку сертификата для всего локального компьютера и нажмите "Далее" от имени администратора:  
![w4](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w4.png)  
6. Выберите "Доверенные корневые центры сертификации", нажмите "ОК":  
![w5](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w5.png)  
7. А затем "Далее" и "Готово". Появится уведомление, оповещающее об успешной установке сертификата.  
8. Закройте окно свойств и запустите установщик.
### Windows 10
9. Установить с официального сайта Microsoft [Windows App SDK](https://learn.microsoft.com/ru-ru/windows/apps/windows-app-sdk/downloads).
10. Первый раз необходимо открыть программу от имени администратора.
## Эксплуатация
После открытия приложения загрузится главная страница - страница, на которой можно выбрать раздел. В верхнем левом углу находится меню-"гамбургер".  
![a9](https://github.com/LeoKhariton/Opric/blob/main/Test/Слайд1.PNG)  
### Вкладка "Разделы"
Кликнув по соответствующему названию раздела, открывается страница с вкладками, на которой располагается содержимое раздела. На нижних вкладках можно выбрать "Лекцию", "Тест" или "Практическое занятие". На верхних вкладках можно выбрать конкретный подраздел лекции или практической работы. После открытия вкладки "Тест" появится начальное уведомление, оповещающее пользователя о начале тестирования. При положительном ответе начнется тестирование, при отрицательном - совершится переход к началу раздела. Вопросы в тесте загружаются в случайном порядке. Отвечать можно, нажимая на кнопки с соответствующими вариантами ответов. При верном ответе кнопка загорится зеленым цветом, при неверном - красным. После нажатия на кнопку "Завершить сейчас!", ответа на последний вопрос теста либо по окончании времени, отведенного для тестирования, подводятся его итоги.  
![a9](https://github.com/LeoKhariton/Opric/blob/main/Test/Слайд2.PNG)  
### Вкладка "Личный кабинет"
При первом посещении этой вкладки приложение предложит заполнить регистрационную форму, после чего будет доступен личный кабинет со статистикой изучения материала и прохождения тестов, а на "главной" вокруг иконок разделов будет отображаться статистика прохождения теста по соответствующей теме.  
![a9](https://github.com/LeoKhariton/Opric/blob/main/Test/Слайд3.PNG)  
### Вкладка "Настройки"
В разделе "Настройки" можно выбрать тему приложения. Например, при включении темной темы:  
![a9](https://github.com/LeoKhariton/Opric/blob/main/Test/Слайд4.PNG)  
![a9](https://github.com/LeoKhariton/Opric/blob/main/Test/Слайд5.PNG)  
*Примечание*  
Во избежание конфликтов стилей желательно, чтобы тема приложения соответствовала системной.  
В нижней части всплывающей панели расположены элементы для отправки отзывов и связи с разработчиком.  
***
Если вы нашли ошибку, просьба сообщить о ней *максимально подробно*, воспользовавшись формой для отправки отзывов. Необходимо описать ситуацию, которая привела к ошибке, и саму ошибку, желательно приложив скриншот. **Важно сообщить об ошибке как можно подробнее, чтобы разработчики могли повторить ситуацию, приведшую к ошибке и исправить ее.**  
Другой вариант сообщения об ошибке - сформировать подробный отчет о ней в виде вопроса на вкладке "Issues" **на странице данного репозитория**. Там также следует описать саму обишку, по возможности приложить скриншот и описать шаги для ее воспроизведения.  
## Публикации и работы ##
1. Международная конференция ["Новые информационные технологии и системы" (НИТиС-2022)](https://elibrary.ru/item.asp?id=50454558&pff=1), Пенза.
2. [Всеросскийская конференция Нижневартовского государственного университета](https://konference.nvsu.ru/konffiles/383/Stud_konf_CH3_Informacionnye_tehnologii.pdf).  
3. [Региональный научно-практический семинар им. Л.В. Широкова](https://elibrary.ru/item.asp?id=54087229), Арзамас.
4. Международная конференция "Инновационные процессы в науке и технике XXI века", Нижневартовск.  
## Апробация и внедрение
## Защита интеллектуальной собственности
[Свидетельство о регистрации программы для ЭВМ № 2023618889](https://www.elibrary.ru/item.asp?id=53819195)  
## История версий
### Версия 0
При установке необходимо загрузить весь образовательный контент отдельно и распаковать его в `C:\faust\`.  
![a9](https://github.com/LeoKhariton/Opric/blob/main/Version%20History/v0-WinForms.png)
### Версия 1
#### Windows
Это приложение является универсальным приложением Windows (т.е. доступно как на десктопных платформах, так и на Windows Phone, и даже на очках смешанной реальности HoloLens, которые также функционируют на базе универсальной платформы Windows). Поэтому установочный файл имеет не привычное расширение .exe (как у программ, разработанных на платформах WPF или Windows Forms), а `.APPX` или `.APPXBUNDLE`.  
#### Что делать, если компьютер не распознает файл .appx или .appxbundle?
Бывают случаи, когда компьютер с ОС Windows 10 не распознает файлы `.appx` и `.appxbundle` как установочные, и предлагает открыть их с помощью какой-то программы.  
В этом случае необходимо открыть Power Shell и ввести следующую команду:
```md
add-appxpackage [путь к установочному файлу]
```
Если все необходимые пакеты установлены, то эта команда приведет к запуску установки приложения (важно, что **сертификат должен быть предварительно установлен вручную тем же способом, который описан выше в пп. 2-9**). В противном случае выведется сообщение об ошибке, возникшей в ходе устновки. Чаще всего это может быть связано с отсутствием каких-либо пакетов (например, пакета поддержки XAML необходимой версии). Их можно установить либо вручную, либо с обновлением Windows, либо с помощью Visual Studio 2019 (для этого обычно достаточно обновить VS до последней версии или подключить пакет разработки приложений для универсальной платформы Windows).
