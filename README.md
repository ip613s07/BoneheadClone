# BoneheadClone

Тестовое Bonehead
Аналог Bonehead

Обязательно делаем в 2D. Нужно использовать бесплатные ассеты на ваше усмотрение для создания фона, ui и моделей с анимациями. В будущем вы не будете заниматься подбором ассетов, но в тестовом это нужно сделать.
Камера и расположение ui аналогично референсу.


Обязательные механики:
1. В верхней области каунтер софты, после пустые ячейки с экипировкой и характеристиками экипировки, в нижней персонаж.
2. При клике на персонажа игрока он проигрывает любую анимацию.
3. Появляется поп-ап сверху надетая экипировка если такая имеется, снизу новая. У каждого предмета есть иконка обозначающая тип экипировки, названием типа экипировки и характеристика экипировки.
Внизу красная кнопка Drop и желтая Equip.
4. Рандомно определяется какую экипировку достал игрок, но достав одну экипировку одного типа три раза подряд должна идти одна экипировка другого типа, потом снова рандом.
5. Реализуем 3 типа экипировки: оружие, щиты, шлем. Иконки экипировки одного типа можно сделать одинаковыми.
У каждого оружия своя характеристика, соответственно: Атака, защита, HP.
Значение характеристики экипировки определяется рандомно от 1 до 15.
6. Справа от характеристики показано лучше характеристика нового предмета или хуже, зеленая стрелка вверх или красная стрелка вниз.
7. При нажатии Drop - закрывается окно, предмет в нижней части поп-апа распадается на монетки и этим монетки с красивой анимацией улетают в каунтер. Примеры карсивой анимации: https://youtu.be/7BfmbzF7cbI?t=99 или  https://youtu.be/3DuZl-xx5JQ?t=98.
В каунтер начисляется то количество монет какое было значение характеристики у дропнутой экипировки.
8. При нажатии Equip - новая экипировка надевается в инвентарь, а старая рассыпается на монеты.
Если в инвентаре небыло ячейки с экипировкой то иконка экипировки появляется в инвентаре.
9. Характеристики игрока справа от инвентаря показывают сумму его текущих характеристик.

Остальные механики можно делать по желанию, их наличие дает вам бонус среди других кандидатов:
10. Справа от персонажа есть иконка боя, при нажатии на которую появляется экран с персонажем и мобом.
Игрок сначала сражается с очень слабым мобом - проигрываются их анимации атак, есть хп бар обоих противников, корректно рассчитывается урон и анимация смерти проигравшего, отображается ui нанесенного урона. Конец битвы переносит в на основной экран. При повторном нажатии на иконку боя  сражается с сильным мобом.
11. При желании можно сделать систему квестов, сундуков или любые другие механики из рефа.


Ассеты:
https://assetstore.unity.com/packages/2d/textures-materials/nature/free-pixel-art-forest-133112
https://assetstore.unity.com/packages/2d/characters/hero-knight-pixel-art-165188