PROBLEM STATEMENT

Use gdb to read assembly code for C program to find factorial of a number with recursion and demonstrate how parameters are passed using pass by value.


ASSIGNMENT 3 README- INSTRUCTIONS


1.Run the command on Terminal (In Linux) or Cygwin (in Windows) 
(Open them in same location where .c files are stored)
            gcc filename.c -fdump-tree-cfg-graph     or 
            gcc filename.c -fdump-tree-all-graph
            
-- a.exe, cfg and cfg.dot files are created
cfg, and code of cfg.dot file can be seen by opening them by double clicking them or use vi or vim.

2.To view Parse Tree generated from cfg.dot file –
#Graphviz

a.In Linux
sudo apt-get install graphviz
dot -Tpng filename.c.011t.cfg.dot -o filename.png
