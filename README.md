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

###2. ActiveX 无效参数数目，非选择性参数错误
控件内部是根据调用方传来的 ID 区寻找内部的函数的，ID给错了，就调用不到或调用到其他函数里了。
vs2010 通过添加接口，已经全部用 DISP_FUNCTION_ID 格式，
而vc6.0 则是DISP_FUNCTION格式（不加 _ID）
http://www.cnblogs.com/scotth/p/3667192.html

