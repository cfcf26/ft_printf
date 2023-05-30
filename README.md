# ft_printf Project

## Introduction

The ft_printf project involves recoding the printf() function in C, with a focus on using a variable number of arguments. It is of moderate difficulty and aims to improve programming skills. Successful completion allows for the addition of ft_printf() to the libft library for use in school C projects.

## Project Objectives

- The project must be written in C.
- The project must be written in accordance with the Norm. If you have bonus files/functions, they are included in the norm check and you will receive a 0 if there is a norm error inside.
- Your functions should not quit unexpectedly (segmentation fault, bus error, double free, etc) apart from undefined behaviors. If this happens, your project will be considered non-functional and will receive a 0 during the evaluation.
- All heap allocated memory space must be properly freed when necessary. No leaks will be tolerated.
- If the subject requires it, you must submit a Makefile which will compile your source files to the required output with the flags -Wall, -Wextra and -Werror, use cc, and your Makefile must not relink.
- Your Makefile must at least contain the rules $(NAME), all, clean, fclean and re.
- Submit your work to your assigned git repository. Only the work in the git repository will be graded.

## Mandatory Part

- Program name: libftprintf.a
- Turn in files: Makefile, *.h, */*.h, *.c, */*.c
- External functions: malloc, free, write, va_start, va_arg, va_copy, va_end
- Libft authorized: Yes
- Description: Write a library that contains ft_printf(), a function that will mimic the original printf()
- The prototype of ft_printf() is: int ft_printf(const char *, ...);
- Your function has to handle the following conversions: cspdiuxX%
- Your function will be compared against the original printf().
- You must use the command ar to create your library. Using the libtool command is forbidden.
- Your libftprintf.a has to be created at the root of your repository.

## Bonus Part

- Manage any combination of the following flags: ’-0.’ and the field minimum width under all conversions.
- Manage all the following flags: ’# +’ (Yes, one of them is a space)
- The bonus part will only be assessed if the mandatory part is PERFECT. Perfect means the mandatory part has been integrally done and works without malfunctioning. If you have not passed ALL the mandatory requirements, your bonus part will not be evaluated at all.

## Submission and Peer-evaluation

Turn in your assignment in your Git repository as usual. Only the work inside your repository will be evaluated during the defense. Don’t hesitate to double check the names of your files to ensure they are correct. Once this assignment passed, you will be allowed to add your ft_printf() to your libft so you can use it in your school C projects.
