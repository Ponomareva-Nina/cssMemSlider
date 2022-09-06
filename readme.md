1. task: https://github.com/rolling-scopes-school/tasks/blob/master/tasks/css-mem-slider/README.md
2. screenshot:
css-slider_screenshot
3. Deploy: https://ponomareva-nina.github.io/cssMemSlider/cssMemSlider/index.html
4. Done 16.05.2022 / deadline 17.05.2022
5. Score: 150/150

Выполненные требования:

* Выполнено всё из секции Требования к репозиторию и как сабмитить задание +30.
* Слайдер позиционируется с равными отступами слева и справа +10.
* Соблюдено расположение картинок, подписей к ним и контролов +10.
* Имеется анимация для смены картинок +20.
* Имеется анимация для смены подписей к картинкам +10.
* Подписи к картинкам являются строковыми значениями (текстом), т.е. текст не должен быть частью картинки +15;
* Каждый контрол имеет большую область нажатия, чем размер самого контрола. У меня реализовано через добавление дочернего div, стилизованного под контрол. +5.
* Контролы имеют интерактивность (момент наведения, момент нажатия, активный контрол, изменение курсора). Имеются эффекты для :hover и :active. +10.
* Имеется мобильная версия слайдера и соблюдено расположение картинок, подписей к ним и контролов +20.
* версия для десктопа: стартует с ширины 1181px;
* в версии для планшетов и небольших экранов адаптированы отступы для лучшего отображения (реализовано на ширине <=1180px и >767px )
* версия для мобильных устройств: <=767px;
* Используются относительные единицы измерения для основных блоков (картинки, контролы, подписи) (rem, em, %, vh, vw, fr and etc... ). В пикселях заданы исключительно значения вспомогательных декоративных элементов (border и box-shadow в величинах 2-3px) - не противоречит ТЗ. Присутствует "резиновость" слайдера +10.
* Все блоки/составные части слайдера (контролы, картинки, подписи к слайдеру) находятся в базовом потоке дом-элементов, не позиционируются с помощью top, left, right, bottom. (Используется свойство background-position для позиционирования картинок на фоне - не противоречит требованиям ТЗ, т.к. фон не является составной частью слайдера или отдельным блоком). Не используются псевдоэлементы. +10.
