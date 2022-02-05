Proje 3
(Binary Search Tree Projesi)

<!-- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb. -->

    [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
1.  [5, 1, 3, 6, 0, 4, 2] [7] [8, 9]

    Her adımda serinin başını node olarak belirliyoruz. 
    Solunda 7'den küçük olan 5, 1, 3, 6, 0, 4 ve 2, sağında 7'den büyük olan  8 ve 9 var.

2.  [1, 3, 0, 4, 2]     [5]     [6]     [7]     [8]     [9]

    root (7)' un solundaki subtree'nin başındaki 5 yeni node oluyor.  
    Solunda 5'den küçük olan 1, 3, 0, 4 ve 2 sıralandı, büyük olan 6 leaf node olarak kaldı. 
    Sağındaki seride ilk sırada yer alan 8 ve onun sağında 8' den büyük olan 9 lead nodes olark sıralandı. 
    

3.  [0]     [1]     [3, 4, 2]   [5]     [6]     [7]     [8]     [9]

    Soldaki subtree'nin başıdaki 1' den küçük olan 0 solda leaf node, 1' den büyük olan 3, 4 ve 2 solda sıralandı. 

4.  [0]     [1]     [2]    [3]     [4]   [5]     [6]     [7]     [8]     [9]

    Son kalan subtree'nin başıdaki 3'den küçük olan 2'nin sola, büyük olan 4'ün sağa leaf node olarak kalması ile
    Binary Searh Tree tamamlanmış oldu. 


