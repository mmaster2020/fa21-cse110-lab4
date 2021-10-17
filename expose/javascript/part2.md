1. At line 12 it will just be printing how many time the loop ran. So in this case we know that the length of the prices array is 3 therefore that will be printed.
2. Here it will be printing out the discounted price. In this case it will print out 150. This is because it will stop at the 3rd loop. The third item in teh array is 300. Then we will multiply that by (1-0.5) whcih is 0.5 making it 300/2 and that is 150.
3. They will be returning the final price. Similar to the discounted price this will get the discounted price multiply it by 100 and then divide by 100. This will leave the answer at 150.
4. There is not an error but nothing will be printed out. Here the function will return an array named discounted. The finalprice gets pushed in there each cycle. I believe the actual array will have [150, 100, 50]. 
5. In this case there will be a reference error because to the computer i is not defined. This is because i is a let variable and a let variable is limited to only being functional in a block {} and outside of it it is useless.
6. The same issue will happen fo this question. Again let is used to declare a varaible but since the console.log(discountedPrice) is outside of the block {} therefore discountedPrice to the computer is not defined. It is again a reference error.
7. This will return 150. This is because this let varibale is inside the block {} therefore it is defined. Since it is defined and it is in the block it will be functional and will not have any refernce error.
8. There is not an error but nothing will be printed out. Here the function will return an array named discounted. The finalprice gets pushed in there each cycle. I believe the actual array will have [150, 100, 50]. 
9. Here since let is used therefore i will not be detemrined. Let is used in the for loop block and console.log(i); is placed outside that block. Let can only be used within a block therefore there will be a refernce error. 
10. Since length of the array never changes and it is always three the program will just simply return 3.
11. Here nothin will be shown and printed. I believe that it will just return an empty array since that is what is declared in the first place and nothing can be changed to it.
12. Notation
    1.  a. student.name
    2.  b. student['Grad Year']
    3.  c. student.greeting();
    4.  d. student['Favorite Teacher'].name
    5.  e. student.courseLoad[0]
13. Arithmetic
     1.   a. This will be 32 because it will  be a string 3 and then adding a 2 next to it making it 32.
     2.   b. This will be 1. This is because the string 3 will be converted to a number 3 and then when we subtract that with 2 it will equal to 1.
     3.   c. This will be 3. Null in this case will be worth 0 and 3+0 is equal to 3.
     4.   d. This will be 3null. This is because null is coerced to a string when the + operator is applied. 
     5.   e. This will be 4. This is because true converts to 1 as a number and 1 +3 is equal to 4.
     6.   f. This will be 0. This will be 0 becuase both false and null will be worth 0 and it will equal to 0.
     7.   g. This will be 3undefined. Because undefined is coereced as a string whne the + is applied.
     8.   h. This will be NaN. This is because undefined will return NaN.
14. Comparison
    1.  a. This will be true. This is true because the '2' will be converted to a number making it 2. 2>1 which is true because 2 is greater than 1.
    2.  b. This will be false. This is because they are strings they will be compared lexicographically. Each characted is compared one at a time.
    3.  c. This will be true. This is because the string will be converted to a number making '2' to 2 and it will equal to 2 making it true.
    4.  d. This will be false. This is because both are not the same type. 
    5.  e. This will be false. This is because javascript converts 2 to 1 and when we compare 2==1 it will not be equal.
    6.  f. This will be true. This is becaase because Boolean(2) is basically true and when we compare it to true it is the same therefore the answer will be true.
15. == compares two variables no matter the type while === compares two variables but checks the types
16. check part2-question16.js file
17. This creates a new array by applying the callback function to each eleement in teh array. doSomething is the callback in this caass. So teh goal for this is to double each element in the array. So this [1,2,3] will return [2,4,6]
18. check part2-question18.js
19. This will print out:
    1
    4
    3
    2
It will be on its on line If there is any issue on git.