# Integers-Between-100-200-Whose-Sum-of-Digits-Is-Even-Correct-Code
for i in range(100, 201):
    num = i
    total = 0

    while num != 0:
        digit = num % 10
        total = total + digit
        num = num // 10

    if total % 2 == 0:
        print(i)
Output:
100
102
104
106
108
110
...
198
200
