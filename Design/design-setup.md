# Добро пожаловать в UI/UX дизайн!

Здесь мы будем делать дизайны функциональных и красивых интерфейсов. Я оставлю несколько полезных ссылок, к которым ты сможешь обратиться после того, как выполнишь эту задачку. Не бойся писать наставнику, тебе всегда помогут, если что-то не получается

## Справочные ресурсы
Курс [Нетологии](https://netology.ru/programs/osnovy-figma#/main) для знакомства с Figma

Статья на [vc.ru](https://vc.ru/design/572082-figma-dlya-nedizaynerov-komu-i-zachem-nuzhen-servis?ysclid=lp7131j7oa419585628), где ты можешь кратко узнать, что такое Figma, ее возможности и области применения(внутри тоже полезные ссылки)

Туториал про [компоненты](https://help.figma.com/hc/en-us/articles/360038662654-Guide-to-components-in-Figma) (на английском языке). Эта тема может показаться непростой. В этой задаче мы поработаем и с компонентами. Если тебе показалось что-то непонятно — смело пиши наставнику, задавай вопросы по этой статье и не только

## Для начала
  Эту задачу нужно выполнить, чтобы познакомиться с необходимыми инструментами и сделать свои первые шаги в дизайне интерфейсов
  
  На этом этапе тебе потребуется открыть [Figma](https://www.figma.com) и создать аккаунт. Пока достаточно веб-версии, но позже ты можешь установить приложение, если так будет удобнее)
  
  1) В личном кабинете на панели слева во вкладке Drafts будут лежать твои черновики
  2) Создай новый черновик, нажав на + Design file в правом верхнем углу
  3) Перед тобой бесконечный холст, на котором можно создавать дизайны экранов приложений и многое другое
  4) На верхней панели ты видишь базовые инструменты. Рекомендую сразу начинать запоминать горячие клавиши

  Теперь перейдем непосредственно к задаче

## Первые шаги
  
  1) Сперва создадим новый фрейм. Клавишей F (Frame) можно создать произвольный прямоугольник(все как в Paint), но мы воспользуемся готовым фреймом Android Large. Это белый экран, на который можно добавлять элементы(кнопки, текст, изображения и т. д.)
  2) Ты можешь регулировать масштаб, зажав ctrl и прокрутив колесико мыши. Перемещаться по холсту можно, зажав колесико мыши
  3) Нажми R (Rectangle) и создай прямоугольник на экране. Следи, чтобы прямоугольник был внутри фрейма. Проверить это можно, посмотрев на панель слева. Там отображаются все элементы на холсте. Проверь, что созданный элемент(Rectangle 1, хотя его можно и переименовать на этой же панели) вложен в твой фрейм, а не лежит отдельно(если "свернуть" фрейм, нажав на стрелку слева, Rectangle 1 должен пропасть на этой панели)
  4) Сделай так, чтобы прямоугольник был по центру. Перемещай его по холсту и ориентируйся на красные линии-подсказки
  5) На панели справа ты можешь задать параметры прямоугольника(прямоугольник должен быть выделен)
  6) Сверху ты видишь ширину(W) и высоту(H). Задай параметры 350 и 250 соответственно. Изогнутая полоса под обозначением высоты означает скругление углов. Задай параметр 10
  7) Ниже на этой панели найди раздел Fill. Прямоугольник заполнен цветом D9D9D9. Это HEX-код и ты можешь его поменять или выбрать цвет из палитры, нажав на цветной квадрат рядом с кодом. Там же можно сделать градиент, вставить фото или видео
  8) Нам не понадобится заполнение, поэтому нажми на минус рядом со значком глаза. Прямоугольник пропадет с холста, но не пугайся, он просто невидимый) Создавать новый не нужно, сейчас покажу, почему
  9) Под разделом Fill найди раздел Stroke и нажми на плюс рядом с ним. Stroke задает рамку фигуры

  Ты уже умеешь выполнять некоторые базовые действия, поэтому дальше я буду говорить немного короче

  1) Создай прямоугольник 32х32 и параметром скругления 100, убери заливку и сделай обводку, как в пп. 8-9 предыдущей части и перемести его под нижний левый угол большого прямоугольника, выровняй по его левому краю
  2) Выдели получившуюся окружность. Зажав alt, отодвинь скопировавшуюся вторую окружность вправо на 8 пикселей(вдоль красных линий будут обозначения). Теперь выдели новую окружность и продублируй ее, зажав ctrl + D (Duplicate). Она копируется на таком же расстоянии, что и первые две

  Получился так называемый Wireframe - набросок того, как должна выглядеть страница функционально. Его используют, чтобы визуализировать структуру и содержание продукта. Вайрфрейм показывает, как будут расположены необходимые на экране элементы: кнопки, панели, карточки, текстовые блоки и т. д. Сейчас мы видим набросок приложения некоторой соцсети: так в ленте будет расположен пост. Кружочки под ним — места для иконок(понравилось, комментарии, поделиться)
  
  ![image](https://github.com/profcomff/interns/assets/132715531/d9f47d56-552a-4992-be8d-04ef841847ee)

  Но что если мы хотим увидеть, как будет выглядеть лента из более, чем одного поста? Неужели придется создавать новые прямоугольники? Копировать, каждый раз выделяя все элементы по очереди? Можно, но давай сделаем проще

  1) Выдели все 4 прямоугольника
  2) Нажми ctrl + G (Group), чтобы сгруппировать элементы. Теперь они хранятся в элементе Group 1 на панели слева. Ты можешь менять расстояние между элементами более удобно, с помощью розовых подсказок
  3) Теперь скопируй (ctrl + D) группу прямоугольников и перемести ниже первоначальной. Целиком на экране она не поместится, но и за пределы фрейма не вылезет. Ты можешь переместить обе группы, чтобы они были видны, но не забудь выравнивать по центру
  4) Примерно так должна выглядеть лента приложения, макет которого ты создаешь прямо сейчас
     
### Продолжаем
Компонент – это элемент или блок, который можно редактировать комплексно. Задав его вид один раз, автоматически измененные копии компонента можно использовать в разных частях проекта.

1) Создай кружок 32х32 и выдели его
2) Нажми на иконку в виде четырех ромбов в центре верхней панели, чтобы создать компонент(Мастер-компонент). Придай ему какой-нибудь цвет(я буду использовать цвет с кодом 226A7E)
3) Продублируй созданный компонент. Получится экземпляр-компонент(instance)

Теперь если ты изменишь параметры мастер-компонента(цет или размеры, например), то параметры экземпляр-компонента поменяются так же. Это будет работать для неограниченного количества экземпляров

Таким образом, с помощью компонентов можно "по кирпичикам" собирать дизайны интерфейсов из уже готовых компонентов – экраны и иконки будут в едином стиле.

1) Теперь выдели мастер-компонент и нажми на иконку в виде ромба с плюсом на верхней панели, чтобы добавить вариант(и еще раз, чтобы в пунктирной рамке было 3 круга)
2) Поменяй цвета получившихся вариантов в пунктирной рамке(нужно поменять цвен именно фигуры, лежащей внутри компонента – ориентируйся на панель слоев слева). Я использовала цвета E1919B E5CAC6

![image](https://github.com/profcomff/interns/assets/132715531/a4b63c9e-4433-4b35-afad-a087f48402ee)

3) Ты можешь переименовать варианты, зайдя в настройки Properties на панели справа
4) Теперь, выделив вариант в рамке и зажав alt, ты можешь "достать" экземпляр нужного варианта и поставить на нужное место на экране, а если захочешь поменять один вариант на другой, достаточно выделить текущий, на панели слева в разделе с именем набора вариантов переключить один на другой(у меня набор вариантов назван Компонент)

![image](https://github.com/profcomff/interns/assets/132715531/b04b06c2-9179-4576-a84b-0e034c6f6513)

### Собираем
Теперь, создав базовые компоненты, ты можешь создать вложенные компоненты, чтобы у тебя был под рукой шаблон поста. Для этого скопируй один из прямоугольников под фотографию поста, созданных ранее, добавь под ним цветные иконки-экземпляры, которые мы только что сделали, и объедини в единый компонент кнопкой наверху экрана, как описано в начале предыдущего раздела. Добавь место под аватарку и имя пользователя

![image](https://github.com/profcomff/interns/assets/132715531/2af29d99-f9f6-4041-94f3-4b1cf5f59eed)

Цветные иконки по-прежнему связаны с мастер-компонентом, но теперь ты легким движением можешь не только добавить в ленту на экране макеты постов, но и поменять параметры каждого из них через один-единственный мастер-компонент. Для этого создай еще один фрейм Android Large

На такой экран поместится два поста-экземпляра, но если редактировать мастер-пост(например, поменять длину картики), то эелементы могут сместиться перекрывая друг друга. В этой ситуации на помощь приходит Auto Layout на панели слева

1) Выдели мастер-пост и нажми Auto Layout
2) сделай в настройках так, чтобы выравнивание было слева посередине

![image](https://github.com/profcomff/interns/assets/132715531/1bc6e863-cbde-4b72-ba71-798179f2fb64)

3) Здесь же ты можешь редактировать расстояние между элементами по вертикали и по горизонтали
4) Чтобы и на экране все оставалось таким же аккуратным, выдели новый фрейм с постами полностью, и добавь Auto Layout
5) Попробуй сделать посты квадратными (330х330) через мастер-компонент. В новом фрейме ничего не придется передвигать или редактировать – Auto Layout уже сделал все сам
6) Измени цвета иконок-вариантов. В ленте и мастер-посте цвет поменяется автоматически

![image](https://github.com/profcomff/interns/assets/132715531/f40cad37-aef7-4831-bc7b-10503e430040)

На этом этапе ты можешь произвольно доработать получившуюся ленту, поиграть с настройками компонентов или добавить цвета:

![image](https://github.com/profcomff/interns/assets/132715531/f99eae3e-8525-4d26-b825-ac406e24a616)

## Заключение

Поздравляю с выполнением первого задания!

Смело делись с наставником результатами своей работы или задавай вопросы, если что-то не получается. 
Твое путешествие в дизайн интерфейсов начинается прямо сейчас)
  
