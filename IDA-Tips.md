
### IDA Tips and Tricks
=============================

- get image base address

![image](https://user-images.githubusercontent.com/8508996/155207214-f07d5d89-f9db-4031-9dda-6f37d41f0ea2.png)

another way is by viewing "Program Segmentation"

![image](https://user-images.githubusercontent.com/8508996/155208197-6fae3797-5045-4dfe-8d6e-7beab989c7c8.png)

then double-click to .text segment and it will show the image base!

easy way is with cff explorer

![image](https://user-images.githubusercontent.com/8508996/155208623-2ed7cb84-5133-4d81-aaa9-cb5d32356082.png)


- find the virtual address of entry point of the binary 
Click CTRL+e

![image](https://user-images.githubusercontent.com/8508996/155207363-b49c588a-c500-4d07-b044-b70a029f8b37.png)

- find the entry point address which is the same relative virtual address 
RVA = virtual address of entry point - base address
