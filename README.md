# Binary-Search-Tree-Projesi

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

**Örnek:** root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

  - Öncelikle bir root belirliyoruz ve belirlediğimiz root'un sol tarafına kendinden küçük elemanları, sağ tarafına da kendinden büyük elemanları ekliyoruz.
  - Daha sonra ekleecek olan diğer elemanları da aynı mantık içerisinde eklemeye devam ediyoruz.
  
  ***
  
  Root 7 olursa,
  
            7
          /   \
         5          * 5 7'den küçük olduğu için sol tarafına yazılır.


            7
          /   \
         5      
        /      
       1            * 1 için önce 7'ye, sonra 5'e sorulur, 7 ve 5'ten küçük olduğu için 5'in sol tarafına yazılır.


            7
          /   \
         5     8    * 8, 7'den büyük olduğu için sağ tarafına yazılır.
        /      
       1        

            7
          /   \
         5     8
        /      
       1       
        \
         3           * 3, 7 ve 5'ten küçük, 1'den büyük olduğu için 1'in sağ tarafına yazılır.


            7
          /   \
         5     8
        / \      
       1   6        * 6, 7'den küçük ama 5'ten büyük olduğu için 5'in sağ tarafına yazılır.
        \
         3


                7
              /   \
             5     8
            / \     
           1   6      
          / \
         0   3           * 0 numaralı eleman 7, 5 ve 1'den küçük olduğu için 1'in sol tarafına yazılır.


                7
              /   \
             5     8
            / \     \
           1   6     9   * 9, 7 ve 8'den büyük olduğu için 8'in sağ tarafına yazılır.
          / \
         0   3
       
           
              7
            /   \
           5     8
          / \     \
         1   6     9
        / \
       0   3
            \
             4          * 4 numaralı eleman, 7 ve 5'ten küçük, 1 ve 3'ten büyük olduğu için 3'ün sağına yazılır.
           
       
              7
            /   \
           5     8
          / \     \
         1   6     9
        / \
       0   3
          / \
         2   4          * 3 numaralı eleman, 7 ve 5'ten küçük, 1'den büyük ama 3'ten küçük olduğu için 3'ün soluna yazılır.
       
     
     
    [Binary Search Tree Projesi](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje)
       
