# Create-return
def is_palindrome(n):     # Перетворюємо число в рядок     str_n = str(n)     # Порівнюємо рядок з його реверсованою версією     return str_n == str_n[::-1]  # Приклади використання print(is_palindrome(121))  # True print(is_palindrome(123))  # False print(is_palindrome(1221)) # True
