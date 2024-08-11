# Insertion Sort Aşamaları
[22, 27, 16, 2, 18, 6] dizisini *Insertion Sort* algoritması ile şu şekilde sıralıyoruz:
1) [22, 27, 16, 2, 18, 6] -> 22 ile 27 arasında herhangi bir değişiklik yapmadık.
2) [16, 22, 27, 2, 18, 6] -> 16'yı 22 ve 27'nin önüne yerleştirdik.
3) [2, 16, 22, 27, 18, 6] -> 2'yi tüm dizinin başına yerleştirdik.
4) [2, 16, 18, 22, 27, 6] -> 18'i 22 ve 27'nin önüne yerleştirdik.
5) [2, 6, 16, 18, 22, 27] -> 6'yı 16'nın önüne yerleştirdik.

# Big-O Gösterimi
Insertion Sort algoritmasının en kötü durum (Worst Case) zaman karmaşıklığı 
𝑂(𝑛^2)'dir. 
Çünkü her eleman, dizinin geri kalanıyla karşılaştırılır ve yer değiştirme yapılır. Bu durumda, dizideki her eleman için n adım gerekir.

# Time Complexity: 18 Sayısının Durumu
Dizi sıralandıktan sonra 18 sayısı dizinin ortasında yer aldığından, Average case kapsamına girer. ​
(Average case: Aradığımız sayının ortada olması)

# [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı
1. [2, 3, 5, 8, 7, 9, 4, 15, 6]
2. [2, 3, 5, 8, 7, 9, 4, 15, 6]
3. [2, 3, 4, 8, 7, 9, 5, 15, 6]
4. [2, 3, 4, 5, 7, 9, 8, 15, 6]
