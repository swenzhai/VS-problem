# VS-problem
Include the problem when I use visual studio to build my project.

##Problems
###1.VS包含目录问题
To add more than one directory, use this option more than once. Directories are searched only until the specified include file is found.
You can use this option with the Ignore Standard Include Paths (/X (Ignore Standard Include Paths)) option.
The compiler searches for directories in the following order:
Directories containing the source file.
Directories specified with the /I option, in the order that CL encounters them.
Directories specified in the INCLUDE environment variable.
