[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Başlangıcı 7 ile yapıyoruz.
                                         7
                                        /
                                       5 => 5, 7'den küçük bu sebeple sola geçer.
                                       
                                        7
                                       /
                                      5
                                     /
                                    1 => 1, 5'ten küçük bu sebeple sola geçer. 
                                    
                                        7
                                       / \
                                      5   8 => 8, 7'den büyüktür bu sebeple sağ satıra geçer.
                                     /
                                    1
                                    
                                        7
                                       / \
                                      5   8 
                                     /
                                    1
                                     \
                                      3 => 3, 1'den büyük bu sebeple sağa geçer.
                                      
                                        7
                                       / \
                                      5   8 
                                     / \
                                    1   6 => 6, 5'den büyük bu sebeple sağa geçer.
                                     \
                                      3 
                                      
                                        7
                                       / \
                                      5   8 
                                     / \
                                    1   6 
                                   /  \
                                  0    3 => 0, 1'den küçük bu sebeple sola geçer.
                                  
                                        7
                                       / \
                                      5   8 
                                     / \   \
                                    1   6   9 =>9, 8'den büyük bu sebeple sağa geçer.
                                   / \
                                  0   3 
                                  
                                        7
                                       / \
                                      5   8 
                                     / \   \
                                    1   6   9 
                                   / \
                                  0   3 
                                       \
                                        4 => 4, 3'den büyük bu sebeple sağa geçer.
                                        
                                        7
                                       / \
                                      5   8 
                                     / \   \
                                    1   6   9 
                                   / \
                                  0   3 
                                     / \
                                    2   4 => 2, 3'den küçük bu sebeple sola geçer.
                                        
                                                                                