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

   - [ft_printf](src/ft_printf/ft_printf.c) - ```int	ft_printf(const char *format, ...)```

      flags:
        -  %c print a single character.
        -  %s print a string of characters.
        -  %p The void * pointer argument is printed in hexadecimal
        -  %d print a decimal (base 10) number.
        -  %i print an integer in base 10.
        -  %u print an unsigned decimal (base 10) number.
        -  %x print a number in hexadecimal (base 16).
        -  %% print a percent sign.
