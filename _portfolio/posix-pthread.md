---
title: "POSIX Pthread Library with Multi-level Feedback CPU Scheduler"
excerpt: "[![star this repo](http://githubbadges.com/star.svg?user=saurabh-deochake&repo=POSIX-Pthread-Scheduler)](https://github.com/saurabh-deochake/POSIX-Pthread-Scheduler)[![fork this repo](http://githubbadges.com/fork.svg?user=saurabh-deochake&repo=POSIX-Pthread-Scheduler)](https://github.com/saurabh-deochake/POSIX-Pthread-Scheduler/fork) <br/>
This project is a library named `my_pthread_t.h` that contains implementations of all the primitive functions of original pthread library.
<br/>Built using: C"
collection: portfolio
---

[![star this repo](http://githubbadges.com/star.svg?user=saurabh-deochake&repo=POSIX-Pthread-Scheduler)](https://github.com/saurabh-deochake/POSIX-Pthread-Scheduler)
[![fork this repo](http://githubbadges.com/fork.svg?user=saurabh-deochake&repo=POSIX-Pthread-Scheduler)](https://github.com/saurabh-deochake/POSIX-Pthread-Scheduler/fork)

Description: 
This project is a library named "my_pthread_t.h" that contains implementations of all the primitive functions of original pthread library and lightweight pthread mutex, mutual exclusion devices that keep a thread locked if it is waiting for a particular mutex. 
This project built a Multi-level feedback queue scheduler to schedule the threads. When a thread runs for its entire time 
slice without terminating, its priority is decreased. As threads decrease in priority they run less often, but for longer. 
We used ucontext to swap out/in the context of threading running or waiting for execution in the wait queue.

Built using: C
