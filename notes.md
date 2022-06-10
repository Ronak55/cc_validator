American Express numbers start with 34 or 37 -> 15-digit numbers

MasterCard numbers start with 51, 52, 53, 54, or 55 -> 16-digit numbers

Visa numbers start with 4 -> Visa uses 13 and 16 digit numbers

4003600000000014

4003600000000014 % 10 = 4 4003600000000014 / 100 = 40036000000000

1st case: 4 + 3 + 0 = 7 2nd case: 1 * 2 + 6 * 2 + 0 + 2 * 4 = 2 + 12 + 0 + 8 = 2 + 1 + 2 + 0 + 8 = 13 Final sum = 7 + 13 = 20

20 % 10 = 0 5 % 2 = 1

1st case:

....Iterate through the CC number
....Use modulo to get the last digit
....Add last digit to sum
....Divide the CC number by 100
....Repeat

2nd case:

....Divide the CC number by 10
....Iterate through the CC number
....Use modulo to get the last digit
....Add last digit mutiplied by 2 to the sum
       1 Use modulo for the last digit 
       2 Use division for the 1st digit
       3 Sum these up
....Divide the CC number by 100
....Repeat