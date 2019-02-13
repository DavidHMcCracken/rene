# rene
Rene is an extended file renamer command line program written in Python for Windows and Linux. Its goal is to be easy to use but powerful. For basic use, the command syntax is as simple as Windows ren and Linux mv yet affords greater flexibility in reusing parts of the original name and formulating its replacement. Features include:

-- Preview of name changes before making them.

-- Automatic name adjustment to avoid existing file names with a choice of parameterized collision avoidance schemas. 

-- Recursion to specified depth, excluding (or including) specified directories.

-- Renaming of files or directories or both.

-- Undo command to restore the original file names changed in the last invocation, including recursion and directory name changes.

-- Command syntax that is simpler but nearly as capable as regular expressions for lexical name selection. 

-- Semantic name selection, for example, of a numeric or alphabetic range, which would otherwise require a program. Regular expressions cannot do this.

-- Fragments of the original name can be discarded or incorporated into the new name completely, by selected parts, or with a numeric or alphabetic bump up or down.

-- Arbitrary numeric and alphabetic sequences can be inserted sequentially into new names.

-- Applies automatic name changes (mainly bump and for collision avoidance) to root rather than to intermediate (e.g. root.tar.gzip) or final extension.

-- Recognizes dotted names, for example .emacs, as root.

-- Simple syntax to specify files with any extension, with no extension, or both.

-- Option to use standard regular expressions instead of rene's native mode.

-- Simple general substitution mode to replace a specific character everywhere or change the case of all letters.

