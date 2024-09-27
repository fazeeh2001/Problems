Best Coupon
Chef is ordering food online (instead of cooking) and the bill comes out to be Rs. 
X
X. Chef can use one of the following two coupons to avail a discount.

Get 
10
10 percent off on the bill amount
Get a flat discount of Rs. 
100
100 on the bill amount
What is the maximum discount Chef can avail?

Input Format
The first line contains a single integer 
T
T - the number of test cases. Then the test cases follow.
The first and only line of each test case contains a single integer 
X
X - the bill amount before discount.
Output Format
For each testcase, output the maximum discount Chef can avail.

Constraints
1
≤
T
≤
100
1≤T≤100
100
≤
X
≤
10000
100≤X≤10000
X
X is a multiple of 
100
100.

'''python
t=int(input())
for _ in range(t):
    x=int(input())
    if x>1000:
        print(int(x/10))
    else:
        print(100)
