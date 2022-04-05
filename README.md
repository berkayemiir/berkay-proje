# berkay-proje
insertion projesi
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

ilk önce sayıları küçükten büyüğe sıralıyoruz nasıl mı, 2,6,16,18,22,27 bu ınsertıon sıralama şekli oluyor.
Big-O: n+(n-1)+(n-2)+...+1 tane işlem var. Bu işlem sayısını hesaplamak için gerekli formül n.(n+1)/2=(n^2 + n)/2 tane işlem var. Big-O'da en büyük olan n^2 fonksiyonu baz alınır. Çünkü elimizdeki veri sayısı yeterince arttığında geriye kalan terimler bir anlam ifade etmez. Dolayısıyla Big-O, O(n^2) olur.

18 sayısı, ortada yer alan 16 ve 18 sayılarından birisi olduğundan dolayı Average case kapsamına girer.

Adım 1: [2,3,5,8,7,9,4,15,6] Adım 2: [2,3,5,8,7,9,4,15,6] Adım 3: [2,3,4,8,7,9,5,15,6] Adım 4: [2,3,4,5,7,9,8,15,6]
