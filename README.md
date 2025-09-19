n=int(input(""))
k=int(input(""))
for i in range(1,k+1):
    s=int(str(n)[::-1])
    n=n+s
    print(f"{i}:{n}")
    if str(n)==str(n)[::-1]:
        print(i,n)
        break
else:
    print([-1,-1])
