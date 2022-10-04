Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

    - root olarak 5 seçilir                                          5
    - 7>5 7 5'in sağına yazılır                                      5
                                                                      \
                                                                       7
    
    - 1<5 1 5'in soluna yazılır                                      5s
                                                                    / \
                                                                   1   7  

    - 8>5 sağa inilir, 8>7 8 7'nin sağına yazılır                    5
                                                                    / \
                                                                   1   7
                                                                        \
                                                                         8

    - 3<5 sola inilir, 3>1 3 1'in sağına yazılır                     5
                                                                    / \
                                                                   1   7
                                                                    \    \
                                                                     3    8


    - 6>5 sağa inilir, 6<7 6 7'nin soluna yazılır                      5
                                                                    /     \
                                                                   1       7
                                                                    \     /  \
                                                                     3   6    8  

    - 0<5 sola inilir, 0<1 0 1'in soluna yazılır                       5
                                                                    /     \
                                                                   1       7
                                                                  / \     /  \
                                                                 0   3   6    8


    - 9>5, sağa inilir, 9>7 sağa inilir,
      9>8 9 8'in sağına yazılır                                        5
                                                                    /     \
                                                                   1       7
                                                                  / \     /  \
                                                                 0   3   6    8
                                                                               \
                                                                                9

    - 4<2 sola inilir, 4>1 sağa inilir,
      4>3 4 3'ün sağına yazılır                                        5
                                                                    /     \
                                                                   1       7
                                                                  / \     /  \
                                                                 0   3   6    8
                                                                      \         \
                                                                       4         9

    - 2<3 sola inilir, 2>1 sağa inilir,
      2<3 2 3'ün soluna yazılır                                        5
                                                                    /     \
                                                                   1       7
                                                                  / \     /  \
                                                                 0   3   6    8
                                                                    / \         \
                                                                   2   4         9                                                                             
                                                                 
                                                                                                                                                   







