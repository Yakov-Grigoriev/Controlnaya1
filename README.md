import random
a = int(random.randint(1, 100))

while True:
    b = int(input('Введите число'))
    def big():
        if b > a:
            print('Больше')
    def small():
        if b < a:
            print('Меньше')
    def yes():
        if b == a:
            print('Вы угадали число')
