For each of the cohort exercises in coding exercise, please provide a brief explanation of your answer, as well as attaching screenshots of the running results.

(10 points) Cohort Exercise 1: Given FactorPrime.java, write a program so that multi-threads factor the number at the same time. Print the factor as soon as it is found.\

![image](https://github.com/sdsorca-cse/CE6_readme/blob/main/photo_4_2023-06-26_23-05-03.jpg)

Name Your Solution: FactorThreadNoInterrupt.java

(10 points) Cohort Exercise 2: Continue with Exercise 1, modify your program such that once the factors are found, stop all threads as soon as possible by interrupting the threads. 

Hints: Use a static Boolean variable found for communication between threads\



Name Your Solution: FactorThread.java

(10 points) Cohort Exercise 3: Assuming that we would like to maintain that “saving + cash = 5000” always, fix the following class: LockStaticVariables.java.

Hint: Think about what is the lock?\

![image](https://github.com/sdsorca-cse/CE6_readme/blob/main/photo_3_2023-06-26_23-05-03.jpg)

Name Your Solution: LockStaticVariablesFixed.java

(20 points) Cohort Exercise 4: Producer/Consumer Pattern

Exercise: fixed the Buffer class in BufferExample.java so that it is thread-safe and efficient

Name Your Solution: BufferExampleFixed.java Can you point out all the potential order of execution before and after your fix?

(10 points) Cohort Exercise 5: Given DiningPhil.java, explain whether it is possibly deadlocking. In what sequence of execution order leads to deadlock? Write a test case which potentially demos the deadlock.\

ANS: It is possibly deadlocking, because each guy tries to pick up the left fork first before picking up the right fork, but if they all pick up their left forks at the same time, they could be  stuck waiting for the right fork from the guy after them. This is a circular dependency.

![image](https://github.com/sdsorca-cse/CE6_readme/blob/main/photo_2_2023-06-26_23-05-03.jpg)


Name Your Solution: DiningPhilDemo.java

Can you point out the order of execution leads to deadlock?

(20 points) Cohort Exercise 6:

• Fix Experiment.java with using volatile. • Name your solution: ExperimentFix1.java • Fix Experiment.java through locking. • Name your solution: ExperimentFix2.java\

![image](https://github.com/sdsorca-cse/CE6_readme/blob/main/photo_6_2023-06-26_23-05-03.jpg)


(20 points) Cohort Exercise 7: • Fix DiningPhil.java by making it deadlock-free, in two different ways: • fixed global order, name your solution: DiningPhilFixed1.java • avoid deadlocks, name your solution: DiningPhilFixed2.java

1:![image](https://github.com/sdsorca-cse/CE6_readme/blob/main/photo_5_2023-06-26_23-05-03.jpg)

2:![image](https://github.com/sdsorca-cse/CE6_readme/blob/main/photo_1_2023-06-26_23-05-03.jpg)

