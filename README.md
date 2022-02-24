x=input('Enter numbers:')
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
    
    
    Output:enter numbers:5 6 7 8 9 1
           5 7 9  6 8 1
