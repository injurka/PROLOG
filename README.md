# PROLOG

<style>
.back-propagation {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

</style>

# 1. Представление правил в продукционном программировании

Продукционная МПЗ (МПЗ - модель представления знаний(или правил))

В основе продукционной модели представления знаний находится конструктивная часть, продукция(правило):

<hr/>
IF <условие>, THEN <действие>
<hr/>

Продукция состоит из двух частей: условие — антецендент, действие — консеквент. Условия можно сочетать с помощью логических функций AND, OR.
Антецеденты и консеквенты составленных правил формируются из атрибутов и значений.
Пример: <br/>

<hr/>
IF температура реактора подымается THEN добавить стержни в реактор
<hr/>

В базе данных продукционной системы хранятся правила, истинность которых установлена к за ранее при решении определенной задачи.  
Правило срабатывает, если при сопоставлении фактов, содержащихся в базе данных с антецедентом правила, которое подвергается проверке, имеет место совпадение. Результат работы правила заносится в базу данных.

# 2. Семантические и ассоциативные сети

<h2>Семанти́ческая сеть</h2>

<b>Семанти́ческая сеть</b> — информационная модель предметной области, имеет вид ориентированного графа.
Вершины графа соответствуют объектам предметной области, а дуги (рёбра) задают отношения между ними.
Объектами могут быть: <u>понятия, события, свойства, процессы</u>. Таким образом, <b>семантическая сеть</b> — это один из способов представления знаний.

В названии соединены термины из двух наук:

1. <b>Семантика</b> в языкознании изучает смысл единиц языка, а сеть в математике представляет собой разновидность графа — набора вершин, соединённых дугами (рёбрами), которым присвоено некоторое число. В семантической сети роль вершин выполняют понятия базы знаний
2. <b>Дуги</b> (причем направленные) задают отношения между ними. Таким образом, семантическая сеть отражает семантику предметной области в виде понятий и отношений.

Неправильно приравнивать друг другу понятия «Семантическая сеть» и «Семантическая паутина». Хотя эти понятия не эквивалентны, тем не менее, они связаны.

- <h4>Структура</h4>
    Математика позволяет описать большинство явлений в окружающем мире в виде логических высказываний. Семантические сети возникли как попытка визуализации математических формул. Основным представлением для семантической сети является граф.
    Однако не стоит забывать, что за графическим изображением непременно стоит строгая математическая запись и что обе эти формы отображают одно и то же.

- <h4>Графическое представление</h4>
    Основной формой представления семантической сети является граф.
    Понятия семантической сети записываются в овалах или прямоугольниках и соединяются стрелками с подписями — дугами.
    Это наиболее удобно воспринимаемая человеком форма. Её недостатки проявляются,
    когда мы начинаем строить более сложные сети или пытаемся учесть особенности естественного языка. Схемы семантических сетей,
    на которых указаны направления навигационных отношений, называют картами знаний, а их совокупность,
    позволяющая охватить большие участки семантической сети, атласом знания.

- <h4>Математическая запись</h4>
    В математике граф представляется множеством вершин V и множеством отношений между ними E.
    Используя аппарат математической логики, приходим к выводу,
    что каждая вершина соответствует элементу предметного множества, а дуга — предикату.

- <h5>Лингвистическая запись</h5>
    В лингвистике отношения фиксируются в словарях и в тезаурусах. В словарях в определениях через род и видовое отличие родовое понятие занимает определённое место.
    В тезаурусах в статье каждого термина могут быть указаны все возможные его связи с другими родственными по теме терминами.
    От таких тезаурусов необходимо отличать тезаурусы информационно-поисковые с перечнями ключевых слов в статьях, которые предназначены для работы дескрипторных поисковых систем.

<h2>Ассоциативная сеть</h2>

<b>Ассоциативная сеть</b> - основное отличие ассоциативной сети от семантической в том, что мы указываем не смысл (сущность) связи между объектами, а просто говорим об их ассоциировании,
о силе, уровне ассоциаций. Под ассоциацией понимается семантическая репрезентативность в смысле.
При этом надо различать индивидуальные, настраиваемые модели ассоциаций (и их объединение в групповые) и усредненные (статистические),
такие как, например, статистики запросов в поисковых машинах. Кроме этого, следует различать модели ассоциаций непосредственно субъекта и модель передачи знаний между субъектами.

# 3. Фреймовая модель представления знаний

<b>Фреймовая модель представления знаний</b> – была предложена М.Минским в 1979 г. как структура знаний для восприятия пространственных сцен.
Фреймом называется также и формализованная модель для отобра­же­ния образа.

В качестве идентификатора фрейму присваивается имя фрей­ма. Это имя должно быть единственным во всей фреймовой системе.

Фрейм имеет определенную внутреннюю структуру, состоящую из мно­­жества элементов, называемых слотами, которым также присва­и­ва­ют­ся имена.
За слотами следуют шпации, в которые помещают данные, представляющие текущие значения слотов.
Каждый слот в свою очередь представляется опре­де­ленной струк­турой данных.
В значение слота подставляется конкретная инфор­ма­ция, относящаяся к объекту, описываемому этим фреймом.

Модель фрейма является достаточно универсальной, поскольку позволяет отобразить все многообразие знаний о мире:

- через фреймы-структуры, для обозначения объектов и понятий (заем, залог, вексель);
- через фреймы-роли (менеджер, кассир, клиент);
- через фреймы-сценарии (банкротство, собрание акционеров, празднование именин);
- через фреймы-ситуации (тревога, авария, рабочий режим устройства) и др.

<u>Основным преимуществом фреймов</u> как модели пред­став­ления знаний является то, что она отражает концептуальную основу ор­ганизации па­мяти чело­века, а также ее гибкость и наглядность. Наиболее ярко дос­то­ин­ства фреймовых систем представления знаний проявляются в том слу­чае, если родовидовые связи изменяются нечасто и предметная область насчитывает немного исключений. Во фреймовых системах данные о ро­до­­видовых связях хранятся явно, как и знания других типов. Значения сло­тов представляются в системе в единственном экземпляре, поскольку вклю­чаются только в один фрейм, описывающий наиболее понятия из всех тех, которые содержит слот с данным именем. Такое свойство систем фрей­мов обеспечивает экономное размещение базы знаний в памяти ком­пью­тера. Еще одно достоинство фреймов состоит в том, что значение лю­бо­го слота может быть вычислено с помощью соответствующих процедур или найдено эвристическими методами. То есть фреймы позволяют ма­ни­пу­лировать как декларативными, так и процедурными знаниями.

<u>К недостаткам фреймовых систем</u> относят их относительно высокую сложность, что проявляется в снижении скорости работы механизма вы­во­да и увеличения трудоемкости внесения изменений в родовую иерар­хию. Поэтому при разработке фреймовых систем уделяют наглядным способам отображения и эффективным средствам редактирования фреймовых структур.

# 4. Обучение сети по методу обратного распространения ошибки

<b>Алгоритм обратного распространения ошибки</b> — популярный алгоритм обучения нейронных сетей прямого распространения (многослойных персептронов). Относится к методам обучения с учителем, поэтому требует, чтобы в обучающих примерах были заданы целевые значения. Также является одним из наиболее известных алгоритмов машинного обучения

<b>Персептрон</b> - математическая или компьютерная модель восприятия информации мозгом

Основная идея этого метода состоит в распространении сигналов ошибки от выходов сети к её входам, в направлении обратном прямому распространению сигналов в обычном режиме работы. Барцев и Охонин предложили обобщающий метод («принцип двойственности»), применимый к более широкому классу систем, включая системы с запаздыванием, распределённые системы.

<div class="back-propagation">
<img src="./assets/back-propagation.png">
Вот кароче формула делайте с ней че хотите
</div>  
<br/>

для вычисления величин коррекции весов нейронов в ее скрытых слоях, где
k
— число выходных нейронов сети,
y
— целевое значение,
y
′
— фактическое выходное значение. Алгоритм является итеративным и использует принцип обучения «по шагам» (обучение в режиме on-line), когда веса нейронов сети корректируются после подачи на ее вход одного обучающего примера.

На каждой итерации происходит два прохода сети — прямой и обратный. На прямом входной вектор распространяется от входов сети к ее выходам и формирует некоторый выходной вектор, соответствующий текущему (фактическому) состоянию весов. Затем вычисляется ошибка нейронной сети как разность между фактическим и целевым значениями. На обратном проходе эта ошибка распространяется от выхода сети к ее входам, и производится коррекция весов нейронов в соответствии с правилом:

<hr/>
Таким образом, алгоритм использует так называемый стохастический градиентный спуск, «продвигаясь» в многомерном пространстве весов в направлении антиградиента с целью достичь минимума функции ошибки.

На практике обучение продолжают не до точной настройки сети на минимум функции ошибки, а до тех пор, пока не будет достигнуто достаточно точное его приближение. Это позволит, с одной стороны, уменьшить число итераций обучения, а с другой — избежать переобучения сети.

<hr/>

# 5. Понятие, и особенности интеллектуальных информационных систем

<b>Интеллектуальная информационная система</b> (ИИС) - комплекс программных, лингвистических и логико-математических средств для реализации основной задачи – осуществления поддержки деятельности человека и поиска информации в режиме продвинутого диалога на естественном языке. ИИС являются разновидностью интеллектуальной системы, а также одним из видов информационных систем.

Для интеллектуальных информационных систем характерны
следующие особенности:

- развитые коммуникативные способности;
- умение решать сложные плохо формализуемые задачи;
- способность к самообучению;
- адаптивность.

Коммуникативные способности ИС характеризуют способ
взаимодействия (интерфейса) конечного пользователя с системой, в
частности возможность формулирования произвольного запроса в
диалоге с ИС на языке, максимально приближенном к естественному.

# 6. Системы, основанные на знаниях

В литературе существуют разные определения термина <b>знание</b>. Следует иметь ввиду, что речь идет не о знаниях вообще, а о том, что понимается под этим термином именно в компьютерных системах, в ИИС.

Так, для знаний дается следующее определение:

<b>Знания</b> – это закономерности предметной области (принципы, связи, законы), полученные в результате практической деятельности и профессионального опыта, позволяющие специалистам ставить и решать задачи в этой области.

Часто определяют понятие <u>знания</u> отличиями от понятия <u>данные</u>.

<b>Данные</b> – это отдельные факты, характеризующие объекты, процессы и явления предметной области, а также их свойства.

Сравнение функций данных и знаний позволяет дать следующее, достаточно общее определение.

<b>Знания</b> (в компьютерной системе) – закодированные некоторым образом сведения об объектах предметной области, их взаимосвязях и особенностях поведения, а также о способах решения задач. Эти сведения в условиях, характеризуемых некоторыми данными, служат инструментом решения задач.

То есть можно сказать, что <u>знания</u> – это инструмент решения задач, а <u>данные</u> - информационное обеспечение такого решения.

<b>Знания</b> – это высокоструктурированные сведения, самодостаточные, не требующие дополнительных программ для интерпретации. Знания обладают семантикой (смыслом) и прагматикой (руководством к действию) в контексте определенной задачи. Данные – это конкретные значения атрибутов объектов, процессов или отношений (констант и переменных, числовых и символьных).

Так, в компьютере могут присутствовать знания о временах года, о том, когда в данном городе летом начинает темнеть, о том, какие районы города и в какое время считаются небезопасными и т.п. Конкретная ситуация может характеризоваться такими данными, как время года, время суток, место нахождения человека. «Наложение» этих данных на знания может привести к суждению о том, что в данном месте в данное время находиться этому человеку опасно (и насколько, опасно). В более сложном случае вывод об опасности нахождения человека в сложившейся ситуации может продолжиться поиском и предложением вариантов действий для этого человека, в том числе, с учетом его цели и его предпочтений.

Классификация знаний выполняется по разным признакам. По характеру и трудности выявления и последующей формализации знаний в компьютере их разделяют на два типа:

- знания 1-го рода (называют еще артикулируемые). Это знания, которые хорошо представляются в виде текстов. Они, соответственно, воплощены в разных учебниках, документах, технологических картах, рекомендациях и т.п.;

- знания 2-го рода (неартикулируемые). Эти знания отражают индивидуальный опыт решения профессиональных задач, они трудно формализуются и, как правило, непредставимы или труднопредставимы с помощью обычных текстов. Эти знания представляются в ИИС с помощью специальных моделей представления знаний, позволяющих не только закодировать их в памяти компьютера. Но и использовать для имитации рассуждения и автоматизированном выводе решений.

По степени объективности знаний они разделяются на глубинные (общепризнанные, отражающие объективные закономерности) и эмпирические, опытные, которые отражают опыт отдельного человека или коллективов людей.

В зависимости от того, что характеризуют знания, они разделяются на фактуальные (декларативные, предметные знания) и процедурные (операционные). Первые – это описания фактов и явлений, а также взаимосвязей между ними. Вторые есть описания способов действий, которые возможно при манипулировании фактами для достижения поставленных целей. Если фактуальные знания отвечают на вопрос «Что (делать)?», то процедурные – на вопрос «Как (как делать)?»

В ИИС различают также знания коллективные и знания индивидуальные. Индивидуальные знания имеют особое значение в экспертных системах, в системах принятия решений, имитирующих рассуждения эксперта в ходе решения задач и рассуждения ЛПР в ходе анализа и выбора альтернатив.

При представлении знаний в ИИС выделяют также термин метазнания – это знания о знаниях, о том, как взаимосвязаны отдельные сегменты знаний между собой, о порядке их использования в процессе вывода решений.

Появление систем, основанных на знаниях (СОЗ), стало важным событием в развитии искусственного интеллекта. Основанные на экспертных знаниях системы (экспертные системы), явились первым примером того, что ИИ – это не только исследования или компьютерные игры, но это и реальный бизнес, это системы, которые могут приносить их пользователям дополнительные доходы, исчисляемые миллионами.

# 7. Модели представления знаний

Распространены четыре основных МПЗ:

- Продукционная МПЗ
- Семантическая сеть МПЗ
- Фреймовая МПЗ
- Формально логическая МПЗ

<h2>1. Продукционная МПЗ</h2>

В основе продукционной модели представления знаний находится конструктивная часть, продукция(правило):

> IF <условие>, THEN <действие>

Продукция состоит из двух частей: условие — антецендент, действие — консеквент. Условия можно сочетать с помощью логических функций AND, OR.

Антецеденты и консеквенты составленных правил формируются из атрибутов и значений.

Пример:

> IF температура реактора подымается THEN добавить стержни в реактор

В базе данных продукционной системы хранятся правила, истинность которых установлена к за ранее при решении определенной задачи. Правило срабатывает, если при сопоставлении фактов, содержащихся в базе данных с антецедентом правила, которое подвергается проверке, имеет место совпадение. Результат работы правила заносится в базу данных.

<h2>2. Семантическая сеть МПЗ</h2>

В основе продукционной модели лежит ориентированный граф.  
Вершины графа — понятия, дуги — отношения между понятиями.

Особенностью является наличие трех типов отношений:

- класс — подкласс
- свойство — значение
- пример элемента класса

По количеству типов отношений выделяют однородные и неоднородные семантические сети. Однородные имею один тип отношения между всеми понятиями, следовательно, не однородные имею множество типов отношений.

Все типы отношений:

- часть — целое
- класс — подкласс
- элемент — количество
- атрибутивный
- логический
- лингвистический

<h2>3. Фреймовая МПЗ</h2>

Предложил Марвин Мински в 1970 году. В основе фреймовой модели МПЗ лежит фрейм. <b>Фрейм</b> — это образ, рамка, шаблон, которая описывает объект предметной области, с помощью слотов. <b>Слот</b> — это атрибут объекта. Слот имеет имя, значение, тип хранимых данных, демон. <b>Демон</b> — процедура автоматически выполняющаяся при определенных условиях. Имя фрейма должно быть уникальным в пределах одной фреймовой модели. Имя слота должно быть уникальным в пределах одного фрейма.

Слот может хранить другой фрейм, тогда фреймовая модель вырождается в сеть фреймов.

<h2>4. Формально логическая МПЗ</h2>

В основе формально логической МПЗ лежит предикат первого порядка. Подразумевается, что существует конечное, не пустое множество объектов предметной области. На этом множестве с помощью функций интерпретаторов установлены связи между объектами. В свою очередь на основе этих связей строятся все закономерности и правила предметной области. Важное замечание: если представление предметной области не правильное, то есть связи между объектами настроены не верно или не в полной мере, то правильная работоспособность системы будет под угрозой.

Пример:

> A1 = <идет дождь> A2 = <небо в тучах> A3 = <солнечно>
> \
> IF A1 AND A2 THEN <взять зонтик>

<i>Важно</i>: Стоит заметить, что формально логическая МПЗ схожа с продукционной. Частично это так, но они имеют огромную разницу. Разница состоит в том, что в продукционной МПЗ не определены никакие связи между хранимыми объектами предметной области.

# 8. Продукционная модель (правила продукций)

<b>Продукционная модель знания</b> — модель, основанная на правилах, позволяет представить знание в виде предложений типа «Если (условие), то (действие)»

Продукционная модель обладает тем недостатком, что при накоплении достаточно большого числа (порядка нескольких сотен) продукций они начинают вследствие необратимости дизъюнкций противоречить друг другу. В этом случае разработчики начинают усложнять систему, включая в неё модули нечёткого вывода или иные средства разрешения конфликтов, — правила по приоритету, правила по глубине, эвристические механизмы исключений, возврата и т. п.

Продукционная модель часто дополняется определённым порядком, вводимым на множестве продукций, что упрощает механизм логического вывода. Порядок может выражаться в том, что отдельная следующая по порядку продукция может применяться только после попыток применения предшествующих ей продукций. Примерно похожее влияние на продукционную модель может оказать использование приоритетов продукций, означающее, что в первую очередь должна применяться продукция, имеющая наивысший приоритет.

Рост противоречивости продукционной модели может быть ограничен путём введения механизмов исключений и возвратов. Механизм исключений означает, что вводятся специальные правила-исключения. Их отличает большая конкретность в сравнении с обобщёнными правилами. При наличии исключения основное правило не применяется. Механизм возвратов же означает, что логический вывод может продолжаться в том случае, если на каком-то этапе вывод привёл к противоречию. Просто необходимо отказаться от одного из принятых ранее утверждений и осуществить возврат к предыдущему состоянию.

Противоречия в базах знаний на языке Пролог выявляются автоматически за счет использования автоматического доказательства теорем со встроенным в систему Пролог механизмами перебора с возвратами, организующего поиск информации в базах знаний и выводом найденной информации в качестве результатов информационного поиска.

# 9. Представление и обработка непределенности в продукционных системах

http://www.systematy.ru/articles/_33_predstavlenie_i_obrabotka_neopredelennosti_v_produktsionnyih_sistemah

# 10. Байесова модель

https://habr.com/ru/post/170545/

# 11. Сетевые модели и графы

<b>Сетевая модель</b> — графическое изображение плана выпол­нения комплекса работ, состоящего из нитей (работ) и узлов (событий), которые отражают логическую взаимосвязь всех операций. В основе сетевого моделирования лежит изображе­ние планируемого комплекса работ в виде графа.

<b>Граф</b> — схе­ма, состоящая из заданных точек (вершин), соединенных сис­темой линий. Отрезки, соединяющие вершины, называются ребрами (дугами) графа. Ориентированным называется такой граф, на котором стрелкой указаны направления всех его ребер (дуг), что позволяет определить, какая из двух его граничных вершин является начальной, а какая — конечной. Исследование таких сетей проводится методами теории графов.

Теория графов оперирует понятием пути, объединяющим последовательность взаимосвязанных ребер. Контур означает такой путь, у которого начальная вершина совпадает с конеч­ной.

<b>Сетевой график</b> — это ориентированный граф без конту­ров. В сетевом моделировании имеются два основных элемен­та — работа и событие.

За более подробной информацией сюда:

https://matica.org.ua/metodichki-i-knigi-po-matematike/osnovy-matematiki-i-ee-prilozheniia-v-ekonomicheskom-obrazovanii-krass-m-s-chuprynov-b-p/30-1-setevye-modeli-osnovnye-poniatiia-setevoi-modeli

# 12. Рейтинговая модель

сочувствую
