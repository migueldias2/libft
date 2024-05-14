# Libft (42cursus) 2023-2024

## Actual Status: Finished (125%)

### Functions from `<ctype.h>` Library

- `ft_isascii`: Test for ASCII character.
- `ft_isalnum`: Alphanumeric character test.
- `ft_isalpha`: Alphabetic character test.
- `ft_islower *`: Lower-case character test.
- `ft_isupper *`: Upper-case character test.
- `ft_isdigit`: Decimal-digit character test.
- `ft_isxdigit *`: Hexadecimal-digit character test.
- `ft_isprint`: Printing character test (space character inclusive).
- `ft_isgraph *`: Printing character test (space character exclusive).
- `ft_isspace *`: White-space character test.
- `ft_isblank *`: Space or tab character test.
- `ft_ispunct *`: Punctuation character test.
- `ft_iscntrl *`: Control character test.
- `ft_tolower`: Upper case to lower case letter conversion.
- `ft_toupper`: Lower case to upper case letter conversion.

### Functions from `<stdlib.h>` Library

- `ft_atoi`: Convert ASCII string to integer.
- `ft_atof *`: Convert ASCII string to integer.
- `ft_calloc`: Memory allocation.

### Functions from `<strings.h>` Library

- `ft_bzero`: Write zeroes to a byte string.
- `ft_memset`: Write a byte to a byte string.
- `ft_memchr`: Locate byte in byte string.
- `ft_memcmp`: Compare byte string.
- `ft_memmove`: Copy byte string.
- `ft_memcpy`: Copy memory area.
- `ft_memccpy`: Copy string until character found.

### Functions from `<string.h>` Library

- `ft_strlen`: Find length of string.
- `ft_strlen_2 *`: Find length of 2D array (i.e. splitted string).
- `ft_strchr`: Locate character in string (first occurrence).
- `ft_strrchr`: Locate character in string (last occurrence).
- `ft_strstr *`: Locate a substring in a string.
- `ft_strnstr`: Locate a substring in a string (size-bounded).
- `ft_strcmp *`: Compare strings.
- `ft_strncmp *`: Compare strings (size-bounded).
- `ft_strnrcmp`: Reversely compare strings (size-bounded).
- `ft_strcpy *`: Copy strings.
- `ft_strncpy *`: Copy strings (size-bounded).
- `ft_strdup`: Save a copy of a string (with malloc).
- `ft_strndup *`: Save a copy of a string (with malloc, size-bounded).
- `ft_strcat *`: Concatenate strings (s2 into s1).
- `ft_strncat *`: Concatenate strings (s2 into s1, size-bounded).
- `ft_strlcpy`: Size-bounded string copying.
- `ft_strlcat`: Size-bounded string concatenation.

### Functions from `<math.h>` Library

- `ft_sqrt *`: Square root function.
- `ft_pow *`: Power function.

### Non-standard Functions

- `ft_swap *`: Swap value of two integers.
- `ft_putchar *`: Output a character to stdout.
- `ft_putchar_fd`: Output a character to given file.
- `ft_putstr *`: Output string to stdout.
- `ft_putstr_fd`: Output string to given file.
- `ft_putendl *`: Output string to stdout with newline.
- `ft_putendl_fd`: Output string to given file with newline.
- `ft_putnbr *`: Output integer to stdout.
- `ft_putnbr_fd`: Output integer to given file.
- `ft_itoa`: Convert integer to ASCII string.
- `ft_substr`: Extract substring from string.
- `ft_strtrim`: Trim beginning and end of string with the specified characters.
- `ft_strjoin`: Concatenate two strings into a new string (with malloc).
- `ft_split`: Split string, with specified character as delimiter, into an array of strings.
- `ft_split_free *`: Free splitted string.
- `ft_strmapi`: Create new string from modifying string with specified function.
- `ft_ftoa_rnd`: Convert float to ASCII string.

### Linked List Functions

- `ft_lstnew`: Create new list.
- `ft_lstsize`: Count elements of a list.
- `ft_lstlast`: Find last element of list.
- `ft_lstadd_back`: Add new element at end of list.
- `ft_lstadd_front`: Add new element at beginning of list.
- `ft_lstdelone`: Delete element from list.
- `ft_lstclear`: Delete sequence of elements of list from a starting point.
- `ft_lstiter`: Apply function to content of all list's elements.
- `ft_lstmap`: Apply function to content of all list's elements into new list.

**Note**: Functions marked with * are bonus functions (not mandatory by the project's subject).
**Note2**: My makefile explains everything that is happening with each command :)

