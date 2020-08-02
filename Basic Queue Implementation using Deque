from collections import deque
def queue(l):
    n=input("1. Insert   2. Remove\n")
    if(n=='1'):
        for i in range(int(input("Enter the number of terms - "))):
            l.insert(0, input())
    elif(n=='2'):
        if(len(l)>=1):
            l.pop()
        else:
            print("Queue is Empty")
    else:
        print("Invalid Entry")

print("Queue using Deque.")
l=deque()
queue(l)
while(True):
    n=input("Continue Y/N - ")
    if(n=='y' or n=='Y'):
        queue(l)
    elif(n=='n' or n=='N'):
        break
    else:
        print("Invalid Entry")
print(l)
