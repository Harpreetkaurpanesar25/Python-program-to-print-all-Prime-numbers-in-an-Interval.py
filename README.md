# Python-program-to-print-all-Prime-numbers-in-an-Interval.py
s = int(input()) 
e = int(input())
# this loop is for the numbers in the interval
for i in range(s,e): 
# this loop is for dividing the numbers in the given interval from 2
    for j in range(2,i): 
        if(i % j==0): 
            break
    else: 
        print(i) 
