a = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
max_num = -1000000
for i in a:
    if i > max_num:
	max_num = i
print(max_num)   
Проходимся по каждому элементу созданного списка. Проверяем каждый элемент, больше ли он нашего максимального значения. Если он больше, то мы присваиваем максимальному значению  значению текущего элемента массива, если не больше, то ничего не делаем и переходим к следующему.
