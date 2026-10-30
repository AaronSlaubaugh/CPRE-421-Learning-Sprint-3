The html that the AI helped me create helped show a simple security issue that is simple to overlook. It shows even without putting print statements in your code that could reveal extra information
you can still reveal information through the execution time. Before I usually think of execution time as a way to see how good a application runs and never thought about it as a security vulnerability.
The lab demonstrates that there could be a hidden pattern in the execution time. For a password we could continue to guess until the time gets longer which would mean that the check goes further down the word
and that means we got more letters correct. This is for the early exit version. There is a slider to show that the attacker may need to test a char multiple times to see if the character was correct.
We change the code to have a fixed time to prevent attackers from inferring information from timings. This lab helped me understand Timing side channel attacks better since I was thinking why do people leave
random print statements in their code to give information. This helped show that information could be hidden else where such as in timings.
