#My Shell Commands

These are all shell commands I write for daily use, or maybe not :)

Run `bash install` in the directory to set the PATH

##random

Generating a random number using $RANDOM.

`random`: generate a random number between 0 and 32767

`random {number}`: generate a random number between 0 and {number}

##init

Initialising a file from the template

Shell: "#!/bin/sh" header and executable status on

HTML: basic structure and jQuery/reset.css reference

Git: git repository with the first commit

`init ignore {template}`: initialise .gitignore with a template

`init sh|shell {file}`: initialise a Shell script

`init html {file}`: initialise an HTML file

`init git [{message}]`: initialise a git repository and make the first commit

`init [usage]`: display usage

##ce

Colourised echo output

`ce`: Usage

`ce -r|--red {message}`: Output red message

`ce -g|--green {message}`: Output green message

`ce -y|--yellow {message}`: Output yellow message

`ce -b|--blue {message}`: Output blue message

`ce -m|--magenta {message}`: Output magenta message

`ce -c|--cyan {message}`: Output cyan message

##dict

Look up word in dictionary

`dict {word}`: Look up word in dictionary

##difference

Diff tool using git diff when available otherwise default diff

`difference {file_1} {file_2}`: Diff two files

##whichen

Enhanced which, searching alias as well

`whichen {command}`: Search command location or alias
