# MergeSortAlgorithm

[16,21,11,8,12,22] Steps of Merge Sort 

1- Separate list to two parts. [16,21,11] and [8,12,22]
2- Separate these parts to two parts. [16,21,11] -> [16,21] and [11]. [8,12,22] -> [8,12] and [22]
3- Separate these parts which include two number. [16,21] -> [16] and [21]. [8,12] -> [8] and [12]
4- Merge in order. [16] and [21] -> [16,21]. [8] and [12] -> [8,12]
5- Merge parts that include two number and parts that include one number with order. [16,21] and [11] -> [11,16,21]. [8,12] and [22] -> [8,12,22]
6- Merge last parts with order. [11,16,21] and [8,12,22] -> [8,11,12,16,21,22]

Big O Notation is O(nlogn)
