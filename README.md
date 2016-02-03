Problem Statement
=================

John is a restaurant manager.
He wants to give some discount coupons to the best customers of his restaurant.  

Customers are all waiting in a line (their positions are fixed), and each of them has a rating score according to the times they've been in the restaurant (the more they've been, the better customers they are).

John wants to give at least 1 discount coupon to each customer. If two customers are next to each other in the queue, then the one with the higher rating (the one that has been more times a customer) must get more coupons.

But John wants to save money, so he needs to minimize the total number of coupons given to the customers.

Input Format
============

The first line of the input is an integer N, the number of customers in John's restaurant queue. Each of the following N lines contains an integer that indicates the rating of each customer.

    1 <= N <= 10^5
    1 <= rating[i] <= 10^5 

Output Format
=============

Output a single line containing the minimum number of discount coupons John must buy.

    Sample Input:
    3  
    1  
    2  
    2

    Sample Output:
    4

Explanation
===========

Here 1, 2, 2 is the rating. Note that when two customers that have equal rating are allowed to have different number of coupons. Hence optimal distribution will be 1, 2, 1.

Another example would be:

    Sample Input:
    10
    2
    4
    2
    6
    1
    7
    8
    9
    2
    1

    Sample Output:
    19

Implementation
=============
    
    Implement your solution in the file solution.php

If you don't want to install PHP locally, you can check your solution in an online PHP executor, like [this service](http://sandbox.onlinephpfunctions.com/).