---
title: Accessibility Basics
localeTitle: Основы доступности
---
> «Темные искусства многочисленны, разнообразны, постоянно меняются и вечны. Борьба с ними - это сражение с многоглавым монстром, у которого, каждый раз, когда шея разорвана, прорастает голова, даже в более ожесточенную и умную, чем раньше. которая является незафиксированной, мутирующей, нерушимой ».
> 
> \- Профессор Северус Снейп, серия Гарри Поттера

Роль доступности в развитии заключается в понимании перспективы и потребностей пользователя, а также знание того, что Интернет и приложения являются решением для людей с ограниченными возможностями.

В наши дни все новые и новые технологии изобретаются, чтобы облегчить жизнь разработчиков, а также пользователей. В какой-то степени это хорошая вещь, это дискуссия в другое время, на данный момент достаточно сказать, что панель инструментов разработчика, особенно веб-разработчика, так же постоянно меняется, как и так называемые «темные искусства», согласно нашему другу Снейпу.

Один инструмент в этой панели инструментов должен быть доступным. Это инструмент, который в идеале должен использоваться на одном из первых шагов написания любой формы веб-контента. Однако этот инструмент часто не так хорошо представлен в наборе инструментов большинства разработчиков. Это может быть связано с простым случаем, когда он не знает, что он существует даже в экстремальных случаях, например, не заботясь об этом.

В моей жизни как пользователю, а затем разработчику, который пользуется доступностью в любом виде контента, я видел оба конца этого спектра. Если вы читаете эту статью, я предполагаю, что вы находитесь в одной из следующих категорий:

*   Вы новичок веб-разработчик и хотели бы узнать больше о доступности
*   Вы опытный веб-разработчик и потеряли свой путь (подробнее об этом позже)
*   Вы чувствуете, что работа несет юридическое обязательство, и вам нужно больше узнать об этом.

Если вы выйдете за пределы этих довольно широких категорий, пожалуйста, дайте мне знать. Мне всегда нравится слышать от людей, которые читают то, о чем я пишу. Внедрение доступности влияет на всю команды: от цветов, выбранных дизайнером, копии, написанной копирайтером, и на вас, разработчика.

## Итак, что такое доступность?

Доступность сама по себе иногда немного вводит в заблуждение, особенно если английский является вашим вторым языком. Его иногда называют инклюзивным дизайном.

Если ваш сайт находится в Интернете, доступный любому, у кого есть веб-браузер, в некотором смысле, веб-сайт доступен для всех с помощью веб-браузера.

Но все ли содержимое на вашем веб-сайте действительно доступно для чтения, доступно и понятно для всех? Нет ли пороговых значений, которые запрещают определенным людям «получать доступ» ко всей информации, которую вы предоставляете?

Вы можете задать себе следующие вопросы:

*   Если вы добавляете информацию, содержащуюся только в аудиофайле, может ли глухой человек получить эту информацию?
*   Если вы обозначаете важную часть вашего сайта с определенным цветом, узнает ли это человек с цветовой слепотой?
*   Если вы добавляете на свой сайт изображения, которые передают важную информацию, как это может узнать слепой или слабовидящий?
*   Если вы хотите использовать приложение с клавиатурой или ручкой, это будет возможно и предсказуемо?
*   Предпринимает ли ваше приложение ориентацию устройства, и что, если пользователь не может физически изменить его?
*   Есть ли прощающие временные аспекты вашего приложения для кого-то, у кого может потребоваться больше времени для заполнения формы?
*   Ваше приложение все еще работает (прогрессивное повышение), предполагая, что JavaScript не загружается вовремя?
*   Вы даже можете сказать, что если ваш сайт очень ресурсоемкий, сможет ли кто-то на медленном или пятнистом соединении читать ваш контент?

Здесь открывается доступность. Доступность в основном влечет за собой сделать ваш контент дружественным, так же легко «доступ» для максимально возможного количества людей. Это включает людей, которые являются глухими, слабовидящими, слепыми, дислексическими, немыми, на медленном соединении, дальтоники, страдающие эпилепсией, умственной отсталостью, физическими ограничениями и т. Д.

## Зачем устанавливать доступность?

Вы можете подумать, что доступность не относится к вам или вашим пользователям, поэтому зачем это реализовать? Что сделает слепой человек с инструментом для редактирования фотографий?

Правда в том, что вы правы в определенной степени. Если вы провели тщательное исследование пользователей и исключили вероятность того, что определенная группа людей посетит ваш сайт, приоритет для обслуживания этой группы людей немного уменьшится.

Тем не менее, проведение этого исследования является ключом к фактической защите такого заявления. Знаете ли вы, что были [слепые геймеры?](http://audiogames.net) и даже [слепые фотографы?](http://peteeckert.com/) , Возможно, вы знали, что [музыканты могут быть глухими](http://mentalfloss.com/article/25750/roll-over-beethoven-6-modern-deaf-musicians) ?

Если да, то хорошо. Если нет, я думаю, что это еще больше подчеркивает мою точку зрения.

Картина становится еще более сложной, когда мы смотрим на законодательство, которое фактически заставляет вас сделать доступными определенные веб-сайты и веб-приложения. Первым примером является [раздел 508,](http://jimthatcher.com/webcourse1.htm) основанный на США. Сейчас этот закон в основном относится к правительственным организациям, сайтам государственного сектора и т. Д. Однако законы меняются.

В прошлом году веб-сайты авиакомпаний были включены в этот список, что означало, что даже здесь, в Европе, разработчики веб-сайтов авиакомпаний собираются сделать их контент доступным. Не делая этого, вы можете получить для вашей компании штраф в буквальном смысле десятков тысяч долларов за каждый день, пока проблема не устранена.

В этом законодательстве существуют различные варианты, более серьезные и всеобъемлющие, чем другие. Не зная об этом факте, к сожалению, судебный процесс неизбежен.

## Хорошо, доступность - это большое дело. Теперь, как мы его реализуем?

К сожалению,на этот вопрос сложнее ответить, чем может показаться. Цитата Гарри Поттера наверху упомянута по какой-то причине, и это не мое пристрастие к Fantasy.

Как я уже говорил выше, доступность важна для большой группы разных людей, каждая из которых имеет свои собственные потребности. Создание вашего сайта в буквальном смысле - это большая, постоянная задача.

Чтобы привести немного к безумию, были составлены Руководящие принципы доступности веб-контента или [WCAG](https://www.wuhcag.com/web-content-accessibility-guidelines/) . Этот документ содержит ряд критериев, которые вы можете использовать для проверки вашего сайта. Пока я расскажу о некоторых из наиболее важных основ. Я укажу вам на низко висящие фрукты, так сказать. В последующих статьях я расскажу о более продвинутых методах, таких как \[WAI-ARIA\], что важно для приложений на базе JavaScript.

### Поговорите, как туземцы

Спецификация HTML - это документ, который описывает, как язык должен использоваться для создания веб-сайтов. Вспомогательные технологии, такие как экранные программы, программы распознавания речи и т. Д., Знают об этом документе. Однако веб-разработчикам часто не хватает или, по крайней мере, недостаточно, и думаю, что что-то вроде этого в порядке:

```html

    <div class="awesome-button"></div> 
 
    <span><strong>Huge heading I will style with CSS later</strong></span> 
 
    <span class="clickable-with-JavaScript">English</span> 
```

Угадай, что? Все три из этих элементов нарушают несколько критериев WCAG и поэтому не доступны вообще.

Первый элемент разбивает так называемое «имя, роль, значение» -критерий, в котором говорится, что все элементы на веб-странице должны выставлять свое имя, свою роль (например, кнопку) и их значение (например, содержимое поля редактирования) к вспомогательным технологиям. Этот div фактически не предоставляет ни одного из трех, что делает его невидимым для экранных считывателей.

Второй элемент выглядит как заголовок визуально после стилизации его с помощью CSS, но семантически это span. Поэтому вспомогательные технологии не будут знать свой заголовок. Считыватель будет читать это как обычный текст, а не заголовок. У экранных считывателей часто есть горячая клавиша для быстрого перехода к ближайшему заголовку, этот заголовок не будет включен в эту область.

Третий элемент может быть, например, элементом, который пользователь может щелкнуть, чтобы изменить язык веб-сайта. Возможно, при нажатии на него будет расширяться анимационное меню языков. Тем не менее, это также диапазон и не раскрывает его роль (ссылка или кнопка), делая вспомогательные технологии, думая, что это просто слово «английский» с некоторым стилем.

Пролисты и divs не являются элементами. Они должны содержать другие элементы, а не сами элементы. Вы можете исправить их двумя способами:

*   Вы можете вручную добавить ARIA-атрибуты к элементам выше. Это расширенная тема и выходит за рамки этой статьи.
*   Или вы можете просто сделать это:

```html

    <button>This is a button</button> 
 
    <h2>Here's a heading level two</h2> 
 
    <a href="JavascriptThing">English</a> 
```

Boom. Внезапно все эти элементы теперь совершенно доступны, просто используя собственный HTML. Другими словами, HTML, как он должен был использоваться, другими словами.

### Фонд не может стоять без структуры

Немного раньше я коснулся горячих клавиш экрана для перехода от заголовка к заголовку. На самом деле есть много таких горячих клавиш, чтобы быстро перейти к ближайшей таблице, поле формы, ссылке и т. Д. Таким образом, эти заголовки на самом деле находятся в логических местах, поэтому является хорошей практикой и действительно снижает уровень стресса ваших пользователей вспомогательных технологий, что хорошо если вы хотите, чтобы посетители продолжали возвращаться на ваш сайт.

Также помните, что заголовки являются иерархическими. Если вы используете h2, убедитесь, что h3, которые следуют за ним, действительно имеют какое-то отношение к этому h2. Не помещайте h3 для контактной информации под своим h2 для последних сообщений в блоге. Хорошей аналогией здесь является книга с главами, в которой есть подразделы. Вы не ставили секцию об выпекании куки в середине главы по приготовлению овощей ... или ... вы бы не ... верно?

### Какая альтернатива?

Изображения на веб-сайте великолепны. Они добавляют новый слой к вашему контенту, могут действительно сделать опыт посетителей вашего сайта более захватывающим и, как правило, просто хорошо выглядеть среди всего этого текста. На картинке можно сказать больше тысячи слов, верно?

Безусловно. То есть, если вы можете их увидеть. В спецификации HTML5 атрибут img всегда должен иметь атрибут alt. Этот атрибут подразумевается как альтернатива изображению, если он не может быть замечен. Это было бы верно для слепых посетителей вашего сайта, но также, когда ваше изображение не может быть загружено по какой-либо причине. Поэтому не добавлять альт-тег в img-атрибут, следовательно, не только нарушает доступность, но и противоречит спецификации HTML5.

Я умоляю любого веб-разработчика, который ловит себя за это, чтобы съесть шляпу своего программиста и работать в Windows 95 исключительно в течение недели. По прошествии времени напишите эссе о том, что вы узнали из этого испытания, чтобы я мог смеяться во время дневного кофе.

Теперь здесь есть одна оговорка. Alt-атрибуты являются обязательными в соответствии с спецификацией HTML5, но не обязательно заполнять их. `<img src="awesome-image.jpg", alt="">` является поэтому законным кодом HTML5.

Должны ли вы заполнять альт-теги для всех изображений? На самом деле это зависит от образа. Для фоновых изображений ответ обычно отсутствует, но в любом случае вы должны использовать CSS для них.

Для чисто декоративных изображений, которые вообще не имеют в них информации, вы в принципе можете выбирать. Либо введите что-то полезное и описательное, либо ничего.

Для изображений, содержащих информацию, например брошюру, карту, диаграмму и т. Д., Не добавляя текст alt, разрывает WCAG, если вы не предоставляете текстовую альтернативу. Обычно это атрибут alt, но также может быть блоком текста справа или рядом с изображением.

Для изображений текста текст может быть включен в атрибут alt или предложен каким-либо альтернативным способом. Проблема в том, что добавление текстовой альтернативы на той же странице в основном делает одно и то же содержимое дважды отображаемым для людей, которые могут видеть изображение, поэтому в этом случае атрибут alt лучше.

Текст должен содержать контекст и информацию, альтернативную виду изображения. Просто не достаточно написать «образ воздушных шаров» - почему там изображены воздушные шары? Если изображение стилизовано или передает эмоциональное значение, это может быть включено.

### Я не могу читать твои каракули, сынок

Даже люди, которые не носят очки и не имеют проблем с их зрением, получают выгоду от легко читаемого шрифта и надлежащего контраста. Я уверен, что вы бы съежились, если бы вам пришлось заполнить форму, в которой светло-желтые, безнадежно зацикленные буквы помещаются на белом фоне. Например, для людей, у которых зрение не так хорошо, как ваша бабушка, например, это становится безнадежно хуже.

WCAG имеет коэффициенты контрастности для меньших и больших букв, и есть много инструментов для проверки достаточности коэффициентов контрастности. Информация и инструменты есть, используйте его.

Хорошим местом для начала проверки цветового контраста является использование [анализатора](https://webaim.org/resources/contrastchecker/) цветового контраста [WebAIM](https://webaim.org/resources/contrastchecker/) .

### Что делает эта кнопка?

Пока мы на тему форм, давайте быстро взглянем на тег `input` . Этот маленький парень очень важен.

Когда вы помещаете некоторые поля ввода на веб-страницу, вы можете использовать метки для ... ну ... маркировать их. Однако поставить их рядом друг с другом недостаточно. Атрибут, который вы хотите, является атрибутом for-attribute, который принимает идентификатор последующего поля ввода. Таким образом, вспомогательные технологии знают, какой ярлык ассоциируется с каким полем формы.

Я думаю, лучший способ проиллюстрировать это, например:

```html

    <label for='username'> 
 
    <input type='text' id='username'> 
```

Это, например, приведет к тому, что сканер экрана скажет «имя пользователя, поле редактирования текста» вместо того, чтобы просто сообщать «текстовое поле редактирования» и потребовать, чтобы пользователь пошел искать метку. Это также действительно помогает людям, использующим программное обеспечение для распознавания речи.

### Это высокий порядок

Давайте сделаем небольшой перерыв. Я хочу, чтобы вы посмотрели действительно хорошо продуманную веб-страницу. Это может быть любая страница. Продолжай, я подожду.

Назад? Ок, отлично. Теперь просмотрите страницу еще раз, но отключите все CSS. Все еще выглядит хорошо? Содержимое на странице все еще в логическом порядке? Если так, отлично. Вы нашли страницу с хорошей структурой HTML. (Один из способов легко просмотреть страницу без CSS - загрузить сайт в WebAIM [WAVE Web Evaluation Tool](http://wave.webaim.org) . Затем нажмите вкладку «Нет стилей», чтобы просмотреть ее без стилей.)

Если нет, отлично. Теперь вы получаете представление о том, с чем мне приходится иметь дело каждый день, когда я сталкиваюсь с плохо структурированным сайтом.

Полное раскрытие: я обычно проклинаю, когда это происходит. Громко. С энергией.

Почему это так важно? Я объясню.

_Осторожно, спойлеры!_ Тем, кто до сих пор изучал только учебную программу HTML / CSS, мы немного пропустим немного.

Считыватели экрана и другие вспомогательные технологии отображают представление веб-страницы сверху вниз, основанное на DOM вашего сайта. Все позиционные CSS игнорируются в этой версии веб-страницы.

DOM обозначает Document Object Model и представляет собой древовидную структуру HTML-элементов вашего веб-сайта. Все ваши HTML-элементы - это узлы, которые иерархически взаимосвязаны на основе HTML-тегов, которые вы используете, и JavaScript. Считыватели экрана используют это дерево DOM для работы с вашим кодом HTML.

Если вы поместите элемент вверху своего элемента, он также появится вверху вашего дерева DOM. поэтому скрин-ридер поставит его вверху, даже если вы переместите его в нижнюю часть страницы с помощью CSS.

Итак, последний совет, который я хочу дать вам всем, - это обратить внимание на порядок вашего HTML, а не только на ваш законченный веб-сайт с добавленным CSS. Разве это все еще имеет смысл без CSS? Большой!

Ох ... это не так? В таком случае вы могли бы однажды услышать приглушенное проклятие, перенесенное к вам на холодный ветерок во время прогулки по улице. Скорее всего, это я, посетив ваш сайт.

В этом случае у меня действительно есть только два слова для вас. Часто я слышал те же самые два слова, которые были направлены на меня, когда я написал плохой код, и я с большим удовольствием говорю вам: «Иди исправить!»

### Цветовая контрастность

Цветовой контраст должен быть минимум 4,5: 1 для обычного текста и 3: 1 для большого текста. «Большой текст» определяется как текст размером не менее 18 точек (24 пикселя) или 14 точек (18,66 пикселей) и полужирный. [Контроллер контраста](https://webaim.org/resources/contrastchecker/)

## Вывод

Я рассказал вам о доступности, о том, что это такое, что это не так и почему это важно.

Я также дал вам основы, самые основы, обеспечения прав доступа. Эти основы, однако, очень эффективны и могут сделать вашу жизнь намного проще при кодировании доступности.

Если мы говорим в терминах FCC, вы должны помнить об этом, выполняя учебную программу HTML / CSS, а также учебную программу JavaScript.  
В последующих статьях я затрону несколько более важных тем. На целый ряд вопросов я отвечу:

*   Добавление структурированных заголовков звучит как хорошая идея, но они не вписываются в мой дизайн. Что я делаю?
*   Есть ли способ для меня написать контент только для чтения с экрана и других вспомогательных технологий?
*   Как создать пользовательские компоненты JavaScript?
*   Какие инструменты существуют, помимо инклюзивного тестирования пользователей, которые могут быть использованы для разработки наиболее надежного и доступного опыта для самой большой группы пользователей?