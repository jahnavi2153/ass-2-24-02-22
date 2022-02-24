# ass-2-24-02-22
write a program to seperate odd numbers and even numbers from the list
x=(input("enter a number"))
l=x.split()
o=[]
e=[]
for i in l:
    i=int(i)
    if i%2==0:
        e.append(i)
    else:    
        o.append(i)
for i in range(len(o)):
    print(o[i],end=' ')
print(' ',end=' ')
for i in range(len(e)):
    print(e[i],end=' ')
    
output:
enter a number45 87 24 22 5 6
45 87 5   24 22 6
