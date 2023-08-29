## План тестирования возможности записаться на обучение профессии «Тестировщик ПО»

### 1. Перечень автоматизируемых сценариев (26 штук).

#### Необходимо протестировать разные методы открытия формы регистрации для незарегистрированного пользователя:

1. Открыть главную страницу сайта netology.ru —> В верхней части нажать на кнопку “Каталог курсов” —> Нажать на кнопку “все курсы” —> На главной форме сайта найти “Тестировщик ПО” и войти в данный пункт —> Нажать на кнопку “Записаться” в верхней части страницы —> Опуститься чуть ниже к форме заполнения полей для регистрации.
   
2. Открыть главную страницу сайта netology.ru —> В верхней части нажать на кнопку “Каталог курсов” —> Нажать на кнопку “все курсы” —> На главной форме сайта найти “Тестировщик ПО” и войти в данный пункт —>  Опуститься в самый низ страницы к форме заполнения полей для регистрации.
   
3. Открыть главную страницу сайта netology.ru —> В верхней части нажать на кнопку “Каталог курсов” —> Нажать на кнопку “все курсы” —> На главной форме сайта найти “Тестировщик ПО” и войти в данный пункт —> Нажать на кнопку “Записаться” в верхней части страницы —> Опуститься чуть ниже к форме заполнения полей для регистрации.
   
4. Открыть главную страницу сайта netology.ru —> В верхней части нажать на кнопку “Каталог курсов” —> Нажать на кнопку “все курсы” —> На главной форме сайта найти “Тестировщик ПО” и войти в данный пункт —> Опуститься в самый низ страницы к форме заполнения полей для регистрации.
   
5. Открыть главную страницу сайта netology.ru —> Чуть ниже найти и нажать на кнопку “Программирование” —> Нажать на кнопку “все курсы” —> Найти “Тестировщик ПО” и войти в данный пункт —> Нажать на кнопку “Записаться” в верхней части страницы —> Опуститься чуть ниже к форме заполнения полей для регистрации.
   
6. Открыть главную страницу сайта netology.ru —> Чуть ниже найти и нажать на кнопку “Программирование” —> Нажать на кнопку “все курсы” —> Найти “Тестировщик ПО” и войти в данный пункт —> Опуститься в самый низ страницы к форме заполнения полей для регистрации.
   
7. Открыть главную страницу сайта netology.ru —> Найти кнопку “Пройти тест” для прохождения профориентационного теста —> Нажать кнопку “Пройти тест” и необходимым образом пройти его, чтобы система подсказала “Тестировщик ПО” —> Нажать на кнопку “попробовать бесплатно” —> Нажать на кнопку “Записаться” в верхней части страницы —> Опуститься чуть ниже к форме заполнения полей для регистрации.
   
8. Открыть главную страницу сайта netology.ru —> Найти кнопку “Пройти тест” для прохождения профориентационного теста —> Нажать кнопку “Пройти тест” и необходимым образом пройти его, чтобы система подсказала “Тестировщик ПО” —> Нажать на кнопку “попробовать бесплатно” —> Опуститься в самый низ страницы к форме заполнения полей для регистрации.
   
#### Необходимо протестировать разные методы открытия формы регистрации для зарегистрированного пользователя по тем же 8 пунктам. 

1. Все пункты останутся такими же, только в начале каждого пункта нужно будет провести аутентификацию пользователя.

#### Тестирование формы регистрации:

1. Тестирование поля “Студент” на валидные значения.
   
2. Тестирование поля “Студент” на невалидные значения.
   
3. Тестирование поля “телефон” на валидные значения.

4. Тестирование поля “телефон” на невалидные значения.

5. Тестирование поля “e-mail” на валидные значения.

6. Тестирование поля “e-mail” на невалидные значения.

### 2. Перечень используемых инструментов с обоснованием выбора.

1. Автоматизированное тестирование с использованием среды IDEA для языка Java.

2. Использование JUnit5 как основу для написания тестов.

3. Проект на базе gradle для просмотра работы тестов.

4. Использование Selenide для тестирования страниц сайта (проще и быстрее в работе, чем Selenium).


### 3. Перечень необходимых разрешений, данных и доступов.

1. Необходим доступ к тестовой базе данных, чтобы данные из заполненных форм отправлялись не на основной сервер.
   
2. Необходимо получить список ответов на вопросы для прохождения профориентационного теста, чтобы после прохождения была подсказана профессия тестировщика ПО.
   
3. Получить информацию о том, что должно происходить по нажатии на кнопку “Записаться” в форме регистрации.
   
4. Получить информацию о том, что должно происходить по нажатии на кнопку “Получить консультацию” в форме регистрации.
   
5. Информация от разработчиков о допустимых значениях полей в форме регистрации.
   
6. Получить тестовые данные для ввода в форму регистрации, если таковые имеются.

### 4. Перечень и описание возможных рисков при автоматизации.

1. Риск остановки тестирования в случае, если не был предоставлен доступ к БД, куда можно отправлять данные из форм регистрации.

2. Риск остановки тестирования в случае, если сервер сайта перестанет быть доступным (минимальный риск).

3. Риск остановки тестирования в случае, если сервер БД перестанет быть доступным.

### 5. Перечень необходимых специалистов для автоматизации.

Специалист по автоматизированному тестированию уровня junior - middle.

### 6. Интервальная оценка с учётом рисков в часах.

3-6 часов. 3 - в случае c middle AQA; 6 - в случае c junior AQA