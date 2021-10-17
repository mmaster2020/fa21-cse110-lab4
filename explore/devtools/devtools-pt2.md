List of breakpoints:
<a href="https://github.com/mmaster2020/fa21-cse110-lab4/blob/1628e6b6009250e05db975a5372543b8680e06ee/explore/devtools/result-calculateSum.png"> breakpoints</a>
<br>
Watch Expressions:
<a href="https://github.com/mmaster2020/fa21-cse110-lab4/blob/a7751434809e260bb5f3cef305b32238676d1d9d/explore/devtools/result-dataType.png">watching</a>

1. The bug here was that the information comes as a string, Num 1 and num 2 are strings and we did not parse. It neveer parses and is a string therefore the addition is not correct. 
2. I fixed it by passing the num1 into parseFloat so it can parse and become a number not a string
This is the fix:
<a href="https://github.com/mmaster2020/fa21-cse110-lab4/blob/1628e6b6009250e05db975a5372543b8680e06ee/explore/devtools/fix.png">bugfixed</a>



