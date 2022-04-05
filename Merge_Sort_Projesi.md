[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

------------------------------

Liste önce [16,21,11] ve [8,12,22] olacak şekilde ikiye bölünür. Her biri tek bir sayı oluncaya kadar 2'ye bölünür. 
Burada ortadaki değerin sağdaki veya soldaki bir değerle birlikte bölünecek olması önemli değildir.
[16,21], [11], [8,12], [22]
Bir kez daha ikiye bölünmesi gerekiyor.
[16], [21], [11], [8], [12], [22] 
Şimdi bu sayıları birleştircez. Birleştirirken kendi içlerinde küçükten büyüğe doğru sıralayacağız.
[16,21], [8,11], [12,22]
Yine birleştirme işlemi uygulayacağız ve birleştirirken kendi içlerinde sıralayacağız.
[8,11,16,21], [12,22]
Son bir işlem daha
[8, 11, 12, 16, 21, 22]

Big-O: Her bir işlemde işlem sayısı yarıya iniyor ve n kez tekrarlanıyor. Bu yüzden O(nlogn)'dir.
