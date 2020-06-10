
`\[` - start of non-printing sequence
`\]` - end of non-printing sequence

# Common Special Characters

`\d` - the current date
`\e` - escape character
`\h` - the hostname
`\n` - a newline
`\t` - current time 24-hour HH:MM:SS
`\T` - 12-hour HH:MM:SS
`\@` - 12-hour HH:MM am/pm
`\u` - username of current user
`\w` - path to current working directory

# Colors!

Black: `\e[30m`
Blue:  `\e[34m`
Cyan:  `\e[36m`
Green:  `\e[32m`
Magenta:  `\e[35m`
Red:  `\e[31m`
White:  `\e[37m`
Yellow:  `\e[33m`

Black: `\033[30m`
Blue:  `\033[34m`
Cyan:  `\033[36m`
Green:  `\033[32m`
Magenta:  `\033[35m`
Red:  `\033[31m`
White:  `\033[37m`
Yellow:  `\033[33m`

To reset the color, use `\e[00m`

# my prompt as example

PS1="[\u@\h \w]$ " 

PS1="\`if [ \$? = 0 ]; then echo \[\e[33m\]^_^\[\e[0m\]; else echo \[\e[31m\]O_O\[\e[0m\]; fi\`[\u@\h \w]\\$ "


