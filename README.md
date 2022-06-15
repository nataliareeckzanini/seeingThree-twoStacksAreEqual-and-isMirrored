For this assignment you will use the Assignment7.java   Download Assignment7.java and write your code where designated.  There will be three methods.

Problem #1

Write a method called "seeingThree" that takes a stack of integers as a parameter and replaces every value in the stack with three occurrences of that value. For example, suppose the stack stores these values:

bottom [3, 7, 1, 14, 9] top

Then the stack should store these values after the method terminates:

bottom [3, 3, 3,7,7, 7, 1,1, 1, 14,14, 14,9, 9, 9] top

Notice that you must preserve the original order. In the original list the 9 was at the top and would have been popped first. In the new stack the two 9s would be the first values popped from the stack. You may use a single queue as auxiliary storage to solve this problem.

Problem #2

Write a method called "twoStacksAreEqual" that takes as parameters two stacks of integers and returns true if the two stacks are equal and that returns false otherwise. To be considered equal, the two stacks would have to store the same sequence of integer values in the same order. Your method is to examine the two stacks but must return them to their original state before terminating. You may use one stack as auxiliary storage.

Problem #3

Write a method called "isMirrored" that takes a queue of integers as a parameter and returns true if the numbers in the queue represent a palindrome (and false otherwise). A sequence of numbers is considered a palindrome if it is the same in reverse order. For example, suppose a queue called q stores these values:

front [3, 8, 17, 9, 17, 8, 3] back
Then the call of isMirrored(q); should return true because this sequence is the same in reverse order. If the queue had instead stored these values:

front [3, 8, 17, 9, 4, 17, 8, 3] back
The call on isMirrored would instead return false because this sequence is not the same in reverse order (the 9 and 4 in the middle don't match). The empty queue should be considered a palindrome. You may not make any assumptions about how many elements are in the queue and your method must restore the queue so that it stores the same sequence of values after the call as it did before. You may use one stack as auxiliary storage.

 

 Deliverables:1) Turn in your finished Assignment7.Java file that compiles and runs.  2) QA documents with screen shots of your working program.
