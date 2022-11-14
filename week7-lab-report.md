# Week 7 Lab Report
**Part 1**

* Changing the name of the `start` parameter and its uses to `base`
* Every key I pressed: `/start<enter>cwbase<esc>n.n.n.:wq` (23 in total)
    * **`/start + <enter>`**: Entering `/<word>+<enter>` in normal mode will look for the string named `<word>` in the file content under the cursor, and the cursor will move to the beginning of the string.
    * **`cw + base + <esc>`**: Typing `cw` in normal mode deletes all characters from the start of the cursor to the end of the entire string and immediately enters insert mode. After that I entered `base` in insert mode and pressed `<esc>` to exit insert mode.
    * **`n`**: Entering `n` in normal mode will repeat the action of the previous search. At this point, the system will look for the next possible string `start` again and move the cursor to the beginning of the string.
    * **`.`**: Typing a period in normal mode will repeat the entire previous text action. At this point, the `.` command will repeat the full behavior of `cw + base + <esc>`.
    * **`n + . + n + .`**: Repeat the first two steps to find the remaining `start` string and change to `base`.
    * **`:wq`**: Typing `:wq` in normal mode will save the file opened by vim and exit vim.