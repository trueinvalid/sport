def dayMenu():
    day = input("Введите день недели:")
    if day == "Понедельник":
        print("Утро: \tКаша и молоко\nОбед:\tКурица с рисом")
    elif day == "Вторник":
        print("Утро: \tХлопья с молоком\nОбед:\tСосиски")
    elif day == "Среда":
        print("Утро: \tОмлет и лимонад\nОбед:\tФрикасе")
    elif day == "Четверг":
        print("Утро: \tСалат и кофе\nОбед:\tМакароны с фаршем")
    elif day == "Пятница":
        print("Утро: \tГречка и молоко\nОбед:\tСуп")
    elif day == "Суббота":
        print("Утро: \tПанини\nОбед:\tБургер")
    elif day == "Воскресенье":
        print("Утро: \tБлины\nОбед:\tПицца")
    else:
        print("ошибка день не найден")
    

while True:
    print("1. Меню на неделю")
    print("2. Калькулятор подсчета калорий")
    print("3. Магазин с продуктами")
    print("4. Список выбранных продуктов")
    print("5. Выход")

    choice = input("Выберите действие (1-5)")
    if choice == "1":
        print("Ваше меню на один день")
        dayMenu()
    elif choice == "2":
        print("Норма калорий")
    elif choice == "3":
        print("Наше меню")
    elif choice == "4":
        print("Cписок выбранных продуктов")
    elif choice == "5":
        print("Конец")
        break
    else:
        print("Неверный ввод, попробуйте снова")
