# Philiosophers
 is a project designed to simulate the classic dining philosophers problem, a well-known synchronization challenge that demonstrates the difficulties of avoiding deadlock and starvation in a multi-threaded environment.

The problem is set up as follows:

- Five philosophers sit around a circular table, each with a plate of spaghetti.
- There are five forks on the table, one placed between each philosopher.
- To eat, a philosopher must pick up two forks: one from the left and one from the right.
After eating, the philosopher will sleep for a random amount of time.
- Upon waking, the philosopher will think for a random amount of time.
- The goal is to ensure that no philosopher starves and that deadlock is avoided.

The mandatory part of the project requires simulating this problem with the following constraints:

- Each philosopher is represented as a thread.
- Each fork is represented as a mutex.
- Philosophers must be able to eat, sleep, and think without causing deadlock or starvation.

The project is implemented in C, using the pthread library for threading in the mandatory part and employing processes and forks.
