jrename
=======

A simple command line script to quickly sort/rename a collection of files into a standard *filename_0000.ext* convention. Useful for files that belong to a series, such as photos.

# Usage
__jrename__ _{options}_ _{files}_

# Command line options

* _-a_ - Automated. Will attempt to preserve the original base filename and only change the file counter, if one exists. Useful for closing gaps. For example, file_0001.ext, file_0003.ext would become file_0001.ext and file_0002.ext.
* _-n_ - New base filename
* _-d_ - Destination directory, if not the current one

# Why another renaming script?

This is a case of me scratching my own itch. I simply couldn't find a rename app or script to do what I wanted it to do. I didn't need the extra bells and whistles. I just wanted something to keep my archived files tidied up and I wanted to be able to run it quickly from the command line. This is the result. (Actually, it was originally a bash script, but that's another story for another time).

