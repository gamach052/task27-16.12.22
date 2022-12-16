###  [Task 7 kyu](https://www.codewars.com/kata/55f2b110f61eb01779000053/train/java)
Given two integers a and b, which can be positive or negative, find the sum of all the integers between and including them and return it. If the two numbers are equal return a or b.

### My solution
```Java
public class Sum
{
    public int GetSum(int a, int b)
    {
        int max = Math.max(a, b);
        int min = Math.min(a, b);
        int result = 0;
        for(int i = min; i<=max; i++){
            result += i;
        }
        return result;
    }
}


```

### Fav solution
```Java
ublic class Sum
{
    public int GetSum(int a, int b)
    {
        return (a + b) * (Math.abs(a - b) + 1) / 2;
    }
}
```
I like this solution because I like it
