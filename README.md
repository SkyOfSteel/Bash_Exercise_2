# Bash_Exercise_2
More exercises in basic Bash scripting based on the scenarios from [w3resource](https://www.w3resource.com/bash-script-exercises/understanding-basic-commands.php).

## 1. Echo Command Basics

Write a Bash script that uses the echo command to print "Hello, World!" to the terminal.

<details>

```
#!/bin/bash
echo Hello, World!
```
![image](https://github.com/user-attachments/assets/d81cde63-a420-422c-b85b-3b3bfedf3801)

**Things to remember**: 
- Backslash to escape special characters if I want to preserve double quotations on the screen output: echo \"Hello, World!\";
- Single quotes are also possible, but a single quote within single quotes cannot be escaped: \'It\'s a me!\';
- Quotes are not necessary for simple text. Text within double quotes ignores some special symbols, while text within single quotes ignores all special symbols.
  
</details>

## 2. Echo With Variables

Write a bash script that takes a user's name as input and uses the echo command to greet the user with "Hello, [name]!".

<details>
  
```
#!/bin/bash
echo Hello, what\'s your name?
read name
echo Hello, $name
```
![image](https://github.com/user-attachments/assets/46306215-acf1-4a32-9a9e-e4a62703eca4)

**Things to remember**: 
- Either put a backslash before the single quotation mark to escape it, or put the entire phrase into double quotations;
- A single quote may not occur between single quotes, even when preceded by a backslash.

</details>

## 3. Cat Command Usage

Write a Bash script that uses the cat command to display the contents of a text file named "exec_stdout.txt".

<details>

```
#!/bin/bash
cat exec_stdout.txt
```
![image](https://github.com/user-attachments/assets/ab20df64-ae8c-48bb-952c-19f52956414e)


</details>

## 4. Listing Files

Write a Bash script that uses the ls command to list all files and directories in the current directory.

<details>

```
#!/bin/bash
ls -asl
```
![image](https://github.com/user-attachments/assets/f9881361-9e9a-4db3-8ca0-ebaa99f2d57a)


**Things to remember**: 
- **a** to list all files, **s** to list the size, **l** to use the long-listing format.
  
</details>
