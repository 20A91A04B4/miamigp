# miamigp
t=int(input())
for i in range(t):
    x,y=map(int,input().split())
    if x*1.07>=y:
        print('Yes')
    else:
        print('No')
