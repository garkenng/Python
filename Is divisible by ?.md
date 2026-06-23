## Is divisible by ?
### Summary<br>

Create a program to find and print all numbers from 0 to 1000 (both included), that are divisible by 7 and whose digits sum are divisible by 3.
<br><br>

```
def divisible_by_7_and_sum_by_3(start,stop):
    for num in range(start, stop):
        if num % 7 == 0:
            digit_sum = sum(int(digit) for digit in str(num))
            if digit_sum % 3 == 0:
                print(num)
                
divisible_by_7_and_sum_by_3(0,1001)
```
<br>

Output<br><br>

```
0
21
42
63
84
105
126
147
168
189
210
231
252
273
294
315
336
357
378
399
420
441
462
483
504
525
546
567
588
609
630
651
672
693
714
735
756
777
798
819
840
861
882
903
924
945
966
987
```

