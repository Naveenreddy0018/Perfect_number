Algorithm to check if a number is a perfect number:

Take an input number 'n' to check if it is perfect or not.
Initialize an empty list 'divisors' to store the proper divisors of 'n'.
Loop through all the numbers from 1 to n//2 (integer division), and check if the current number is a divisor of 'n'.
If a number is a divisor of 'n', append it to the 'divisors' list.
Check if the sum of the 'divisors' list is equal to 'n'. If it is, then 'n' is a perfect number. Otherwise, it is not a perfect number.
Return True if 'n' is a perfect number, otherwise return False.
