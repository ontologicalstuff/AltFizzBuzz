# AltFizzBuzz
Alternative solution to FizzBuzz
The classic solution to the classic FizzBuzz coding challenge involves using the remainder (%) operator. However, there is an alternative, if less 'elegant', solution to the problem. Since all multiples of 3 yield an integer quotient when divided by 3 and since all multiples of 5 also yield an integer quotient when divided by 5 - indeed, since for any integer n, and any number x, if x/n = integer, then n is a multiple of x. Therefore, we can use the Number.isInteger() method to see if for any number x, x/n = integer. 
