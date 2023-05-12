# Artificial-Intelligence
This is a repository which provides codes and solutions to the problems generally asked in the subject of Artificial Intelligence in College and Universities.
The common problem in the early stages of AI is the Water-Jug Problem.
Here's a description to how to solve this problem.


X= Big Jug
Y= Small Jug
Z= The amount of litres required to be measured by the two jugs X & Y and the end result to be measured in Jug X.
Input: X = 4, Y = 3, Z = 2
Output: {(0, 0), (0, 3), (3, 0), (3, 3), (4, 2), (0, 2)}
Explanation: 
    Step 1:- First we will fill the 4 litre jug completely with water. 
    Step 2:- Then optimal approach would be to empty water from 4-litre jug into 3-litre  (leaving 1L water in 4L jug and 3L completely full). Hence, we got 1L water.
    Step 3:- Now, Empty water from 3L.
    Step 4:- Pour the water from 4L jug into 3L jug Now 4L container is completely empty and 1L water in present in 3L litre jug.
    Step 5:- Fill the 4L jug with water completely again.
    Step 6:- On transferring  water from 4L jug to 3L jug, we will get 2L water in 4L jug which was our required quantity.

