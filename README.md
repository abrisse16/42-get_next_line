<div align=center>

# <b>Get Next Line</b>

### 42 Common Core / circle #1
<i>May it be a file, stdin, or even later a network connection, you will always need a way to read content line by line.
<br>This project is about programming a function that returns a line
read from a file descriptor and learn about static variables.</i>

##

### Final grade
[![abrisse's 42 get_next_line Score](https://badge.nimon.fr/api/v2/clw51aj8x026501rzp5ef4x2f/project/2439557)](https://github.com/Nimon77/badge42)

### Subject
English version [here](https://github.com/abrisse16/42-subjects/blob/7385a594afd19b06ab40ed62b5e8c818d2d8bd21/get_next_line-subject-v10.en.pdf)
<br>
French version [here](https://github.com/abrisse16/42-subjects/blob/7385a594afd19b06ab40ed62b5e8c818d2d8bd21/get_next_line-subject-v10.fr.pdf)

</div>

---

## The project

In this project, I had to code a function that returns a line ending with a newline, read from a file descriptor.

Calling the function `get_next_line` in a loop will then allow you to read the text available on a file descriptor one line at a time until the EOF. It behave well when it reads from a file, from the standard output, from a redirection etc.

In the <b>bonus</b> version, `get_next_line` is able to handle multiple file descriptors opened simultaneously.

## Usage

Clone this repository :

```sh
git clone https://github.com/abrisse16/42-libft.git path/to/repository
```

When compiling <i>get_next_line</i>, be sure to include the following flag in your compilation command :

```sh
-D BUFFER_SIZE=xx
```

Where `xx` is the buffer size you wish to use when reading from a file descriptor.

---
<div align=center>
	<a href="mailto:abrisse@student.42.fr">abrisse@student.42.fr</a>
</div>