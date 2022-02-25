# hrudaya-spandana-Feb-25-ass-1
n=int(input("enter n value:"))
l=[]
t=[]
for i in range(n):
    x=int(input())
    l.append(x)
    x=0
for i in range(n):
    if l[i]>=0:
        t.append(l[i])
for i in range(x,n):
    if l[i]<0:
        t.append(l[i])
        x=x+1
print(t)
