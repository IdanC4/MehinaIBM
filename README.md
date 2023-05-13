s = 0
a = int(input("type a number ->"))
m = 0
while a != 999:
    m = m + 1
    s = s + a
    a = int(input("type a number"))
else:
    if m == 0:
        print("no data")
    else:
        avg = s / m
        print("avg is ", avg)
    print("s is ", s)
    print(m)
