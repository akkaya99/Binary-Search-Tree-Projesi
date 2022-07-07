# Binary-Search-Tree-Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

1.) İlk değer 7 olduğu için root olarak seçilir.
2.) 5, 7'den küçük olduğu için 7'nin soluna eklenir.
3.) 1, 7 ve 5'ten küçük olduğu için 5'in soluna eklenir
4.) 8, 7'den büyük olduğu için 7'nin sağına eklenir.
5.) 3; 7 ve 5'ten küçük, 1'den büyük olduğu için 1'in sağına eklenir.
6.) 6; 7'den küçük, 5'ten büyük olduğu için 5'in sağına eklenir.
7.) 0; 7, 5 ve 1'den küçük olduğu için 1'in soluna eklenir.
8.) 9; 7 ve 8'den büyük olduğu için 8'in sağına eklenir.
9.) 4; 7 ve 5'ten küçük, 1'den ve 3'ten büyük olduğu için 3'ün sağına eklenir.
10.) 2; 7 ve 5'ten küçük, 1'den büyük ve 3'ten küçük olduğu için 3'ün soluna eklenir.


                              7
                             / \
                            5   8
                           / \   \
                          1   6   9
                         / \
                        0  3
                          / \
                         2   4
