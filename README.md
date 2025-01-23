# Task - 2

Генерация функций фильтра четных чисел, нахождения максимального элемента в списке, а также нахождения числа фибоначчи рекурсией или циклом на ЯП Swift и Python.

Присутствует обработка списка, который внутри запроса пользователя.

### Вызов функций
``` swift
textToCode.generatedCode(inputText: "напиши функцию фильтра четных чисел в списке [5, 6, 70, 1, 2, 8] на swift")
textToCode.generatedCode(inputText: "напиши функцию фильтра четных чисел в списке [1, 2, 3, 4, 5, 6] на питоне")

textToCode.generatedCode(inputText: "напиши функцию нахождения максимального элемента в [5, 6, 70, 1, 2, 8] на свифт")
textToCode.generatedCode(inputText: "напиши функцию нахождения максимального элемента в списке [1, 2, 3, 4, 5, 6] на python")
textToCode.generatedCode(inputText: "напиши функцию нахождения максимального элемента на python")

textToCode.generatedCode(inputText: "напиши функцию нахождения фибоначчи на свифт рекурсией")
textToCode.generatedCode(inputText: "напиши функцию нахождения фибоначи swift через цикл")
textToCode.generatedCode(inputText: "напиши функцию нахождения фибоначи на питоне через рекурсию")
textToCode.generatedCode(inputText: "напиши функцию нахождения фибоначчи на python циклом")

textToCode.generatedCode(inputText: "напиши функцию нахождения фибоначчи на java циклом")
```

### Вывод в консоли
``` console
напиши функцию фильтра четных чисел в списке [5, 6, 70, 1, 2, 8] на swift
func filterEvenNumbers(from numbers: [Int]) -> [Int] {
    return numbers.filter { $0 % 2 == 0 }
}

// Пример использования
let numbers = [5, 6, 70, 1, 2, 8]
let evenNumbers = filterEvenNumbers(from: numbers)
print(evenNumbers)  // Вывод: [6, 70, 2, 8]

 

напиши функцию фильтра четных чисел в списке [1, 2, 3, 4, 5, 6] на питоне
def filter_even_numbers(numbers):
    return [num for num in numbers if num % 2 == 0]

# Пример использования
numbers = [1, 2, 3, 4, 5, 6]
even_numbers = filter_even_numbers(numbers)
print(even_numbers)  # Вывод: [2, 4, 6]

 

напиши функцию нахождения максимального элемента в [5, 6, 70, 1, 2, 8] на свифт
func findMax(in list: [Int]) -> Int? {
    return list.max()
}

let numbers = [5, 6, 70, 1, 2, 8]
if let maxNumber = findMax(in: numbers) {
    print(maxNumber)
} else {
    print("Список пустой.")
}
// 70

 

напиши функцию нахождения максимального элемента в списке [1, 2, 3, 4, 5, 6] на python
def find_max(lst):
    if lst:
        return max(lst)
    return None

numbers = [1, 2, 3, 4, 5, 6]
max_number = find_max(numbers)

if max_number is not None:
    print(f"Максимальное число {max_number}")
else:
    print("Список пустой.")
#Максимальное число 6

 

напиши функцию нахождения максимального элемента на python
def find_max(lst):
    if lst:
        return max(lst)
    return None

numbers = []
max_number = find_max(numbers)

if max_number is not None:
    print(f"Максимальное число {max_number}")
else:
    print("Список пустой.")
#Список пустой.

 

напиши функцию нахождения фибоначчи на свифт рекурсией
func fibonacci(_ n: Int) -> Int {
    if n <= 0 {
        return 0
    } else if n == 1 {
        return 1
    } else {
        return fibonacci(n - 1) + fibonacci(n - 2)
    }
}

// Пример использования
let n = 10  // Замените на нужное значение
print("Число Фибоначчи для $n): $fibonacci(n))")

 

напиши функцию нахождения фибоначи swift через цикл
func fibonacci(n: Int) -> Int {
    if n <= 0 {
        return 0
    } else if n == 1 {
        return 1
    }

    var a = 0
    var b = 1
    for _ in 2...n {
        let temp = b
        b = a + b
        a = temp
    }
    return b
}

// Пример использования
let n = 10
print("Fibonacci number at position $n is $fibonacci(n: n)")

 

напиши функцию нахождения фибоначи на питоне через рекурсию
def fibonacci(n):
    if n <= 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fibonacci(n - 1) + fibonacci(n - 2)

# Пример использования
n = 10  # Замените на нужное значение
print(f"Число Фибоначчи для {n}: {fibonacci(n)}")

 

напиши функцию нахождения фибоначчи на python циклом
def fibonacci(n):
    if n <= 0:
        return 0
    elif n == 1:
        return 1

    a, b = 0, 1
    for _ in range(2, n + 1):
        a, b = b, a + b
    return b

# Пример использования
n = 10
print(f"Фибоначчи с номером позиции {n} это {fibonacci(n)}")

 

напиши функцию нахождения фибоначчи на java циклом
Не указан язык, на котором надо решить Вашу проблему, либо ваш язык не поддерживается.
```
