# Week 5 Lab Report
1. **`less`**\
![Image](pic/LR4/less.png)\
\
This is the result of the standard `less <<file-path>>` command, which displays the file contents.

    * `-N`
    ![Image](pic/LR4/less-N.png)\
    \
    The `less -N <<file-path>>` command shows the line numbers of the lines in the file.

    * `-X`
    ![Image](pic/LR4/less-X.png)\
    \
    The `less -X <<file-path>>` command leaves the contents of the file in Terminal which should be clear on exit.

    * `-M`
    ![Image](pic/LR4/less-M.png)\
    \
    The `less -M <<file-path>>` command adds a percentage to the last line of the command line to indicate that what is currently displayed is where the entire content is.

2. **`find`**\
![Image](pic/LR4/find.png)\
\
This is the result of the standard `find <<directory-path>>` command, which searches in a directory for files and lists.

    * `-name`
    ![Image](pic/LR4/find-name.png)\
    \
    The `find <<directory>> -name "pattern"` command returns all filenames in the directory that contain "pattern". It will be very convenient for us to find files of a certain file pattern.

    * `-ls`
    ![Image](pic/LR4/find-ls.png)\
    \
    The `find <<directory>> -ls` command outputs all file attributes in the directory in ls-dils format. It is useful when we need to see file properties.

    * `>`
    ![Image](pic/LR4/find-d.png)\
    \
    This `find <<directory>> > <<file-path>>`  command will import everything returned by the find command into a new file <<file-path>>. After that, we can do more processing on the file.

3. **`grep`**\

    * `-v`
    ![Image](pic/LR4/grep-v.png)\
    \
    The `grep -v` command will return lines that do not match the input. It will work when we need to filter lines.

    * `-c`
    ![Image](pic/LR4/grep-c.png)\
    \
    The `grep -c` command will count the number of lines in the file that match the input. It will work when we need to know how many lines fit the input.

    * `grep -m num`
    ![Image](pic/LR4/grep-mn.png)\
    \
    This `grep -m NUM` command will output only the first NUM lines matching the input. It will work when we only need a certain number of matching outputs.

