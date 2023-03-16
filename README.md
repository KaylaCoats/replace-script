# replace-script

The run-test script has two usages:
	setup - creates test directories and files
	teardown - removes all the test directories and files
Usage: run-test (setup|teardown)

The replace script is used to replace any pattern within the files and directories as well as the contents of the files.
You must state where you want the script to begin recursively looking for the pattern, what new pattern you want to replace the old one, as well as what the old pattern was.
Usage: replace path oldpattern newpattern
