 /-------------------------------------Priority Scheduling Implementation in Pintos----------------------------------------------------------------------/
Insrtuctor :- Rajni AAron

Step :1 Installing and compiling Pintos on qemu simulator
        instruction following from this blog :-https://pintosiiith.wordpress.com/2012/09/13/install-pintos-with-qemu/

Step :2 For changing algorithm of Scheduling we have implemented function for priority scheduling in following files :-
        a) src/devices/timer.c and timer.h
        b) src/threads/sync.c and sync.h and thread.c and thread.h interrupt.c and interrupt.h

Step :3 Implemented sorted doubly link list in this list.c file (src/lib/kernel/list.c)

Step :4 Designed test files in tests folder (path:-test/threads folder)
        For testing test cases for priority and alarm -> first export path using following command export PATH=/home/pintos-project-1-master/src/utils:$PATH
        For test any cases run following command -> pintos run test-case-name (example alarm-multiple,priroity-donate-one etc). 
        For checking extra test case name open test.c file on following location(/src/test/threads/).

Step :5  If you want to add your own test case follow this procedure :-
         first open any file in same location which was in last step and add any function in same way which was written in file itself then write prototype in test.c 
         ,test.h and compile in thread folder using make command.

Step :6 If you want to directly check whether all test cases passed or not Follow it:-
         a)  After compiling change your directory to it (/src/thread/build).
         b)  Run make check command.
         c)  it wil show you status of all test cases one by one.

 /------------------------------------------------------------------End---------------------------------------------------------------------------------------/
