# phyton-dev-# 1. Kullanıcıdan ad ve soyad alıp tam adı yazdırma
ad = input("esma: ")
soyad = input("Aydın: ")
print( esma, aydın)

# 2. İki sayının toplamı, farkı ve çarpımı
sayi1 = int(input("20: "))
sayi2 = int(input("30: "))
print(sayi1 + sayi2)
print(sayi1 - sayi2)
print(sayi1 * sayi2)

# 3. Yaş 18'den büyük mü kontrol etme
yas = int(input("20: "))
print( yas > 18 )
print(yas < 18 )

# 4. Dikdörtgenin alanı ve çevresi
kisa = int(input("15: "))
uzun = int(input("30: "))
print("Alan:", kisa * uzun)
print("Çevre:", 2 * (kisa + uzun))

# 5. Girilen sayının pozitif olup olmadığını kontrol etme
sayi = int(input("-6: "))
print(sayi > 0)
print(sayi < 0)

# 6. Kelimenin ilk 3 ve son 2 harfini yazdırma
kelime = input("yoruldum: ")
print(kelime[0:3])
print(kelime[-2:])

# 7. İki sayının ortalamasını ondalıklı hesaplama
s1 = float(input("10: "))
s2 = float(input("60: "))
print("Ortalama:", (s1 + s2) / 2)

# 8. İki sayının her ikisi de çift mi kontrol etme
a = int(input("3: "))
b = int(input("2: "))
print(a % 2 == 0 and b % 2 == 0)

# 9. Metnin uzunluğu ve büyük harfe çevrilmiş hali
metin = input("geçti benden: ")
print( len(metin))
print( metin.upper())

# 10. Dairenin alanı (pi = 3.14)
r = float(input("15: "))
pi = 3.14
alan = pi * (r ** 2)
print( alan)

# 11. İki sayının eşit olup olmadığını ve birincinin büyük olup olmadığını kontrol etme
x = int(input("5: "))
y = int(input("5: "))
print(x == y)
print( x > y)

# 12. Sayının hem 3'e hem 5'e bölünüp bölünmediğini kontrol etme
n = int(input("30 "))
print( n % 3 ==  and n % 5 == 0)
