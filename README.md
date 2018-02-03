# cache
An implementation of a cache with C. Takes a text file of addresses and generate tag, set, and offset for each address according the the framework user has set for cache.

Compile with: gcc -std=c99 -o cache cache.c -lm '\n'
Execute with: ./cache 'cache-size' 'associativity' 'size-of-block' address.txt

