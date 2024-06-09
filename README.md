# Открытие БКЛ и влияние на нагрузку на метрополитен Москвы
В урбанистике есть замечательная теория, которая, если кратко, звучит так : <br>
При большом количестве пробок в городе нельзя расширять дороги и строить новые, так как это приведет к росту спроса на автомобили (дороги начинают занимать относительно большую часть городской инфраструктуры), который всегда перекрывает рост предложения дорог. <br>
Я практически каждый день пользуюсь метро, в частности живу на БКЛ, и меня особенно обрадовало открытие этой линии. Я подумал: отлично, сейчас не только мне станет удобнее, но и другие линии разгрузятся! Но шли годы после открытия БКЛ, последняя станция открылась более года назад, а людей в метро как будто становилось только больше. В этот момент у меня закралась страшная мысль- а что если не только с автомобилями этот принцип работает? Что если метро тоже может вытеснять другие виды общественного транспорта и перегружаться? Эта мысль меня напугала, так как это означало бы что тот факт, что метро постоянно строится, будет делать мою жизнь не лучше, как мы все привыкли думать, а хуже. <br>
Я начал искать информацию на эту тему и увидел утешительную статистику - официальный сайт метро Москвы (https://stroi.mos.ru/specprojects/bkl-open/) говорит, что открытие БКЛ разгрузило Кольцевую линию на 23%, а радиальные линии до 12%. Хотелось бы поверить и успокоиться, однако не получалось - на всем моем ежедневном маршруте, состоящем как из Кольцевой, так и радиальных линий, людей, кажется, с каждым месяцем все больше. Поэтому эти факты надо проверить. <br><br>
Будем рассматривать 2 гипотезы. <br>
Первая гипотеза будет слабой и будет состоят из двух частей:<br>
После открытия БКЛ остальные линии разгрузились;<br>
Первая часть слабой гипотезы - кольцевая линия разгрузилась на 23%;<br>
Вторая часть - радиальные линии разгрузились до 12%.<br><br>
Иначе говоря, в первой гипотезе мы будем тестировать статистику, представленную на официальном сайте МосМетро. Я не знаю, каким образом были получены представленные значения, так что мы попытаемся оценить их способами, которые получится придумать. Важно заметить, что для подсчетов нам придется использовать прокси переменную - количество входящих на станцию людей, так как это единственное абсолютно точное значение, которое можно получить, так как внутри станций и внутри пересадок нет ниикаких датчиков, чек-инов или иных способов идентификации входящего. А на входе такая штука как раз стоит.<br> <br>

Вторая гипотеза будет тестированием теории про автомобили, применимо к метро. Иначе говоря, перекрывает ли растущий спрос на инфраструктуру метро увеличивающееся предложение станций и линий. Само собой, мы не можем однозначно принять или отвергнуть эту гипотезу на этом примере, это просто недостаточная выборка, однако применимо к нынешнему населению Москвы, привычкам граждан и уже построенной системе мы можем рассуждать подтверждается или опровергается эта гипотеза в краткосроке. <br>
Заметим, что отклонение первой гипотезы будет означать принятие второй, так как если первая гипотеза не работает, то это значит, что и кольца, и радиусы метро нагрузились, а значит и все метро нагрузилось. В обратную сторону это тоже работает. <br>
Остальная информация в project.ipynb <br>
Важно!! GH плохо дружит с Folium, поэтому for best experience лучше открывать файл локально
