
# SINGLE THREADED VS MULTI THREADED

Thread means flow of instruction of executioning the apps.


Single-threaded means one command is processess at a time.
And multi-threaded means processess a multiple part of program
at the same time .

Multi thread also depend on the core of the cpu , how many computer 
, here some example : 

#### Single-thread:

- Execute task 1
- Execute task 2
- Execute task 3
- Execute task 4
- Execute task 5
- Execute task 6
- Execute task 7
- Execute task 8
- Execute task 9

#### Multi-threaded:

Thread1:

- Execute task 1
- Execute task 2
- Execute task 3
Thread2:

- Execute task 4
- Execute task 5
- Execute task 6
Thread3:

- Execute task 7
- Execute task 8
- Execute task 9

#### Assuming if this example using single-core , usually nowday computer using mutilple core 

- CPU : 1 & No blocking => Single-threaded will finish equal or faster than multithreaded ( this because no switching thread)
- CPU : 1 & There a a blocking => Multi-threaded is faster , assuming work the blocking help multi-threaded split the loading at same time
- CPU : more than 1 => Logicly multi-threaded is faster 

