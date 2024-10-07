# lab8
rydok1 = input("Введіть рядок:")
rydok2 = input("Введіть рядок:")
rydok1 = rydok1.split()
rydok2 = rydok2.split()
result1 = []
result2 = []
for rydok in rydok1:
    if len(rydok) > 2:
        md_rydok = rydok[0] + rydok[1:-1].upper() + rydok[-1]
result1.append(md_rydok)

for rydok in rydok2:
    if len(rydok) > 2:
        md_rydok = rydok[0] + rydok[1:-1].upper() + rydok[-1]
result2.append(md_rydok)

print(result1)
print(result2)
