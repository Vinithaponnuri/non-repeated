PROGRAMME:
x=[1,2,1,3,2,4,2,5,4,6,5,7,6,4]
l=[]
l1=[]
for i in x:
    if i not in l:
        if x.count(i)==1:
            l.append(i)
            l1.append(x.count(i))
print(l)
print(l1)
OUTPUT:
[3, 7]
[1, 1]
