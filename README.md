# Selection---Insersion-Short-Projesi

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması

[22,27,16,2,18,6] -> Insertion Sort algoritmasına göre ikinci elemanımızı anahtar eleman olarak ele alalım. Yani bu durumda eleman kümemizin içindeki "27" elemanımız anahtar elemanımız oldu. "27" anahtar elemanı "22" küme elemanından büyük olduğu için sağındaki eleman olan "16" küme elemanına anahtar elemandan büyük mü küçük mü diye soruyoruz. "27" anahtar elemanı "16" küme elemanından büyük olduğu için yeni anahtar elemanımız "16" oluyor. Bu durumda kümemizin yeni dizilimi; [16,22,27,2,18,6] olmuş oluyor.

Bu işleme kümemizde doğru dizilim olana kadar devam ediyoruz. Yani sıralamalarımız şu şekilde olacak;

-> [2,16,22,27,18,6]

-> [2,16,18,22,27,6]

-> [2,6,16,18,22,27]

Big-O gösterimi o(n^2) şeklinde olur. 

Time Complexity'i dizi sıralandıktan sonra "18" küme elemanı dizimizin ortasında bulunduğu için Average Case kapsamına girer.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] -> Selection Sort algoritmasına göre dizi içerisindeki en küçük elemanın bulunup kümenin en başındaki elemanla yer değiştirilmesi gerekir. Bu prensipte aynı işlemleri 2., 3. ve dizi sıralanana kadar bütün diziye bu işlem yapılması gerekir. Bu bağlamda ilk dört adımımız şu şekilde olacaktır;

Anahtar elemanımız "2" yani;

-> [2,3,5,8,7,9,4,15,6]

-> [2,3,4,8,7,9,5,15,6]

-> [2,3,4,5,7,9,8,15,6]

-> [2,3,4,5,6,9,8,15,7]
