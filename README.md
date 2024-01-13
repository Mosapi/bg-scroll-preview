# Bg-horizon-scrolling
This is horizontal scrolling for a website in pure javascript, without using third-party plugins. In this project, there is a change not of images, but of the background.
Scrolling is done automatically and supports manual change, using the side arrows or controllers at the bottom.

## How to use:
***1. Place the Bg horizon scrolling in the place you need***
```
<div id="gkHeader" class="mess">
	<div id='zatun'></div>
</div>
```

***2. Connect the decolation.js before closing the tag <body>***
```
<script type="text/javascript" src="system/js/decolation.js"></script>
</body>
```

***3. The script works with data selected from the database. We specify them before connecting the script***

```
<script>
// all data select from db (msql or other)
imgs = ["82.jpg", "82b.jpg", "84.jpg", "87b.jpg"];
links = ["Cyberpunk2077", "NierAutomata", "EldenRing", "HorizonFW"];
titlet = ["Cyberpunk 2077", "Nier: Automata", "Elden Ring", "Horizon Forbidden West"];
descr = ["Приключенческая ролевая игра с открытым миром, рассказывающая о киберпанке-наёмнике Ви и борьбе за жизнь в мегаполисе Найт-Сити.", "Nier: Automata (NieR new project) — это непрямой сиквел NIER, действие которого разворачивается на порабощенной боевыми роботами Земле.", "НОВЫЙ ФЭНТЕЗИЙНЫЙ РОЛЕВОЙ БОЕВИК. Восстань, погасшая душа! Междуземье ждёт своего повелителя. Пусть благодать приведёт тебя к Кольцу Элден.", "Отправьтесь вместе с Элой в путешествие по величественному, но опасному миру Запретного запада, который скрывает новые загадочные угрозы."];
</script>
```
***4. The general style of the arrows is set by class="_arr", the direction is indicated by id="_pl" - left arrow and id="_pr" - right arrow***

***5. The lower controllers are set as follows:***
```
<div class='_shiv _flx'>
	<div id='sl0' class='_shblo _acti'></div>
	<div id='sl1' class='_shblo'></div>
	<div id='sl2' class='_shblo'></div>
	<div id='sl3' class='_shblo'></div>
	<div id='sl4' class='_shblo'></div>
</div>
```
The number of blocks is unlimited, but must be 1 more than in the ***imgs[]*** array. The ***_acti*** class points to the initially active controller.

***6. For a better idea of how controllers, arrows, and other elements can be positioned, see example***


## Preview
https://user-images.githubusercontent.com/22084187/174544947-49367ab3-5555-4e17-812e-c8e14ecc5493.mp4




