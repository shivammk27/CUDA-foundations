1. In you own language, explain the difference between program, process and thread.
2. Which of the following is NOT a state in the traditional five-state process model? (MCQ) <br>
a. READY <br>
b. RUNNING <br>
c. START <br>
d. BLOCKED <br>
3. In the context of threads, which of the following statements correctly describes the 'Thread Local Storage' (TLS)? (MCQ) <br>
a. TLS allows threads to share variables easily without synchronization. <br>
b.  TLS is used to allocate memory that is global to all threads in a process. <br>
c. TLS provides static or global variables that are unique to each thread. <br>
d. TLS defines a mechanism for recycling thread identifiers in a multithreaded environment. <br>
4. Considering modern operating systems, which of the following best explains the difference between kernel-level threads and user-level threads? (MCQ) <br>
a. Kernel-level threads are managed by the user program, while user-level threads are managed by the operating system kernel. <br>
b. User-level threads can run on different processors simultaneously, whereas kernel-level threads cannot. <br>
c. Kernel-level threads are scheduled by the operating system, whereas user-level threads are managed and scheduled by the application. <br>
d. Kernel-level threads require less overhead than user-level threads because they are lighter and easier to create and destroy. <br>
5. Consider a system with three processes P1, P2, and P3 ready to run. The processes arrive in the order P1, P2, P3 and the arrival times are at 0 ms for all.
The CPU burst times are as follows:
P1: 10 ms
P2: 20 ms
P3: 15 ms
The system is using a Round Robin scheduling algorithm with a time quantum of 5 ms. (MCQ) <br>
a. P1: 15 ms, P2: 50 ms, P3: 45 ms <br>
b. P1: 45 ms, P2: 50 ms, P3: 45 ms <br>
c. P1: 30 ms, P2: 50 ms, P3: 45 ms <br>
d. P1: 25 ms, P2: 55 ms, P3: 50 ms <br>
6. In an operating system, time slicing is used to allocate CPU time among various processes. When a process exceeds its allocated time slice, it is typically preempted and moved to the end of the ready queue. Considering a system with adaptive time slicing, which of the following factors would likely influence the duration of a process's time slice? (MCQ) <br>
a. The priority level of the process, with higher-priority processes receiving longer time slices <br>
b. The amount of time the process has spent waiting in the ready queue, with longer waiting times leading to shorter time slices <br>
c. The I/O behavior of the process, with I/O-bound processes receiving shorter time slices to improve responsiveness <br>
d. The historical CPU burst behavior of the process, with processes that have historically used less CPU time receiving longer time slices to reduce context switching overhead <br>
7. How do hardware threads differ from software threads in terms of execution?
8. Can software threads function without hardware threads?
9. In a multithreaded application, which of the following strategies is NOT typically used to avoid deadlock? (MCQ) <br>
a. Employing a lock hierarchy to impose a global order in which locks must be acquired <br>
b. Using a try-lock mechanism that retries acquiring a lock until it is successful without blocking <br>
c. Allowing a thread to hold only one lock at a time to simplify the lock management <br>
d. Implementing a resource-allocation graph algorithm to detect circular wait conditions <br>
10. In a real-time operating system, a high-priority process H is blocked by a lower-priority process L that holds a needed resource. Process L is preempted by a series of medium-priority processes Mi​, leading to process H experiencing significant delays. Which of the following mechanisms can be used to resolve this type of priority inversion? (MCQ) <br>
a. Priority Donation: Process L temporarily inherits the priority of process H until the resource is released <br>
b. Aging: Process H increases its priority over time until it surpasses the priority of the Mi​ processes <br>
c. Semaphore Queuing: H and L are placed in a semaphore queue with H at the front to ensure it acquires the resource next <br>
d. Elimination of Medium-Priority Processes: Temporarily blocking all Mi​ processes from executing until H has completed <br>
