# get_next_line
char	*get_next_line(int fd); \
A function that returns the next line from a file \
Takes in a filedescriptor, which can be created by using open()

## functions used
malloc(); \
read(); \
free();

## lessons learned
using minimal lines to create something working \
Max allowed: 2 c files, 5 functions per file, 25 lines per function \
working with static char * \
Logic for handling the current read() and the saved buffer
