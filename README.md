# 42-ft_printf

The aim of this projetc was to recreate the function printf using C language (stdio library)

To execute this program, just type **make** in your terminal  
To delete the objects and the executable file, type **make fclean**   


This implementation cover the following set of flags, length modifiers and conversions, besides the availability of the width and precision modifiers:

**Flags**
| Flag |                             Description                            |
|:----:|:-------------------------------------------------------------------|
| -    | Align replaced text to the left when enough width is given         |
| 0    | Add '0' as a padding character in numeric conversions              |

**Conversions**
| Flag |                             Description                            |
|:----:|:-------------------------------------------------------------------|
| -    | Align replaced text to the left when enough width is given         |
| 0    | Add '0' as a padding character in numeric conversions              |
| +    | Add a plus sign ('+') in the front of positive numeric conversions |
| #    | Alternate input method for placeholder                             |
