# Лабораторная работа №8. Применение функций.

## Практическая часть.

1. Напишите простую игру использующую рандом в языке python. Правила игры (2 игрока), компьютер и вы. Начинает игру компьютер бросает вам мяч, с вероятностью 70% вы его ловите, с вероятностью 30% нет. Если вы поймали мяч то отчечаете на вопрос вы, если нет то компьютер придумывает что-то. Далее вы бросаете мяч компьютеру, он ловит его с вероятностью 70%, и отчечает на вопрос сам рандомно, если он не поймал мяч то вы отвечаете на вопрос.

2.Напишите функцию reverse_number, которая принимает число в качестве параметра и возвращает перевернутое число.
Напишите функцию is_palindrome, которая проверяет, является ли число палиндромом.
Напишите функцию process_numbers, которая принимает список чисел в качестве параметра, переворачивает каждое число и выводит новый список с перевернутыми числами. Если какое-то число является палиндромом, ваш код должен об этом сообщить.

3. Допустим, у вас есть некоторая сумма денег, которую вы хотите инвестировать под определенный процент. Напишите программу, которая принимает на вход начальную сумму, процентную ставку и количество лет, на которые вы планируете инвестировать деньги. Программа должна рассчитать и вывести итоговую сумму по истечении указанного количества лет с учетом сложного процента.

4. Допустим, два игрока играют в игру, где каждый выбирает одну из трех дверей. За одной из дверей находится приз, а за двумя другими - ничего. После того как оба игрока сделали свой выбор, открывается одна из дверей, за которой нет приза. Затем игрокам предлагается изменить свой выбор на другую дверь или остаться при своем первоначальном выборе.
Напишите программу, которая моделирует эту игру и определяет вероятность выигрыша для игрока, который решает изменить свой выбор и для игрока, который остается при своем первоначальном выборе.
Двери должны генерироваться рандомно к примеру [“приз”,“пусто”,“пусто”], [“пусто”,“приз”,“пусто”]. Вы должны написать функцию которая принимает количество двирей и количество призов. Фунция должна вернуть, (список, словарь или еще что-то на ваш выбор в зависимости от реализации), в котором будут имметировться двери.

5.Реализуйте систему лутбоксов для игры, у вас должнобыть несколько списков с предметами: обычные, редкие, эпические, легендарные. У каждого из типов есть свой шанс на дроп, для обычных 0.7, для редких 0.2, для эпических (0.1), для легендарных (0.05). Также существует система гаранта за 20 открытых лутбоксов, выпадает легендарный предмет. При запуске программы должно происходить 20 автоматических открытий лутбокса, в результате программа должна написать сколько выпало, обычных, редких, эпических и легендарных. Если эпических выпало больше 3 то вы должны написать (Удача!), если легендарных больше 1, вы должны написать (Большая удача!), в конце вы должны написать список полученных предметов, вы должны отобразить разным цветов разное качество полученных предметов (белый - обычный, синий - редкий, фиолетовый - эпический, оранжевый - легендарный).