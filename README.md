# insertion sort
soru1:
[22,27,16,2,18,6] => Aşama 1 (n)

[2,27,16,22,18,6] => Aşama 2 (n-1)

[2,6,16,22,18,27] => Aşama 3 (n-2)

[2,6,16,18,22,27] => Aşama 4 (1)

soru2:
n + (n-1) + (n-2) + 1 = n.(n+1) / 2 

(n^2 +n) / 2 = O(n^2)

soru3:
Average Case
[2,6,16,18,22,27] => 16,18
Worst Case
[2,6,16,18,22,27] => 27
Best Case 
[2,6,16,18,22,27] => 2

soru4:
average case kapsamına girer.

soru5:
[7,3,5,8,2,9,4,15,6] => Aşama 1 (n) 
[2,3,5,8,7,9,4,15,6] => Aşama 2 (n-1) 
[2,3,4,8,7,9,5,15,6] => Aşama 3 (n-2) 
[2,3,4,5,7,9,8,15,6] => Aşama 4 (n-3)

# merge sort
soru1:
        [16, 21, 11, 8, 12, 22]
              /            \ 
    [16, 21, 11]          [8, 12, 22]
      /      \             /        \ 
  [16, 21]    [11]       [8, 12]     [22]
    /   \       |         /   \        |  
[16]    [21]   [11]     [8]    [12]   [22]
  \      /      |         \     /      | 
  [16, 21]    [11]        [8, 12]    [22]
    \   |      /           \   |     /                 
    [11, 16, 21]           [8, 12, 22]
       \   \    \          /   /   /
          [8, 11, 12, 16, 21, 22]
          
soru2:
O(nlogn)

#Binary Search Tree
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
Root: 5
Root'un sağında: 7
Root'un solounda: 3
 
                  5 
              /       \
            3          7
          /   \      /   \
         1     4    6     8
        / \               | 
       0   2              9
