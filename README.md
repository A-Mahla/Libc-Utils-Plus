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
### Printf

   - [ft_printf](libft/ft_printf/ft_printf.c#L112) - ```int	ft_printf(const char *format, ...)```

      flags:
        -  [%c](libft/ft_printf/ft_print_str_char.c#L22) print a single character.
        -  [%s](libft/ft_printf/ft_print_str_char.c#L76) print a string of characters.
        -  [%p](libft/ft_printf/ft_print_prt_pct.c#L44) The void * pointer argument is printed in hexadecimal
        -  [%d](libft/ft_printf/ft_print_int.c#L70) print a decimal (base 10) number.
        -  [%i](libft/ft_printf/ft_print_int.c#L70) print an integer in base 10.
        -  [%u](libft/ft_printf/ft_print_uint.c#L70) print an unsigned decimal (base 10) number.
        -  [%x](libft/ft_printf/ft_print_hex.c#L67) print a number in lowercase hexadecimal (base 16).
        -  [%X](libft/ft_printf/ft_print_hex.c#L67) print a number in uppercase hexadecimal (base 16).
        -  [%%](libft/ft_printf/ft_print_prt_pct.c#L68) print a percent sign.
