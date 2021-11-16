Что будем автоматизировать: 
* поиск страницы профессии и формы записи на ней;
* заполнение формы записи.

1. Поиск страницы профессии и формы 

1.1 Открыть https://netology.ru/

1.2. Нажать "Каталог курсов" 

![img_1.png](img_1.png)

Далее - "Программирование", "Тестировщик ПО" 

![img_2.png](img_2.png)

Форма записи на странице курса

![img_3.png](img_3.png)

1.3. Нажать "Каталог курсов", далее - "Программирование", "Тестировщик ПО", 
проскроллить страницу до конца вниз к форме записи на курс. 


![img_4.png](img_4.png)

1.4. Нажать NEO 

![img_5.png](img_5.png)

Далее - "Тестировщик ПО"

 ![img_6.png](img_6.png)

Найти форму на странице курса. 

1.5. Перейти в самый низ главной страницы сайта 

![img_7.png](img_7.png)

Далее - "Программирование", "Тестировщик ПО", найти форму на странице.

1.6. На главной странице блок "Актуальные темы"

![img_8.png](img_8.png)

Далее - "Программирование", "Тестировщик ПО" 

![img_9.png](img_9.png)
 
Найти форму на странице курса.

1.7. Всплывающая кнопка "Записаться" на странице курса Тестировщик. 

![img_10.png](img_10.png)

1.8. кнопка записаться на поле "Гарантия возврата денег" на странице Тестировщик ПО 

![img_11.png](img_11.png)

3. Автоматизируемые сценарии: 
- поиск формы -8 сценариев;
- заполнение формы: 
- -сценарии позитивные: 
* валидные имя и телефон (учесть короткие имена из двух букв, имена через дефис, имена из 2 и более слов, лишние пробелы при вводе),
--сценарии негативные:
* невозможность отправки пустой формы, формы с незаполненным одним полем,
* невозможность ввода символов (кроме дефиса) в поле Имя, 
* невозможность отправки формы с введенными цифрами и буквами кроме кириллицы и латиницы в поле Имя,
* невозможность отправки формы с невалидным номером телефона (короче длинны поля).


3. Инструменты:

- ПК с установленным ПО: JDK, IntellijIDEA с фреймворками Maven или Gradle, JUnit или TestNG, Selenide, плагин Lombok,  выход в сеть Интернет.

4. Необходимые данные/разрешения/доступы: 

- разрешение на автоматизированное тестирование сайта;
- доступ к базе данных;
- генератор рандомных данных.

5. Риски автоматизации:

- изменение в структуре сайта;
- изменение формы записи;
- изменение Css-селекторов полей;
- недостаточная генерация валидных данных для тестирования (не учтены уникальные имена).

6. Специалисты: 

- тестировщик ПО с навыками написания авто-тестов для UI, работы с СУБД;
- product-manager(?, кто-то же должен выдать доступ к БД).

7. Затрудняюсь ответить. 13-15 рабочих часов(?).


 

