# 42 Common Core / Libft
This project is about coding a C library that contains a lot of general purpose functions to be used throughout the course.
###
Most of these funcions already exist on standard C libraries and so this project is about understanding the way these functions work, implementing and learning to use them. 
To add another layer of difficulty the only external functions allowed are: write(), malloc() and free(). 
### String manipulation
- `ft_isalpha` - checks for an alphabetic character.
- `ft_isdigit` - checks for a digit (0 through 9).
- `ft_isalnum` - checks for an alphanumeric character.
- `ft_isascii` - checks whether a giver char is representable as ASCII character.
- `ft_isprint` - checks for any printable character.
- `ft_toupper` - convert char to uppercase.
- `ft_tolower` - convert char to lowercase.
- `ft_strlen` - calculate the length of a string.
- `ft_strlcpy` - copy string to a specific size.
- `ft_strlcat` - concatenate string to a specific size.
- `ft_strchr`	- locate first char occurence in string from the beginning.
- `ft_strrchr` - locate first char occurence in string from the end.
- `ft_strncmp` - compare two strings.
- `ft_strnstr` - locate a substring in a string.
- `ft_strdup` - creates a duplicate for the string passed as parameter.
- `ft_atoi` - convert a string to an integer.
- `ft_substr` - returns a substring from a string.
- `ft_strjoin` - concatenates two strings.
- `ft_strtrim` - trims the beginning and end of string with specific set of chars.
- `ft_split` - splits a string using a char as parameter.
- `ft_itoa` - converts a number into a string.
- `ft_strmapi` - applies a function to each character of a string.
- `ft_striteri` - applies a function to each character of a string.
###
### Memory manipulation
- `ft_memset` - fill memory with a constant byte.
- `ft_bzero` - zero a byte string.
- `ft_memcpy`	- copy memory area.
- `ft_memmove` - copy memory area.
- `ft_memchr` - scan memory for a character.
- `ft_memcmp`	- compare memory areas.
- `ft_calloc` - allocates memory and sets its byte values to 0.
###
### Linked list manipulation
- `ft_lstnew`	- creates a new list element.
- `ft_lstadd_front`	- adds an element at the beginning of a list.
- `ft_lstsize` - counts the number of elements in a list.
- `ft_lstlast` - returns the last element of the list.
- `ft_lstadd_back` - adds an element at the end of a list.
- `ft_lstclear` - deletes and frees the list.
- `ft_lstiter` - applies a function to each element of a list.
- `ft_lstmap`	- applies a function to each element of a list.
###
### Outputs to file descriptor
- `ft_putchar_fd` - output a char to a file descriptor.
- `ft_putstr_fd`	- output a string to a file descriptor.
- `ft_putendl_fd` - output a string to a file descriptor, followed by a new line.
- `ft_putnbr_fd`	- output a number to a file descriptor.
