# Sum-of-last-two-digits
You're given a number N (N>100). Print the sum of the last two digits of N. Input Given an integer N. (100 &lt;= N &lt;= 109) Output Print the sum of last two digits.

def sum_last_two_digits(N):
    last_digit = N % 10
    second_last_digit = (N // 10) % 10
    return last_digit + second_last_digit

N = int(input().strip())

print(sum_last_two_digits(N))
