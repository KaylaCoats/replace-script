# replace-script

The [`run-test`](https://github.com/KaylaCoats/replace-script/blob/main/run-test) script has two usages:
- setup - creates test directories and files
- teardown - removes all the test directories and files

Usage: `run-test (setup|teardown)`

The [`replace`](https://github.com/KaylaCoats/replace-script/blob/main/replace) script is used to replace any pattern within the files and directories as well as the contents of the files. You must state where you want the script to begin recursively looking for the pattern, what pattern you want replaced, as well as what you want the pattern replaced by.

Usage: `replace path oldpattern newpattern`

Reminders:
- the path must be a subdirectory to where the replace script is run from
- you must make the files executable 
