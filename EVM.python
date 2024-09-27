from tkinter import *
root=Tk()
text=Text(root)
root.title("EVM")
root.geometry("700*500")

v1=0
v2=0
def vote1():
    global v1
    v1=v1+1
    print("Value of v1",v1)
def vote2():
    global v2
    v2=v2+1
    print("value of v2",v2)

def result():
    if(v1>v2):
        Label1(root,text="Winner party-1",height=2,width=20).grid(row=3,column=2)
    elif(v2>v1):
        Label(root,text="Winner: party-2",height=2,width=20).grid(row=3,column=2)
    elif(v1==v2):
        Label(root,text="Result Tie",height=2,width=20).grid(row=3,column=2)


Label(root,text="Party1",height=2,width=10).grid(row=1,columns=1)
btnl=Buttom(root,text="vote",command=vote1).grid(row=1,column=2)

Label(root,text="Party2",height=2,width=10).grid(row=2,columns=1)
btn2=Buttom(root,text="vote",command=vote2).grid(rows=2,column=2)



