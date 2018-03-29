
ls command is used to list files and directories. By default, it will be list the content of current directory.
```bash
-------------------------------------------------------------------------------------------------------------------------
|  № | short |  long           |                       Description                                                       |
|----|-------|-----------------|-----------------------------------------------------------------------------------------|
|1   |-A     |-all             |  Show all (hidden) files without "." amd ".."                                           
|2   |-l     |        -        |  show list (row and column)                                                             
|3   |-h     |--human-readable |  show norman mb or kb ... size                                                          
|4   |-si    |        -        |  This parameter is similar with -h parameter, but --si powers 1000 while -h powers 1024 
|5   |-S     |        -        |  will be sort by the largest file size first                                            
|6   |   -   |--block-size=M   |  Ls can scale size by before printing K = Kilobyte M = Megabyte G = Gigabyte T = Terabyte P = Petabyte E = Exabyte Z = Zettabyte Y = Yottabyte
|7   |-d */  |--directory */   |  List directory entries only                                               
|8   |-g     |        -        |  show information group                                               
|9   |-G     |--no-group       |  show information owner                                               
|10  |-n     |--numeric-uid-gid|  If we want to know the UID and GID of owner and group owner 	                                              
|11  |-i     |--inode          |  To print the index number or known as inode numbe                                               
|12  |-r     |--reverse        |  reverse order while sorting                                               
|13  |-R     |--recursive      |  list subdirectories recursively                                               
|14  |-X     |--sort=extension |  sort the list by extension                                               
|15  |-t     |       -         |  sort the list by the modification time                                               
```
