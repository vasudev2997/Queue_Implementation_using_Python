class queue():
    def __init__(self, queuelength):     #Creation of Queue
        self.queue=[]
        self.length=queuelength-1       #Declaration of Length
        self.start=-1       #Declaraing the Starting Point
        
    def insert(self,value):     #Insert Function to  insert the values to the queue from the beginning
        if(self.start < self.length):
            self.queue.insert(0,value)
            self.start+=1
            print("Item Inserted in the Queue.")
            return True
        else:
            print("Queue is Full.")
            return False
        
    def remove(self):       #Remove Function to pop the values out of the Queue from rear
        if(self.start>-1):
            print("{} Removed".format(self.queue.pop()))
            self.start-=1
            return True
        else:
            print("Queue is Empty.")
            return False

def operation(queuelength):        #List of operations that one can do on a queue
    n=int(input("1. Insert  2. Remove\n"))
    if(n==1):
        l=int(input("Enter the number of items to be inserted : "))
        if(l<=queuelength):
            for i in range(l):
                addqueue.insert(input())    #Calling the insert func with value to be inserted as an argument
        else:
            print("Invalid Entry")
    elif(n==2):
        addqueue.remove()       #Calling the remove func
    else:
        print("Invalid Entry")

queuelength=int(input("Enter the length of Queue : "))      #Main Function
addqueue=queue(queuelength)     #Creating Object
operation(queuelength)
while(1):
    n=input("Continue Y/N : ")
    if(n=="Y" or n=="y"):
        operation(queuelength)
    elif(n=="N" or n=="n"):
        break
    else:
        print("Invalid Entry")
