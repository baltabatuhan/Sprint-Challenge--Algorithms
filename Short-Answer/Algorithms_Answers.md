#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) This one has just one loop and there is no nested loop so answer is O(n)

b) This one has one for loop O(n) and one nested while loop (doubled each time) O(log(n)) so answer is O(n\*log(n))

c) this is classic recursive operation so answer is O(n)

## Exercise II

This is the one of classic possibility question so I solved this problem before with just two eggs. (n*(n+1)/ 2 )gives us the sum of arithmetically incresing numbers for example if n is 5 5*6/2 = 15 (1+2+3+4+5) . If we say the building is 100 floor. I would find the sum of n numbers that would be less than or equal to floor number 100.(1,2,3,4+...+13) I would start a counter forn 1 and start throwing eggs starting from the biggest number in the sequence(13) and increase my counter by that number if it doesn't break. Lets say we throw it from 13 and it didnt break. We increase the counter by 13 now its 14. And thos time throw it from 13+12(25th) floor (save this value for maximum tried floor value). If it broke this time we start throwing eggs from the last counter value by increasing the floor by one each time until we find the "f". So far we know that value f is greater than or equal to our counter value and less than our maximum tried floor. So we crack just two eggs and Maximum try equation is n(n+1)/2+(maxfloor-n(n+1)/2)
