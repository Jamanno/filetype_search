# filetype_search
Recovery tools like testdisk or scalpel output many directories with sometimes ungrouped files.
For example you re-find openoffice files as .zip.

filetype_search should help to go through recovered files and read their file contents on keywords.

example for lost personal letters:

filetype_search openoffice /home/user/recovered_files/ love 0
Will find out all files and lists them which have the word "love" in their text.
change last number to 1 or 2 will copy or move files. 

filetype_search openoffice /home/user/recovered_files/ love 1
Will copy all files containing love to /home/user/recovered_files/openoffice_love_files/

filetype_search openoffice /home/user/recovered_files/ love 2
Will move all files containing love to /home/user/recovered_files/openoffice_love_files/

