# Harf notu bulan program

```
# -*- coding: utf-8 -*-
notunuz=input("Sınavlarınızın ortalamasını giriniz: ")
if notunuz <0: notunuz=0
if notunuz >100: notunuz=100
if 100 >= notunuz >= 95: print ("Harf notunuz: AA")
if 95 >= notunuz >= 85: print ("Harf notunuz: AB")
if 85 >= notunuz >= 80: print ("Harf notunuz: BB")
if 80 >= notunuz >= 70: print ("Harf notunuz: BC")
if 70 >= notunuz >= 65: print ("Harf notunuz: CC")
if 65 >= notunuz >= 50: print ("Harf notunuz: CD")
if 50 >= notunuz >= 45: print ("Harf notunuz: DD")
if 45 >= notunuz >= 35: print ("Harf notunuz: DF")
if 35 >= notunuz >= 25: print ("Harf notunuz: FD")
if not (100>= notunuz >=25): print ("Harf notunuz: FF")
