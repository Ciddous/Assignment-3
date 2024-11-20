# Assignment-3
# How to Compile and Run the Code
To compile and run the code, it is recommended to use a virtual machine with `gcc` installed. If you don’t already have a server setup, please contact your instructor for access. Follow these steps to transfer, compile, and run the code on your server.

# Step 1: Setting Up Your Environment
1. Accessing the server
   * Use PuTTY or any terminal to connect to your server
2. Transferring Files
   * Ensure that producer_consumer.c and mytest.dat are in the proper directory
   * Then transfer the files using the following commnad
   * pscp [local_file_path] [username]@[hostname]:[remote_directory]
       * Replace [local_file_path] with the path to the files
       * Replace [username] with server username
       * Replace [hostname] with server IP
       * Replace [remote_directory] with the directory path
3. Navigate to files
   * Use the following command
       * cd /home/user/project

# Step 2: Compile the Code
* use the gcc compiler to compile the program
    gcc producer-consumer.c -o producer-consumer
* Then ensure there are no errors

# Step 3: Run the Program
* Run the program using the following command
    ./producer_consumer
* Expected output of the program is that the characters from mytest.dat will be print to the console a 1 second delay
