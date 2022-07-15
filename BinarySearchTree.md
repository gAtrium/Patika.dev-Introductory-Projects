# Binary Search tree
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] </br>
>Write steps for binary search tree

1. Root is determined as 7
2. 5 is smaller than root, write it as a left child of root.
3. 1 is smaller than root->rightnode, write it as the left child.
4. 8 is bigger than root, write it as the right child.
5. 3 is smaller than root->leftnode, write it as the left child.
6. 6 is smaller than root->rightnote, write it as the left child.
7. 0 is smaller than root->leftnode->leftnode, write it as the left child.
8. 9 is bigger than root->rightnode, write it as the right child.
9. 4 is bigger than root->leftnode->leftnode, write it as the right child.
10. 2 is smaller than root->leftnode->leftnode->rightnode, write it as the left child.

                                        7(1)
                        5(2)                            8(4)
                1(3)            3(5)            6(6)            9(8)
        0(7)            4(9)
                2(10)
