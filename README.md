oceny = []

while True:
    inp = input()
    if inp == "stop":
        break
    inp = int(inp)
    if inp > 6 or inp <= 0:
        print("To nie jest ocena")
    else:
        oceny.append(inp)

print(oceny)
print(max(oceny))
print(sum(oceny)/len(oceny))
