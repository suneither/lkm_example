**About**

This repository is for pure learning purpose, it is nothing more than 
an introduction to LKM - Linux Kernel Module, that will lead 
to the world of device drivers.

Everything it does is prints classic `Hello, World!` on module load and not 
so classic `Goodbye, World!` on module unload. 

---

**Project files**
- lkm_example.c - contains all loading/unloading logic
- Makefile - contains 3 commands: 
  - `all` to compile build files
    ```
    // run 
    make
    // or 
    make all
    ```
  - `clean` to remove all compiled files
    ```
    // run 
    make clean
    ```
  - `test` to run all necessary commands to test if it build correctly
    ```
    // run
    make test
    ```
    
