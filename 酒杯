num = int(input("请输入金额："))
price = int(input("请输入单价："))
n = num / price
p = n
q = n
count = 0
while p >= 2 or q >= 4:
    t = p // 2 + q // 4
    count += t
    p = p % 2 + t
    q = q % 4 + t
count = count + n
print(int(count))
