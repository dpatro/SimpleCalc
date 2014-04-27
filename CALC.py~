#!/usr/bin/env python3

from Tkinter import *

def add():

    num1 = float(fnumber.get())

    num2 = float(snumber.get())

    plus= num1+num2
    
    labelsum=Label(root,text='the result is : %f' % plus).grid(row=7,column=2)


def subtract():

    num1 = float(fnumber.get())

    num2 = float(snumber.get())

    diff= num1-num2
    
    labelsum=Label(root,text='the result is : %f' % diff).grid(row=7,column=2)


def multiply():

    num1 = float(fnumber.get())

    num2 = float(snumber.get())

    prod= num1*num2
    
    labelsum=Label(root,text='the result is : %f' % prod).grid(row=7,column=2)

def divide():

    num1 = float(fnumber.get())

    num2 = float(snumber.get())

    quo= num1/num2
    
    labelsum=Label(root,text='the result is : %f' % quo).grid(row=7,column=2)







root = Tk()
root.geometry('400x200+100+200')
root.title('simple calculator')

fnumber=StringVar()
snumber=StringVar()


label1 = Label(root,text='enter number 1',fg='red').grid(row=1,column=1)
label2 = Label(root,text='enter number 2',fg='red').grid(row=3,column=1)
u
number1=Entry(root,textvariable=fnumber).grid(row=1,column=2)
number2=Entry(root,textvariable=snumber).grid(row=3,column=2)

button1 = Button(root,text='+',command=add).grid(row=5,column=1)
button2 = Button(root,text='-',command=subtract).grid(row=5,column=2)
button3 = Button(root,text='*',command=multiply).grid(row=5,column=3)
button4 = Button(root,text='/',command=divide).grid(row=5,column=4)





root.mainloop()
