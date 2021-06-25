# go-concurrency

**Concurrency Vs Parallelism**

Concurrency is like having a juggler juggle many balls. Regardless of how it seems, the juggler is only catching/throwing one ball per hand at a time. Parallelism is having multiple jugglers juggle balls simultaneously.

Concurrency means that multiple processes or threads are making progress concurrently. While only one thread is executed at a time by the CPU, these threads can be switched in and out as required. This means that no thread is actually completed totally before another is scheduled. So all the threads are executing concurrently.

Parallelism means that multiple processes or threads are making progress in parallel. This means that the threads are executing at the same time. This can happen if all the threads are scheduled on parallel processors.



