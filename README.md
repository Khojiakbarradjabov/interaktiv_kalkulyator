# interaktiv_kalkulyator. 
Created on Wed Feb  9 00:50:40 2022

@author: khoji
"""

#Интерактив калкулятор


print("Solishtirish kalkulyatorini ishlatish uchun shartlarini bajaring")
a = float(input("Birinchi raqam: ")) # sonni so'z sifatida kiritgani uchun avvalo o'nlik songa aylantirib olishimis kerak. Shu sababli float() ishlatamiz
what = input("Qanday amal bajarish kerak? (*,/,+,-): ")

b = float(input("Ikkinchi raqam: "))
d = float(input("Solishtirish uchun javobingizni kiriting: "))
if what == "+":
    c = a+b
    if d==c:
        print("To'ppa to'gri")
    elif d>=c:
        print("Ko'payib ketti")
    elif d<=c:
        print("Kam hisobladingiz")
elif what == "-":
    c = a-b
    if d==c:
        print("To'ppa to'gri")
    elif d>=c:
        print("Ko'payib ketti")
    elif d<=c:
        print("Kam hisobladingiz")
elif what == "*":
    c = a*b
    if d==c:
        print("To'ppa to'gri")
    elif d>=c:
        print("Ko'payib ketti")
    elif d<=c:
        print("Kam hisobladingiz")
elif what == "/":
    c = a/b
    if d==c:
        print("To'ppa to'gri")
    elif d>=c:
        print("Ko'payib ketti")
    elif d<=c:
        print("Kam hisobladingiz")
else:
    print("Hato operaciya") 
