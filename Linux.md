# Linux Operating System

Linux refers to a family of free operating system based on the Linux Kernel. Kernal is the core component of a computer operating system.

GNU/Linux

Commands:

        ```
        $ rm <filename> --> rm deletes the files/ folders permenently
        $ rm -rf <folder>
        $ history
        $ ls
        $ ls -a; ls -l; ls -al
        $ cd ~/path/
        $ ~/.bash_history --> history of commands used in the terminal
        $ ls | grep --> use the pipe character (|) to pipe the output from the ls command to the grep command
        $ ls > list --> create new or replace completely 
        $ ls >> list --> creates new or append
        $ rm  "Joe's 'Term paper'" 
        $ rm Joe's\ Term papers
        ```

Piping allows you to take the output from one command and move it to a second command for processing.

Linux terminal is case sensitive

## File system

A “filesystem” refers to how the information stored on a disk is organized, whether on a hard disk, a USB flash drive, or an optical disk like a CD-ROM or a DVD-ROM.

Note: In the Linux filesystem, various hardware devices are also represented as files, all stored in the /dev directory.

        ```
        $ tree
        $ pwd --> present workind directory path
        ```
/bin: System Binaries
/dev: hardware devices on the system
/etc: Configuration files for sevices and programs that run on Linux
/home: Home folder for all users on the system
/media and /mnt: Store removeable media
/root: contians home folder of the root user
/sbin: Holds system commands but only root directory can use it
/tmp: temporary files
/usr: multi-user application
/var: stores data that changes during the operation of the system

Note: Relative Path vs Absolute Path(full path) Remember that you can use relative file paths if the file or directory you intend to work with is in your current working directory. If not, you should use the absolute file path.
