***
# Merge Sort Projesi  
***
[16,21,11,8,12,22] dizisini Merge Sort türüne göre aşamalarını yazıyoruz.  
+ İlk olarak dizemizi ikiye bölüyoruz.  
1-[16,21,11],[8,12,22]   
+ Sağ ve sol dizeleri tekrar ikiye bölüyoruz.  
2-[16,21] [11],[8] [12,22]    
+ Tek eleman kalıncaya dek bir daha bölüyoruz.  
3-[16] [21] [11], [8] [12] [22]  
+ Daha sonra tek elemanlı dizelerimi sıralı halde ikili ikili birleştiriyoruz. Fakat birleştirme işleminde bir kıyaslama yapılacaktır.  
[16],[21],[11],[8] [12] [22] dizelerinde karşılaştırma yaparak en küçük elemanı en başa alıp küçükten büyüğe doğru sıralama yaparak birleştiriyoruz. 
+ İkili ikili sıralayarak devam ediyoruz.  
5-[11,16,21],[8,12,22]  
+ Son birleştirmede dizimiz oluşmuştur.  
6-[8,11,12,16,21,22]  
***
## Big-O Gösterimi =
+ O(n.logn)
***
www.patika.dev

