# 18.arrange-elements-in-sequential-order
n = int(input())
l = list(map(int,input().split()))
l.sort(reverse=True)
r=set(l)
z=list(r)
print(z)
