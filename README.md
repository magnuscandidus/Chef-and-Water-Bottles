# Chef-and-Water-Bottles
# cook your dish here
for i in range (int(input())):
    n,x,y = map(int,input().split())
    a = y//x
    if(n>=a):
        print(a)
    else:
        print(n)
