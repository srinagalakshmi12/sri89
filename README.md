# sri89

def checkarmstrong(a):
   while a>0:
        num=a
        rev=0
        rem=a%10
        rev=rev+rem*rem*rem
        a=a//10
if num==rev:
    a=input()    
    if checkarmstrong(a):
        print('armstrong')
    else:
        print('not armstrong')
