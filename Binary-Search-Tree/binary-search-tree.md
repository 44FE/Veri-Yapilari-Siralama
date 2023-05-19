## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.        

1. ilk elemanı(7) root olarak kabul edersek 7 den küçük olanları sol tarafa büyük olanları sağ tarafa yazmamız gerekir.Elemanların yerleri sırayla kontrol edilerek bulunur.
2. 5 < 7 olduğundan 5  -> 7'nin soluna yazılır.
3. 1 < 7 sola bakılacak, 1 < 5 olduğundan 1 -> 5'in soluna yazılır.
4. 8 > 7 olduğundan 8 -> 7'nin sağına yazılır.
5. 3 < 7 sola bakılacak,3 < 5 sola bakılacak, 3 > 1 olduğundan 3 -> 1'in sağına yazılır.
6. 6 < 7 sola bakılacak, 6 > 5 olduğundan 6 -> 5'in sağına yazılır.
7. 0 < 7 sola bakılacak,0 < 5 sola bakılacak, 0 < 1 olduğundan 0 -> 1'in soluna yazılır.
8. 9 > 7 sağa bakılacak, 9 > 8 olduğundan 9 -> 8'in sağına yazılır.
9. 4 < 7 sola bakılacak, 4 < 5 sola bakılacak, 4 > 1 sağa bakılacak , 4 > 3 olduğundan 4 -> 3'ün sağına yazılır.
10. 2 < 7 sola bakılacak, 2 < 5 sola bakılacak, 2 > 1 sağa bakılacak, 2 < 3 olduğundan 2 -> 3 'ün soluna yazılır.

 >             7  
 >            / \
 >           5   8
 >          / \   \
 >         1   6   9 
 >        / \   
 >       0   3  
 >          / \
 >         2   4  