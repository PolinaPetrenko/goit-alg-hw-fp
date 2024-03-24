# goit-alg-hw-fp
Порівнюючи отримані ймовірності сум при киданні двох кубиків методом Монте-Карло із аналітичними розрахунками, можна зробити наступні висновки:

Суми 2 і 12: Ймовірності цих сум за методом Монте-Карло становлять 2.79%, що відповідає теоретичним розрахункам в 2.78%. Різниця дуже мала і обидва методи дали близький результат.

Суми 3 і 11: Ймовірності цих сум також досить точно відповідають аналітичним розрахункам (5.56% за Монте-Карло і 5.56% теоретично).

Суми 4, 5, 6, 8, і 9: Для цих сум різниця між результатами методу Монте-Карло і теоретичними розрахунками також досить невелика, з відхиленнями в межах 0.01-0.02%.

Сума 7: У сумі 7 відхилення є найбільшим (16.68% за Монте-Карло проти 16.67% теоретично). Однак, це все ще дуже близькі значення, і метод Монте-Карло добре відображає ймовірність цієї суми.

Суми 10: Тут також відзначається досить точне відображення ймовірності (8.32% за Монте-Карло проти 8.33% теоретично).

Узагальнюючи, метод Монте-Карло дав дуже близькі результати до теоретичних розрахунків для всіх можливих сум при киданні двох кубиків велику кількість разів. Відхилення були дуже малі, що свідчить про ефективність методу Монте-Карло для обчислення ймовірностей у таких випадкових експериментах.

Варто враховувати, що точність результатів симуляції методом Монте-Карло залежить від кількості проведених випробувань. Чим більше випробувань (у цьому випадку кидків кубика), тим більш точні результати.
