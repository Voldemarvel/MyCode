sum1 = float(input("Sisesta 1. arv: "))
print("Operaatoriks on: +, -, x, /")
op = input("Sisesta operaator: ")
sum2 = float(input("Sisesta 2. arv: "))

if op == "+":
    print(sum1 + sum2)
elif op == "-":
    print(sum1 - sum2)
elif op == "x":
    print(sum1 * sum2)
elif op == "/":
    print(sum1 / sum2)
else:
    print("Viga")
