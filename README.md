# AOS1_20CS10027_20CS10028

This repository contains code for the AOS1 (Advanced Operating Systems 1) project by 20CS10027 and 20CS10028.

## Instructions for Running the Code

To compile and run the code, follow these steps:

1. Open a terminal.

2. Navigate to the project directory.

3. Run the `make` command to build the necessary files:

   ```bash
   make
   ```

   Make sure you are using the correct test file name.

4. Switch to the superuser mode using `sudo`:

   ```bash
   sudo su
   ```

   You will be prompted to enter your password.

5. Load the kernel module using `insmod`:

   ```bash
   insmod ./partb_1_20CS10027_20CS10028.ko
   ```

6. Run the executable file:

   ```bash
   ./f1
   ```

7. After testing, remove the kernel module using `rmmod`:

   ```bash
   rmmod partb_1_20CS10027_20CS10028
   ```

8. Exit the superuser mode:

   ```bash
   exit
   ```

9. Repeat the above steps for testing all the test cases.

Make sure to replace `partb_1_20CS10027_20CS10028.ko` with the correct kernel module file and `f1` with the appropriate test file name when necessary.

```
