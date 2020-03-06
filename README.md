# ft_printf
Regardless of the programming language considered, the printf function,(or its equivalents) is always highly useful. The main reason is the ease of its formatting, and the support of diverse types in variable numbers. Some variations even propose to be able to write the resulting string of characters either in a file descriptor or in a particular stream. Some also propose to recall this string without printing it. In short, undeniably, printf is a vital function.

- You have to recode the libc’s printf function.
- Your function will be called ft_printf and will be prototyped similarly to printf.
- You won’t do the buffer management in the printf function. 
- You have to manage the following conversions: csp 
- You have to manage the following conversions: diouxX with the following flags: hh, h, l and ll. 
- You have to manage the following conversion: f with the following flags: l and L. 
- You must manage %% 
- You must manage the flags #0-+ and space 
- You must manage the minimum field-width 
- You must manage the precision
