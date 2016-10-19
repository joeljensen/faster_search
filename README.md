## Fast recursive search

I use this script to search across multiple repositories for strings while doing ansible work. Grep is too slow when dealing with really large codebases. I needed something indexed.

This repository contains a script to search all files recursivly from your starting position.

Usage: search [terms ...] or pass term in from STDIN

Searches the current directory and subdirectories for the terms, using mdfind,
then opens the results in your editor. mdfind is much faster than grep for looking through large codebases.
The term you searched for is copied to the system clipboard as well, for easy navigation within the document

To use

 * Clone this repository
 * Place in a directory which is on your path.
 * in terminal ''' search [term ...]'''