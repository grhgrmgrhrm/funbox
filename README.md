<p><i>npm install</i></p>
<p><i>npm run start</i></p>
<hr>
<h1>Тестовое задание для FunBox</h1>

<hr>

<p><strong>Q1 Расскажите, чем, на ваш взгляд, отличается хорошая верстка от плохой с точки зрения</strong></p>

<p><strong>Пользователя:</strong> Пользователь не должен получать затруднений в использовании каких-либо интерактивных элементов, загрузка должна происходить быстро. &nbsp;Интерфейс не должен разъезжаться, элементы не должны друг друга перекрывать и мешать просмотру контента или взаимодействию с элементами страницы. Само собой, сайт/приложение/интерфейс должны корректно отображаться во всех браузерах и на всех устройствах.</p>

<p><strong>Менеджера проекта:</strong> Вёрстка должна соответствовать ТЗ + код должен быть удобночитаем, чтобы неприятных вопросов у заказчика не возникало.</p>

<p><strong>Дизайнера:</strong> Хорошая вёрстка, а также её поведение максимально точно отражает задумку дизайнера.</p>

<p><strong>Верстальщика:</strong> Хорошая верстка должна одинаково хорошо выглядеть во всех браузерах и на всех устройствах, для которых проектировался интерфейс. Интерфейс не должен &quot;разваливаться&quot;. В вёрстке будут используются общие для компании правила написания кода.</p>

<p><strong>Клиентского программиста:</strong> Для фронтенд-программиста хорошая верстка должна быть легко читаема, иметь чёткую структуру, чтобы не было лишней работы в чистке кода, правке стилей и пр.</p>

<p><strong>Серверного программиста:</strong> верстка не нагружает сервер большим количеством запросов, применяется при возможности кэширование, cdn, сжатие gzip и js.</p>

<p><strong>Q2 Опишите основные особенности верстки крупных многостраничных сайтов, дизайн которых может меняться в процессе реализации и поддержки. Расскажите о своем опыте верстки подобных сайтов: какие методологии, инструменты и технологии вы применяли на практике.</strong></p>

<p>Верстка должна быть выполнена отдельными, независимыми компонентами или блоками которые можно многократно использовать. Обязательно использовать переменные для стилей. Этим можно моментально изменить на всем сайте шрифт, высоту и начертание текста, заголовков, различных элементов интерфейса &ndash; например, кнопок.</p>

<p>Для более-менее крупных проектов нужно использовать методологии web-разработки, например, Agile. В верстке избегать дублирования стилей с помощью &nbsp;БЭМ.</p>

<p><strong>Q3 Опишите основные особенности верстки сайтов, которые должны одинаково хорошо отображаться как на любом современном компьютере, так и на смартфонах и планшетах под управлением iOS и Android. Расскажите о своем опыте верстки подобных сайтов: какие инструменты и технологии вы применяли, как проверяли результат на различных устройствах, какие именно устройства требовалось поддерживать.</strong></p>

<p>В последнее время я применяю подход mobile-first &ndash; потому как пользователей мобильных устройств становится всё больше, по сравнению со стационарными ПК/ноутбуками.</p>

<p>Первоначально верстка тестируется в браузере, с помощью инструментов разработчика меняю тип устройства и проверяю корректность работы. Затем обязательное тестирование на живых устройствах &ndash; потому как тот же Chrome для различных девайсов работает иногда по-разному.</p>

<p><strong>Q4 Расскажите, какие инструменты помогают вам экономить время в процессе написания, проверки и отладки кода.</strong></p>

<p>В зависимости от целей, пишу код в Sublime Text, WebStorm. Для работы с Git &ndash; SmartGit. Панель разработчика в Google Chrome или dev-сборку&nbsp; Firefox. Для JavaScript &ndash; console.log().</p>

<p>Картинки сжимаю через TinyPNG или FastStone. Макеты нарезаю через Adobe Creative Cloud</p>

<p><strong>Q5 Вам нужно понять, почему страница отображается некорректно в Safari на iOS и в IE на Windows. Код писали не вы, доступа к исходникам у вас нет. Ваши действия? Сталкивались ли вы с подобными проблемами на практике?</strong></p>

<p>В указанных браузерах есть инструменты разработчика, которые позволят оперативно посмотреть на проблему. Если проблема в CSS, нужно дописать стили для каждого проблемного браузера.</p>

<p><strong>Q6 Дизайнер отдал вам макет, в котором не показано, как должны выглядеть интерактивные элементы при наведении мыши. Ваши действия?</strong></p>

<p>В первую очередь, нужно уточнить у дизайнера, что он имел в виду, когда прислал такой вариант макета. Если дизайнер по каким-то причинам недоступен,&nbsp; то для базовых элементов сделаю какие-нибудь стандартные, которые можно будет потом легко поменять.</p>

<p><strong>Q7 Какие ресурсы вы используете для развития в профессиональной сфере? Приведите несколько конкретных примеров (сайты, блоги и так далее). Какое направление развития вам более близко: JS-программирование, HTML/CSS- верстка или и то, и другое? Какие ещё области знаний, кроме тех, что непосредственно относятся к работе, вам интересны?</strong></p>


