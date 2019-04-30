import sys
import math
import string
c = 0
cases = int(sys.stdin.readline().rstrip())
for caseNum in range (cases):
    a = (sys.stdin.readline().rstrip())
    for i in range (len(a)):
        if (a[i] == " "):
            b = i
    if (a[(b+1):len(a)] == "true"):
        c = 5
    if (a[(b+1):len(a)] != "true"):
        c = 0
    if (int(a[0:(b)]) <= 60+c):
        print("no ticket")
    if (int(a[0:(b)]) >= 61+c and int(a[0:(b)]) <= 80+c):
        print("small ticket")
    if (int(a[0:b]) >= 81+c):
        print("big ticket")
