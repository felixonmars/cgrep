Cgrep: Advanced grep for C/C++ source codes
===========================================

Usage
-----

Cgrep 2.1. Usage: cgrep [OPTION] [PATTERN] files...

cgrep [OPTIONS] [ITEM]

Pattern:

    -f --file=FILE      read PATTERNs from file
    -w --word           force word matching
    -G --regex          regex matching
    -i --ignore-case    ignore case distinctions

Context:

    -c --code           grep in C/C++ source code
    -m --comment        grep in comments
    -l --literal        grep in string literals

C/C++ Token:

       --identifier     identifiers
       --keyword        keywords
       --directive      preproc directives
       --header         headers name
       --number         literal numbers
       --string         literal strings
       --char           literal chars
       --oper           operators

Output control:

    -h --no-filename    suppress the file name prefix on output
    -N --no-line-umber  suppress the line number on output lines

General:

    -j --jobs=INT       number of jobs
       --multiline      enable multi-line matching

    -r --recursive      enable recursive search
       --invert-match   select non-matching lines

    -d --debug          debug mode
    -? --help           Display help message
    -V --version        Print version information
