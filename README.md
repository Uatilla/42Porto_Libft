# 42Porto_Libft
This project is about coding a C library. It will contain a lot of general purpose functions your programs will rely upon.
Libft is a custom library created as a part of the 42 curriculum. It contains a set of useful functions that can be used in various C projects. The purpose of this library is to provide an implementation of standard library functions, as well as additional functions that can be handy in everyday programming tasks.
[![MasterHead](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExODI4MTEwMzllZjE2ODE4OGI1NDM3YTg5MTgxYzYyNzRiOWQyNDI2NCZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/fsXOS3oBboiYf6fSsY/giphy.gif)](https://www.linkedin.com/in/uatilla/)

## Getting Started

You just need to download or clone this git repository.
`git clone git@github.com:Uatilla/42Porto_Libft.git`

The repository contains all functions source code, and the Makefile that can be used to compile.
In the repository's root directory runs on terminal the following codes:

To build the library and link the **Mandatory** files: `make`
To build the library and link the **Bonus** files: `make bonus`

## How to use it

To compile your code you can do: `cc yourmaincode.c libft.a`

To clean the .o files: `make clean`
To clean all .o files and the libft.a: `make fclean`

To clean all .o files, the libft.a and build the library libft.a the Mandatory files .o: `make re`

## Functions

The library provides a wide range of functions that cover various common programming operations, such as:

## Mandatory part

### Memory manipulation

**ft_bzero()**: Writes zeroes to a byte string.

***ft_memcpy()**: Copies n bytes of data from a memory area (the data CAN'T overleap).

***ft_memset()**: Writes a byte to a byte string.

***ft_memmove()**: Copies n bytes of data from a memory area (the data CAN overleap).

***ft_memchr()**: Returns the position in the memory that the first occurrence of a character happened.

**ft_memcmp()**: Compares two memory areas and returns the difference between the first different character.

### String manipulation

***ft_calloc()**: Alocate some memory of size bytes and sets as 0.

***ft_strdup()**: Make some memory with malloc() and duplicates a string to there.

**ft_strncmp()**: Compares two strings and returns the difference between the first different character.

**ft_strlen()**: Measure the size of a string without the NULL character ('\0').

**ft_strlcpy()**: Copy a string src to a dest and guarantee the null terminator, return the size of src.

**ft_strlcat()**: Concatenate a string src to a dest and guarantee the null terminator, return the size of src + dest.

***ft_strchr()**: Returns the position in the memory that the first occurrence of a character happened."

***ft_strrchr()**: Returns the position in the memory that the last occurrence of a character happened."

***ft_strnstr()**: Returns the position of the first occurrence of a string, if it didn't find it returns NULL, if the little string isn't find it returns the big string. 

***ft_substr()**: Returns a pointer to a substring that has size len. 

***ft_strjoin()**: Concatenate two strings and returns a pointer to the new bigger string.

***ft_strtrim()**: Returns a pointer to a new string that has the characters of the set removed from the beginning and the end of the string.

** **ft_split()**: Returns a pointer to an array of strings that are obtained by splitting the string s using the character c as a delimiter.

***ft_strmapi()**: Applies the function f to each character of the string s to create a new string resulting from successive applications of f.

***ft_striteri()**: Applies the function f to each character of the string passed as argument, and passing its index as first argument. Each character is passed by address to f to be modified if necessary.

**ft_putchar_fd()**: Outputs the character c to the given file descriptor.

### Character classification

**ft_isalnum()**: Alphanumeric character test.

**ft_isalpha()**: Alphabetic character test.

**ft_isascii()**: Ascii character test.

**ft_isdigit()**: Decimal digit character test.

**ft_isprint()**: Printing character test (space character inclusive).

**ft_toupper()**: Changes one character to uppercase if it's lowercase else returns the character without changes.

**ft_tolower()**: Changes one character to lowercase if it's uppercase else returns the character without changes.


### String to integer conversion

**ft_atoi()**: Converts the initial portion of the string in int.

### File descriptor output

**ft_putchar_fd()**: Outputs a char to the given file descriptor.

**ft_putstr_fd()**: Outputs the string s to the given file descriptor.

**ft_putendl_fd()**: Outputs the string s to the given file descriptor, followed by a newline.

**ft_putnbr_fd()**: Outputs the integer n to the given file descriptor.

### Integer to string conversion
***ft_itoa()**: Returns a pointer to a new string that represents the integer received as an argument.

## Bonus part

### List creation and modification

***ft_lstnew()**: Allocates (with malloc(3)) and returns a new element.

***ft_lstadd_front()**: Adds the element ’new’ at the beginning of the list.

***ft_lstlast()**: Returns the last element of the list.

***ft_lstadd_back()**: Adds the element ’new’ at the end of the list.

### List deletion and memory management

***ft_lstdelone()**: Takes as a parameter an element and frees the memory

***ft_lstclear()**: Deletes and frees the given element and every successor

### List itaration and mapping

**ft_lstiter()**: Iterates the list ’lst’ and applies the function

***ft_lstsize()**: Counts the number of elements in a list.

***ft_lstmap()**: Iterates the list ’lst’ and applies the function returning a new list

<h1 align="center">Hi 👋, I'm Uatilla Viana Almeida</h1>
<h3 align="center">A brazilian code learner</h3>
<img align="right" alt="Coding" width="400" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExN25yYmwyMmxoMmI0YXBjd2lwb2c3Z2Eybjg2bWZxdXFyd3VnNGE5NCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/qgQUggAC3Pfv687qPC/giphy.gif>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=uatilla&label=Profile%20views&color=0e75b6&style=flat" alt="uatilla" /> </p>

- 🌱 I’m currently learning **C on 42 School of Porto.**

- 📫 How to reach me **uatillaalmeida@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/uatilla/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/uatilla/" height="30" width="40" /></a>
<a href="https://instagram.com/uatillaalmeida" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="uatillaalmeida" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://ifttt.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/ifttt/ifttt-ar21.svg" alt="ifttt" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=uatilla&show_icons=true&locale=en&layout=compact" alt="uatilla" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=uatilla&show_icons=true&locale=en" alt="uatilla" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=uatilla&" alt="uatilla" /></p>


