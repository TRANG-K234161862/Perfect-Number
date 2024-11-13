# Perfect-Number
Chương trình số hoàn hảo
n=int(input("Input n:"))
sum_divisor=0
for i in range(1,n):
    if n %i==0:
        sum_divisor=sum_divisor+i
if sum_divisor==n:
    print(n,"is a perfect number")
else:
    print(n, "is NOT a perfect number")
