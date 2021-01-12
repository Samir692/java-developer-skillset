Fundamental skills for Java developers

Variable increments:

Difference between ++x and x++

++x is prefix | preincrement  | first increment then return
x++ is suffix | postincrement | first return then increment

Example

int x = 4;
int a = ++x;
int b = x++;

System.out.println(a); // 5

System.out.println(b); // 5 because first x returns its current value which is 6. then b assigns this value 6 to itself. Only after x is incremented
