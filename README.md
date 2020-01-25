# Multiplication-table


Write a python program to print the table of a given number

Print the multiplication till 10.
Logic Test Case 1

Input (stdin)
7

Expected Output

7 x 1 = 7

7 x 2 = 14

7 x 3 = 21

7 x 4 = 28

7 x 5 = 35

7 x 6 = 42

7 x 7 = 49

7 x 8 = 56

7 x 9 = 63

7 x 10 = 70
Logic Test Case 2

Input (stdin)
17

Expected Output

17 x 1 = 17

17 x 2 = 34

17 x 3 = 51

17 x 4 = 68

17 x 5 = 85

17 x 6 = 102

17 x 7 = 119

17 x 8 = 136

17 x 9 = 153

17 x 10 = 170






a=int(input())
for i in range(1,11):
    print(a,'x',i,'=',a*i)
