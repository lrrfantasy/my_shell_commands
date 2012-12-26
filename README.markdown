#My Shell Commands

These are all shell commands I write for daily use, or maybe not :)

Run `bash install` in the directory to set the PATH

##random

Generating a random number using $RANDOM.

`random`: generate a random number between 0 and 32767

`random <number>`: generate a random number between 0 and number

##ce

Colourised echo output.

`ce`: Usage

`ce -r|--red <message>`: Output red message

`ce -g|--green <message>`: Output green message

`ce -y|--yellow <message>`: Output yellow message

`ce -b|--blue <message>`: Output blue message

`ce -m|--magenta <message>`: Output magenta message

`ce -c|--cyan <message>`: Output cyan message

##dict

Look up word in dictionary. Only works in Mac OS X.

`dict <word>`: Look up word in dictionary

##difference

Diff tool using git diff when available otherwise default diff.

This can replace default diff

`difference <file_1> <file_2>`: Diff two files

##whichen

Enhanced which, searching alias as well.

This can replace default which.

`whichen <command>`: Search command location or alias

##rtncd

Short for "return code", display return code for a command. Use this command carefully.

`rtncd <command>`: Display a return code for a command, doesn't display the command's output

`rtncd -v <command>`: Display a return code for a command, also display the command's output

##wf

Calculate word frequency from stdin.

`wf [n]`: Display the first n lines of top frequent words. By default n is 25.
