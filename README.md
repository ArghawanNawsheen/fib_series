# fib_series
def fibonacci_series(limit):     fib_series = []     a, b = 0, 1     while a &lt;= limit:         fib_series.append(a)         a, b = b, a + b     return fib_series  limit = 50 fib_series = fibonacci_series(limit) print(" ".join(map(str, fib_series))


optional code

x,y=0,1

while y<50:
    print(y)
    x,y = y,x+y
