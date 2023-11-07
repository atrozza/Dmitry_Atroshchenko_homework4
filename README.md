### Dmitry Atroshchenko
### 07.11.2023
### Description: Homework 4
### My vetsion Python 3.11

## Код для вычисления чисел Фибоначчи, проверки палиндромов и генерации FizzBuzz вместо чисел кратных трём и пяти соответственно

### 1. Вычисление числа Фибоначчи
Функция `fibonacci(n)` выводит n-ое число Фибоначчи, используя только временные переменные, циклические операторы и условные операторы. Параметр `n` задается пользователем.

### Использование

'''python
n = 10  # Замените на желаемое значение n
result = fibonacci(n) 
print(f"The {n}-th Fibonacci number is: {result}")'''

### 2. Проверка на палиндром
С этим кодом можно проверить, является ли заданное число палиндромом (читается слева направо и справа налево одинаково). Число должно быть положительным целым числом произвольной длины, и задача выполняется без конвертации числа в строку или другие преобразования.

### Использование

> ### python
> ### Copy code
> n = 12321  # Замените на желаемое число для проверки
> 
> result = palindrome(n)
> 
> if result:
> 
>     print(f"{n} is a palindrome.")
> 
> else:
> 
>     print(f"{n} is not a palindrome.")

### 3. Генератор FizzBuzz вместо чисел кратных трём и пяти соответственно
Данный код создает генератор, который возвращает цифры от S до N, но вместо чисел, кратных 3, выводит "Fizz", вместо чисел, кратных 5, выводит "Buzz", а вместо чисел, одновременно кратных и 3 и 5, выводит "FizzBuzz".

### Использование

> ### python
> ### Copy code
> S = 1  # Начальное значение
> 
> N = 20  # Конечное значение
> 
> for result in fizz_buzz(S, N):
> 
>     print(result)
При желании вы можете заменить значения n, S и N на свои собственные, чтобы выполнить соответствующие вычисления и проверки.
