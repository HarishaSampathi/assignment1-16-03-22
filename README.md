# assignment1-16-03-22
list
s=input("enter a numbers")
l=list(s)
print(l)
res=[]
for i in l:
    if i not in res:
        res.append(i)
for i in res:
    print(i,end=" ")
output:
enter a numbers11234556666
['1', '1', '2', '3', '4', '5', '5', '6', '6', '6', '6']
1 2 3 4 5 6 
