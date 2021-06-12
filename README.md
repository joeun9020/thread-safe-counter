# thread-safe-counter (project2)

# ubuntu 18.04



#mutex



![Screenshot from 2021-06-13 00-39-09](https://user-images.githubusercontent.com/70720350/121781506-0e6bf100-cbe0-11eb-95b7-226a3dd7b848.png)

#semaphore



![Screenshot from 2021-06-13 00-14-53](https://user-images.githubusercontent.com/70720350/121781516-1c217680-cbe0-11eb-91fe-89907410b0fd.png)

It is about the time complexity difference between mutex and binary semaphore.
When implementing mutual exclusion, semaphore may experience priority inversion.
so semaphore is more suitable for some synchronization problems like producer-consumer.

if you have single instance for resource, it is better to use mutex.
