# Patika.dev---Merge-Sort-Projesi
## Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

# AŞAMALAR
[16,21,11,8,12,22] dizi ikiye bölünmelidir.

[16,21,11] ve [8,12,22] tek eleman kalıncaya kadar bölünmeye devam edilir.

[16],[21,11] ---- [8],[12,22]

[16] - [21], [11] ----- [8] - [12], [22] Birleştirme işlemi yapılır (Küçükten Büyüğe)

[16] - [11,21] ----- [8] - [12,22] Kendi aralarında birleştirme devam eder. (Küçükten Büyüğe)

[11,16,21] ----- [8,12,22] Kendi aralarında birleştirme devam eder. (Küçükten Büyüğe)

[8,11,12,16,21,22] Sıralama tamamlandı.

Big O Gösterimi
Her adımda n işlem yapılmakta ve yukarıdan aşağı işlem sayısı 2^x = n ----> logn olduğundan O(nlogn)

www.patika.dev