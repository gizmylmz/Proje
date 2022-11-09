# Insertion Sort Projesi
***
[22,27,16,2,18,6] -> Insertion Sort  
Yukarı verilen dizinin sort türüne göre aşamaları şu şekildedir;  
1)Dizimizdeki en küçük sayı 2 olduğundan dolayı, 22 ile 2 yer değiştirmelidir. [2,27,16,22,18,6]  
2) Dizimizdeki en küçük ikinci sayı 6 olduğu için 6 ve 27 yer değiştirmelidir. [2,6,16,22,18,27]  
3) Dizimizdeki 6 rakamından sonraki en küçük sayı 16'dır. 16 dizideki yerinde doğru yerde olduğu için üçüncü sıra için işlem yapmamıza gerek yoktur. Dolayısıyla direkt 18 sayısı ile 22 sayısının yerini değiştirdiğimizde beşinci ve altıncı rakamlar da kendiliğinden sıraya girmiş olur. [2,6,16,18,22,27]  
***
## Big-O Gösterimi
***
- Verilen dizinin toplam eleman sayısına n dersek en küçük sayıyı bulmak için n tane işlem yapıyoruz. n=6  
- Verilen dizinin en küçük ikinci elemanını bulmak için n-1 tane işlem yapıyoruz. 6-1=5 tane işlem.  
- Verilen dizinin en küçük üçüncü elemanını bulmak için n-2 tane işlem yapıyoruz. 6-2=4 tane işlem.  
- Verilen dizinin en küçük küçük dördüncü elemanı bulmak için n-3 tane işlem yapıyoruz. 6-3=3 tane işlem.
- Verilen dizide beşinci adımda dört küçük elemandan sonraki en küçük elemanı bulmak için n-4 tane işlem yapıyoruz. 6-2=4 oluyor. İşlem altı elemanlı bir dize olduğundan dolayı altıncı elemanı bulmak adına işlem yapmadan dizi sıralaması küçükten büyüğe sıralanmış oluyor.  
- Algoritmamız n+(n-1)+(n-2)+(n-3)+(n-4)+1 kadar işlem yapmış olur. 6+5+4+3+2+1= 21 ile 21 işlemde dizi tamamlanmıştır olur.
- Big-O cinsinden ele aldığımızda, bu işlem bize birden n'e kadar olan sayıların toplamını veren formuldur. Bu formül ise [n+(n+1)/2]idi. n sayısını parantezin içine dağıttığımızda işlem n²+n/2 çıkıyor. Big-O Natational gösteriminde bunu domine eden fonksiyonu aldığımız için Big-O gösterimi= O(n²) olur.  
***
## Time Complexity
***
18 sayısı için sıraladığımızda, [...,18,...] On sekiz sayısı dizinin ortasında kalacağından ötürü Average Case sınıfına girer.
Average Case: Aradığımız sayının ortada olması.
***
## Selection Sort ile sıralama
***
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı;

[2,|3,5,8,7,9,4,15,6]

[2,3,|5,8,7,9,4,15,6] 

[2,3,4,|8,7,9,5,15,6] 

[2,3,4,5,|7,9,8,15,6] 
***
[www.patika.dev]
