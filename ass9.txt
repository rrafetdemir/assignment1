cümle = "el alem ala dana aldı aladanalandı da biz bir ala dana alıp aladanalanamadık"
söz = {}

for i in cümle:
    a = söz.keys()
    if i in a:
        söz[i] += 1
    else:
        söz[i] = 1
print(söz)
