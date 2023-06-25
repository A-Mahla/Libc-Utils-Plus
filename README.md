#  Libft - Printf, Getline and 50+ Utility Functions

![mybadge](https://badgen.net/badge/SKILLS/%20C,%20LIBC,%20LINKED%20LISTS%20/blue?scale=1.2)

#### Extended Implemented C Library with Printf, Getline and 50+ Utility Functions.

🔧 System Requirements:
   - Operating System: Unix-based OS
   - Software: [make](https://www.gnu.org/software/make/), [gcc](https://gcc.gnu.org/)

## Usage
 
To run the command, open your terminal and follow these steps:

  - To create ```libft.a```:
  
      ```shell
      (cd /path/to/project/directory && make)
      ```

   - To compile with ```libft.a```:
  
      ```shell
      (cd /path/to/project/directory && make)
      gcc -o a.out *.o -I </path/to/project/directory>/libft/includes -L /path/to/project/directory -lft
      ```

## Functions
### ft_printf :

   ```C
   # include "ft_printf.h"
   ```

   - [ft_printf](libft/ft_printf/ft_printf.c#L112) - ```int	ft_printf(const char *format, ...);```

      Types conversions :
        -  [%c](libft/ft_printf/ft_print_str_char.c#L22) print a single character.
        -  [%s](libft/ft_printf/ft_print_str_char.c#L76) print a string of characters.
        -  [%p](libft/ft_printf/ft_print_ptr_pct.c#L44) The void * pointer argument is printed in hexadecimal
        -  [%d](libft/ft_printf/ft_print_int.c#L70) print a decimal (base 10) number.
        -  [%i](libft/ft_printf/ft_print_int.c#L70) print an integer in base 10.
        -  [%u](libft/ft_printf/ft_print_uint.c#L41) print an unsigned decimal (base 10) number.
        -  [%x](libft/ft_printf/ft_print_hex.c#L67) print a number in lowercase hexadecimal (base 16).
        -  [%X](libft/ft_printf/ft_print_hex.c#L67) print a number in uppercase hexadecimal (base 16).
        -  [%%](libft/ft_printf/ft_print_ptr_pct.c#L68) print a percent sign.

      Flag directives (use them between '%' character and the type conversion):
        - ['-'](https://learn.microsoft.com/en-us/cpp/c-runtime-library/format-specification-syntax-printf-and-wprintf-functions?view=msvc-170#flags) left align the result within the given field width.
        - ['+'](https://learn.microsoft.com/en-us/cpp/c-runtime-library/format-specification-syntax-printf-and-wprintf-functions?view=msvc-170#flags) use a sign (+ or -) to prefix the output value if it's of a signed type.
        - ['#'](https://learn.microsoft.com/en-us/cpp/c-runtime-library/format-specification-syntax-printf-and-wprintf-functions?view=msvc-170#flags) When it's used with the o, x, or X format, the # flag uses 0, 0x, or 0X, respectively.
        - ['0'](https://learn.microsoft.com/en-us/cpp/c-runtime-library/format-specification-syntax-printf-and-wprintf-functions?view=msvc-170#flags) If width is prefixed by 0, leading zeros are added until the minimum width is reached.
        - [blank (' ')](https://learn.microsoft.com/en-us/cpp/c-runtime-library/format-specification-syntax-printf-and-wprintf-functions?view=msvc-170#flags) use a blank to prefix the output value if it's signed and positive.
        - ['.'](https://learn.microsoft.com/en-us/cpp/c-runtime-library/format-specification-syntax-printf-and-wprintf-functions?view=msvc-170#precision) the precision specification
        - ['\<number\>'](https://learn.microsoft.com/en-us/cpp/c-runtime-library/format-specification-syntax-printf-and-wprintf-functions?view=msvc-170#width) the width specification field.

   
### ft_getline :

   ```C
   # include "ft_getline.h"
   ```

   - [ft_getline](libft/ft_getline/ft_getline.c#L15) - ```char	*ft_getline(int fd);```

### Libc :
