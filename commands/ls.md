# ls 

The `ls` command lists files and folders of a directory

## command:

```Shell
$ ls
````

## options:

Option | Description
------ | ---------------------------------------------------------------------------
-a     | List all files. As well hidden ones (e.g. .gitignore)
-A     | Like above but does not list current (.) and parent (..) directory
-d     | use this option with -l (e.g. -ld) to see details about the directory
-F     | This option appends an indicator character at the end of entries (e.g. "/")
-h     | with option -l will display sizes in human readable format
-l     | displays contents in long format
-r     | displays in reverse order. Default is in alphabetically order
-S     | sort by file size
-t     | sort by modification time

## examples:
```Shell
$ ls -lh
```
Shows the long lists with human readable format of the file size
