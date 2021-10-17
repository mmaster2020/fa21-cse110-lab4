1. The bug here was that the information comes as a string, Num 1 and num 2 are strings and we did not parse. It neveer parses and is a string therefore the addition is not correct. 
2. I fixed it by passing the num1 into parseFloat so it can parse and become a number not a string



