"# jv-stream-api" 
Дано: List of Integer numbers. Вернуть сумму нечетных числел или 0, если таких несуществует.
Дана коллекция строк Arrays.asList(«a1», «a2», «a3», «a1»). Вернуть количество вхождений объекта «a1»
Дана коллекция строк Arrays.asList(«a1», «a2», «a3», «a1»). Вернуть Optional первого элемента коллекции
Дана коллекция строк Arrays.asList(«a1», «a2», «a3», «a1»). Найти элемент в коллекции равный «a3» или кинуть ошибку NoSuchElementException
Дана коллекция чисел Arrays.asList(6, 2, 3, 7, 2, 5) Отнимите от каждого элемента, который стоит на непарной позиции (имеет не парный индекс) 1 и верните среднее арифметическое всех нечетных чисел или киньте ошибку NoSuchElementException
Дана коллекция класс People (с полями name — имя, age — возраст, sex — пол), вида Arrays.asList( new People(«Вася», 16, Sex.MAN), new People(«Петя», 23, Sex.MAN), new People(«Елена», 42, Sex.WOMEN), new People(«Иван Иванович», 69, Sex.MAN)). Давайте посмотрим примеры как работать с таким классом:
Выбрать мужчин-военнообязанных (от 18 до 27 лет)
Найти всех потенциально работоспособных людей в выборке (т.е. от 18 лет и учитывая что женщины выходят в 55 лет, а мужчина в 60)
Дано коллекцию List of peoples. Класс People (с полями name — имя, age — возраст, sex — пол, List cats - кошки этого человека). Дано класс Cat (name- имя кошки, age - возраст кошки). Задача: вивести все имена кошек в которых хозяева это девушки старше 18 лет