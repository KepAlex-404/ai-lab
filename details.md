class: middle, center, title-slide 

# Системи штучного інтелекту

Осінь 2023 р.

<br><br>
Кочура Юрій Петрович<br>
[iuriy.kochura@gmail.com](mailto:iuriy.kochura@gmail.com) <br>
<a href="https://t.me/y_kochura">@y_kochura</a> <br>


---

class: middle

# Викладач з практик

.center[
.circle.width-40[![](figures/course-details/ykochura.jpg)]
]


.center.bold.larger-x[Кочура Юрій Петрович]
- Кафедра обчислювальної техніки, ФІОТ

---

class: middle

# Опис предмету

.width-100[![](figures/course-details/ai-ua.png)]

???
Штучний інтелект (ШІ) – це галузь комп’ютерних наук, яка зосереджена на створенні систем, що здатні виконувати завдання, які зазвичай потребують людського інтелекту. ШІ використовує методи та алгоритми, які спроектовані для вивчення, моделювання та реалізації інтелектуальних функцій, таких як розпізнавання образів, мовний аналіз та прийняття рішень. Малий та великий бізнес в усьому світі використовує штучний інтелект для вирішення своїх найбільших викликів. Медичні працівники використовують штучний інтелект для більш точної та швидшої діагностики пацієнтів. Підприємства роздрібної торгівлі використовують його, щоб пропонувати клієнтам персоналізований досвід покупок. Автовиробники використовують ШІ, щоб зробити транспортні засоби безпечнішими та ефективнішими. Основні аспекти ШІ включають в себе розробку алгоритмів та навчання систем на основі даних. Сьогодні ШІ є однією з найпотужніших та швидкозростаючих технологій нашого часу.

Ідея штучного інтелекту з'явилася в 1950-х, коли група ентузіастів із галузі інформатики, що тільки зароджувалась, задалися питанням, чи можна змусити комп'ютери «думати», — питанням, яке ми вивчаємо досі. Коротко цю область можна визначити так: автоматизація інтелектуальних завдань, які зазвичай виконують люди. Хоча багато основних ідей виношувалися роками й навіть десятиліттями раніше, «штучний інтелект» остаточно викристалізувався як галузь досліджень у 1956 році, коли Джон Маккарті, на той час молодий доцент кафедри математики Дартмутського коледжу, організував літній семінар.

Відповідно, ШІ - це область, що охоплює машинне навчання і глибоке навчання, а також включає багато підходів, не пов'язані з навчанням. Наприклад, перші програми для гри в шахи працювали за жорстко визначеними правилами, заданими програмістами, і не могли кваліфікуватися як машинне навчання. Довгий час багато експертів вважали, що ШІ рівня людини можна створити, якщо дати програмісту достатній набір явних правил для маніпуляції даними. Цей похід, відомий як символьний ШІ, і являв собою домінуючу парадигму ШІ з 1950-х до кінця 1980-х. Пік його популярності прийшов на бум експертних систем в 1980-х.

Символьний ШІ чудово справлявся з вирішенням чітко визначених логічних завдань, таких як гра в шахи, але, як виявилося, неможливо задати строгі правила для вирішення більш складних, нечітких завдань, таких як класифікація зображень, розпізнавання мови та переклад тексту. На зміну символьному ШІ прийшов новий підхід: машинне навчання.

---


class: middle

# Навчальна мета

- Навчитись визначати типи проблем до яких застосовуються методи штучного інтелекту.
- Дізнатись про основні методи та інструменти, необхідні для навчання моделей ШІ.
- Отримати досвід розробки простих систем, які навчаються на досвіді.


---


# Програмне забезпечення

Цього семестру лекції проходять онлайн в .bold[*BigBlueButton*] at  [https://bbb.comsys.kpi.ua/b/yur-h7j-fwv-yhv](https://bbb.comsys.kpi.ua/b/yur-h7j-fwv-yhv)

.center.width-90[![](figures/course-details/bbb.png)]

---

class: middle 

# Матеріали лекцій


-  HTML та PDF формат
- Надсилатись будуть після занять у телеграм групу

<!-- .center.width-80[![](figures/course-details/github.png)] -->

---

class: middle

# Підручники

 Для всеосяжного ознайомлення з ШІ:

.grid[
.kol-1-3[
[.center.width-80[![](figures/course-details/deep-learning-book-goodfellow-cover.jpg)]](https://www.deeplearningbook.org/)
.center[Безкоштовна]
]

.kol-1-3[
[.center.width-95[![](figures/course-details/Neural-Networks-and-Deep-Learning.png)]](http://neuralnetworksanddeeplearning.com/index.html)
.center[Безкоштовна]
]

.kol-1-3[
[.center.width-80[![](figures/course-details/deep-learning-with-python-second-edition-chollet.png)]](https://www.manning.com/books/deep-learning-with-python-second-edition?query=deep/)
.center[Безкоштовний перегляд]
  ]
]

---


class: middle

# Обговорення

Оголошення та обговорення відбуватимуться в Telegram

- Задавайте свої запитання.
- Не соромтесь!

---

class: middle

## Практичні роботи

Вправи, які допоможуть познайомитись з предметом.

---

class: middle

# Оцінювання

- 60%  &nbsp;&emsp; Практичні роботи (30% кожна)
- 40%  &nbsp;&emsp; Екзамен

**Примітка!** Допуск до здачі екзамену:<br>
  Практичні роботи $ \geq 42\%$

---

class: end-slide, center
count: false

.larger-xx[Почнемо!]