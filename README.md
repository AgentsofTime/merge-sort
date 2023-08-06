[16,21,11,8,12,22] -> Merge Sort
• Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Dizi her aşamada ikiye bölünür ve en sonda sıralama yapılır
[16 21 11 ] [ 8 12 22]
[16 21] [ 11] [ 8 12] [22]
[16] [21] [11] [8] [12] [22]
[16 21] [11] [8 12] [22]
[11 16 20] [8 12 22]
-----> [8 11 12 16 20 22]

Big-O gösterimini yazınız.
Her itersayonda n-1 kadar kontrol işlemi yapılır.Time complexity n olarak alınabilir,aynı zamanda dizi boyutu her adımda yarıya ineceğinden 2^x=n’den log2n=x yani logn olarak alınabilir.
Bu durumda O(nlogn)şeklinde ifade edilir.(çalışma zamanı X iterasyon sayısı)