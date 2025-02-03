Problem Statement:
The Stock Span Problem is a financial problem where we need to calculate the span of stock prices for all days.
The span of a stock's price on a given day is defined as the maximum number of consecutive days (including the current day) the price of the stock was less than or equal to its price on the current day.

Input Format:
The first line contains an integer n (the number of days).
The second line contains n space-separated integers representing the stock prices on each day.

Output Format:
Output a single line containing n space-separated integers representing the span of stock prices for each day.

Example:
Input:
7
100 80 60 70 60 75 85

Output:
1 1 1 2 1 4 6
