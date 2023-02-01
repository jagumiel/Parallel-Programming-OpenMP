# Parallel Programming in C with OpenMP
## _Introduction_

Today is February 1st, 2023. A new challenge has come to my mind and it is to improve my skills in parallel programming. To do so, I will use the month of February to do one parallelisation exercise per day. The idea is to make a new commit every day in this repository.

## _Exercise statements:_
1. Hello World: Print "Hello World" from multiple threads in parallel.
2. Sum of numbers: Compute the sum of an array of numbers in parallel.
3. Dot product: Compute the dot product of two vectors in parallel.
4. Matrix multiplication: Compute the product of two matrices in parallel.
5. Reduction: Compute the sum, minimum, and maximum of an array of numbers in parallel.
6. Parallel loop: Parallelize a for loop that performs some computation on each iteration.
7. Parallel section: Use parallel sections to execute multiple sections of code in parallel.
8. Critical section: Use a critical section to protect a shared resource from concurrent access.
9. Atomic operations: Use atomic operations to update a shared variable in parallel.
10. Barriers: Use a barrier to synchronize the completion of work by multiple threads.
11. Master thread: Identify and execute code only by the master thread.
12. Single thread: Execute code only by a single thread, excluding the other threads.
13. Private variables: Use private variables to store per-thread data.
14. Shared variables: Use shared variables to store data that can be accessed by multiple threads.
15. Firstprivate variables: Use firstprivate variables to initialize per-thread data.
16. Lastprivate variables: Use lastprivate variables to pass data from a thread to the next iteration.
17. Reduction clause: Use the reduction clause to perform a reduction operation on private variables.
18. Schedule clause: Use the schedule clause to control the distribution of work among threads.
19. Dynamic schedule: Use a dynamic schedule to dynamically distribute work among threads.
20. Guided schedule: Use a guided schedule to dynamically distribute work among threads with decreasing chunks.
21. Nested parallelism: Use nested parallelism to launch multiple levels of parallelism.
22. Threadprivate variables: Use threadprivate variables to store per-thread data in a nested parallel region.
23. Flush: Use the flush directive to ensure that updates to a shared variable are visible to other threads.
24. Task parallelism: Use task parallelism to decompose a computation into smaller tasks that can be executed in parallel.
25. Tasks with dependencies: Use tasks with dependencies to ensure that certain tasks are executed before others.
26. Taskloop: Use the taskloop construct to distribute a loop-based computation among tasks.
27. Parallel do: Use the parallel do construct to distribute a loop-based computation among threads.
28. Loop collapse: Use the collapse clause to collapse multiple loops into a single parallel loop.