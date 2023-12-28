# hw6 problem 3  
#
# Name(s): Mehrin Khan 
#
# Hmmm...
#

# This is a placeholder whose code you'll replace:
#00 read r1          # get number from user to r1
#01 read r2          # ditto, for r2
#02 mul r3 r1 r2     # r3 = r1 * r2
#03 write r3         # print what's in r3
#04 halt             # stop.

# Hmmm program to print the first n Fibonacci numbers


00 read r1         # read number of Fibonacci numbers to generate
01 setn r2 1       # initialize r2 to 1 (first Fibonacci number)
02 write r2        # print first Fibonacci number
03 setn r3 1       # initialize r3 to 1 (second Fibonacci number)
04 jltzn r1 14     # if count is negative, jump to line 14
05 write r3        # print second Fibonacci number
06 add r4 r2 r3    # add previous two Fibonacci numbers to get next one
07 write r4        # print next Fibonacci number
08 copy r2 r3      # set grandparent Fibonacci number to previous parent
09 copy r3 r4      # set parent Fibonacci number to previous sum
10 addn r1 -1     # decrement count of remaining Fibonacci numbers to generate
11 jltzn r1 14     # if count is negative, jump to line 14
12 jumpn 06         # jump back to line 6 to generate more Fibonacci numbers
13 nop             # do nothing
14 halt            # end program
