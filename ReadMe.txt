This is simple parser program that tries to extract "struct", variables from other *.C  and *.h files  
and puts them in .c and .h files in /tmp location

Compilation: 
-----------
make clean
make


Execution:
----------
e.g: ./main <*.c>
     ./main <*.h>

       (or)

    ./main /opt/linux-4.6.4/

This will create folders and files in /tmp/opt/linux-4.6.4/ with extracted structure variables.
