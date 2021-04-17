<a id="content"></a>
# Программирование на Python [:top:](https://github.com/pilyay/python-programming-course-by-bioinformatics-institute)

1. [<details open><summary>Операторы. Переменные. Типы данных. Условия</summary>](chapter_1)

	* :green_book: [Общая информация о курсе](#chapter_1.1)
	* :green_book: Введение: программы и Python. Проверка заданий
	* :green_book: Интерактивный режим Python. IPython
	* :green_book: Установка Python на компьютер
	* :green_book: Операции с целыми числами
	* :green_book: Операции с вещественными числами
	* :green_book: Типы данных
	* :green_book: Переменные. Стандартный ввод/вывод
	* :green_book: Логические операции, операции сравнения
	* :green_book: Условия: if, else, elif. Блоки, отступы
	* :green_book: Строки
	* :green_book: Задачи по материалам недели

2. <details open><summary>Циклы. Строки. Списки</summary>

	* :green_book: Цикл while
	* :green_book: Операторы break, continue
	* :green_book: Цикл for
	* :green_book: Строки и символы
	* :green_book: Списки
	* :green_book: Задачи по материалам недели

3. <details open><summary>Функции. Словари. Интерпретатор. Файлы. Модули</summary>

	* :green_book: Функции
	* :green_book: Словари
	* :green_book: Интерпретатор: установка, запуск скрипта
	* :green_book: Файловый ввод/вывод
	* :green_book: Модули, подключение модулей
	* :green_book: Установка дополнительных модулей
	* :green_book: Задачи по материалам недели
	* :green_book: Библиотеки для анализа данных. NumPy
	* :green_book: Библиотека Matplotlib
	* :green_book: Заключение
</details>

---

<a id="chapter_1"></a>
# Операторы. Переменные. Типы данных. Условия
<a id="chapter_1.1"></a>
## Общая информация о курсе [:top:](#content)

### Добро пожаловать!
Мы рады видеть вас на курсе «Программирование на Python». В этом вводном уроке мы расскажем вам о том, что вас ждёт, и дадим рекомендации по прохождению курса. Жмите кнопку «вправо», чтобы перейти к следующему шагу.

### Сначала о формате
Каждая неделя состоит из нескольких уроков, которые представляют собой наборы коротких видео-лекций (от 30 секунд до 5 минут, в редких случаях дольше).

Обычно один урок посвящен обсуждению одного понятия в общем, а один видео-фрагмент внутри урока — одной стороне или детали понятия.

Видео чередуются с простыми тестами, состоящими из одного-двух вопросов для проверки только что услышанного материала.

Внутри одного урока видеофрагменты и тесты на платформе Stepik принято называть шагами (стэпами). В верхней части окна вы можете видеть несколько иконок-квадратов. Это кнопки навигации, позволяющие перемещаться от одного фрагмента видео или тестов к другому. Также можно использовать клавиши «вправо» и «влево» на клавиатуре.

**Перейдите к следующему шагу**, чтобы увидеть тестовое задание в действии.

### Задачи
Важной частью курса является закрепление изученного материала через решение задач. И именно по результатам решения задач вам будет поставлена оценка за курс. На шагах с задачами рядом с полем ответа приводится число баллов, которое вы получите за её решение, а также набранный вами балл.

Все задачи можно решать любое количество раз. За неверные попытки баллы не снижаются, не бойтесь ошибаться! Также, все ваши прошлые решения остаются доступны по ссылке под полем задачи.

Вопрос: как называется этот курс? Чтобы ответить, нажмите на зелёное поле ниже и выберите правильный ответ.

### Wakari и Trinket
В курсе используется онлайн-платформа Wakari, позволяющая работать в интерактивном режиме Python без его установки на локальный компьютер.


В случае высокой загрузки Wakari может стать недоступным. Вместо него можно использовать аналогичный сервис [Сocalc](https://cocalc.com). Так же можно использовать [Trinket.io](https://trinket.io/python/41462f0f16). Он позволяет запускать программы на Python в вашем браузере. У него есть некоторые отличия от Wakari, о которых будет упомянуто отдельно в уроке «Интерактивный режим Python».

### Общие рекомендации по онлайн-курсу
Чтобы все функции видео-плеера (например, ускорение видео) работали корректно, используйте одну из последних версий браузера. Подробнее о поддерживаемых версиях: <http://caniuse.com/#search=mp4>

Несмотря на то, что в курсе есть видео и текстовые материалы, ведите конспект или хотя бы делайте заметки. Так материал будет лучше запоминаться.

При необходимости ставьте видео на паузу. Помните, что в онлайн-курсе материал даётся в более сжатом виде, чем на обычных лекциях. И наоборот: ускоряйте видео, если изложение кажется вам слишком медленным.

Под каждым шагом есть форум для обсуждения. В нём можно (и нужно!) задавать вопросы по материалам и задачам курса, а также помогать другим, если знаете ответ. **Пожалуйста, не выкладывайте свой код и решения задач.** Старайтесь разобраться, в чем проблема, по наводящим вопросам. Формат курса не подразумевает поиск преподавателями ошибок в индивидуальных программах студентов..

При возникновении технических вопросов по курсу пишите на почту online@bioinformaticsinstitute.ru. 



---
<a id="chapter_1"></a>
## Операторы. Переменные. Типы данных. Условия [:top:](#content)
* :green_book: [Код недели](https://onedrive.live.com/?authkey=%21AGzgO67ZttTN6do&cid=334D0964A644C8BA&id=334D0964A644C8BA%211135171&parId=334D0964A644C8BA%211135161&o=OneUp)
* :green_book: [Общая информация о курсе](https://onedrive.live.com/?cid=334D0964A644C8BA&id=334D0964A644C8BA%211135198&parId=334D0964A644C8BA%211135161&o=OneUp)
* :green_book: [Введение: программы и Python. Проверка заданий](https://onedrive.live.com/?cid=334D0964A644C8BA&id=334D0964A644C8BA%211135206&parId=334D0964A644C8BA%211135161&o=OneUp)
	* :blue_book: [Официальный сайт Python](https://www.python.org/)
	* :blue_book: [Официальная документация по Python](https://docs.python.org/3/)
	* :blue_book: [Python в браузере](https://trinket.io/python/41462f0f16)
	* :blue_book: [PyCharm Educational Edition](https://www.jetbrains.com/pycharm-educational/)
	* :blue_book: [PyCharm Community Edition](https://www.jetbrains.com/pycharm/)
	* :blue_book: [Sublime Text 3](http://www.sublimetext.com/3)
	* :blue_book: [Интерактивный учебник языка Python (на русском языке)](http://pythontutor.ru/)
	* :blue_book: [Книга A Byte of Python (EN)](http://www.swaroopch.com/notes/python/)
	* :blue_book: [Книга A Byte of Python (RU)](http://wombat.org.ua/AByteOfPython/)
* :green_book: [Интерактивный режим Python. IPython](https://onedrive.live.com/?cid=334D0964A644C8BA&id=334D0964A644C8BA%211135210&parId=334D0964A644C8BA%211135161&o=OneUp)
* :green_book: [Установка Python на компьютер](https://onedrive.live.com/?cid=334D0964A644C8BA&id=334D0964A644C8BA%211135215&parId=334D0964A644C8BA%211135161&o=OneUp)
* :green_book: [Операции с целыми числами](https://onedrive.live.com/?cid=334D0964A644C8BA&id=334D0964A644C8BA%211135216&parId=334D0964A644C8BA%211135161&o=OneUp)
	* :blue_book: [Деление с остатком](https://ru.wikipedia.org/wiki/Деление_с_остатком)
	* :blue_book: [An Informal Introduction to Python. Numbers](https://docs.python.org/3/tutorial/introduction.html#numbers)
* :green_book: [Операции с вещественными числами](https://onedrive.live.com/?cid=334D0964A644C8BA&id=334D0964A644C8BA%211135222&parId=334D0964A644C8BA%211135161&o=OneUp)
	* :blue_book: [Экспоненциальная запись](https://ru.wikipedia.org/wiki/Экспоненциальная_запись#.D0.9A.D0.BE.D0.BC.D0.BF.D1.8C.D1.8E.D1.82.D0.B5.D1.80.D0.BD.D1.8B.D0.B9_.D1.81.D0.BF.D0.BE.D1.81.D0.BE.D0.B1_.D1.8D.D0.BA.D1.81.D0.BF.D0.BE.D0.BD.D0.B5.D0.BD.D1.86.D0.B8.D0.B0.D0.BB.D1.8C.D0.BD.D0.BE.D0.B9_.D0.B7.D0.B0.D0.BF.D0.B8.D1.81.D0.B8)
* :green_book: [Типы данных](https://onedrive.live.com/?cid=334D0964A644C8BA&id=334D0964A644C8BA%211135224&parId=334D0964A644C8BA%211135161&o=OneUp)
* :green_book: [Переменные. Стандартный ввод/вывод](https://onedrive.live.com/?cid=334D0964A644C8BA&id=334D0964A644C8BA%211135227&parId=334D0964A644C8BA%211135161&o=OneUp)
	* :blue_book: [Использование переменных в python 3](https://www.8host.com/blog/ispolzovanie-peremennyx-v-python-3/) 
	* :blue_book: [PEP8 - стиль кода в языке Python](https://pep8.ru/doc/pep8/)
	* :blue_book: [Динамическая типизация](https://ru.wikipedia.org/wiki/Динамическая_типизация)
* :green_book: [Логические операции, операции сравнения](https://onedrive.live.com/?cid=334D0964A644C8BA&id=334D0964A644C8BA%211135228&parId=334D0964A644C8BA%211135161&o=OneUp)
	* :blue_book: [Built-in Types](https://docs.python.org/3/library/stdtypes.html)
* :green_book: [Условия: if, else, elif. Блоки, отступы](https://onedrive.live.com/?cid=334D0964A644C8BA&id=334D0964A644C8BA%211135233&parId=334D0964A644C8BA%211135161&o=OneUp)
* :green_book: [Строки](https://onedrive.live.com/?cid=334D0964A644C8BA&id=334D0964A644C8BA%211135235&parId=334D0964A644C8BA%211135161&o=OneUp)
* :green_book: Задачи по материалам недели

<a id="chapter_2"></a>
## Циклы. Строки. Списки [:top:](#content)
* :green_book: Цикл while
* :green_book: Операторы break, continue
* :green_book: Цикл for
* :green_book: Строки и символы
* :green_book: Списки
* :green_book: Задачи по материалам недели

<a id="chapter_3"></a>
## Функции. Словари. Интерпретатор. Файлы. Модули [:top:](#content)
* :green_book: Функции
* :green_book: Словари
* :green_book: Интерпретатор: установка, запуск скрипта
* :green_book: Файловый ввод/вывод
* :green_book: Модули, подключение модулей
* :green_book: Установка дополнительных модулей
* :green_book: Задачи по материалам недели
* :green_book: Библиотеки для анализа данных. NumPy
* :green_book: Библиотека Matplotlib
* :green_book: Заключение
