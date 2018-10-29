# OneDrive_cleanFileNames
Checks directory contents for file name issues that will conflict with MS OneDrive, displaying, and optionally correcting them.

File renaming substitutes illegal characters "*:<>?/\| substituting them with hyphens "-", trims all leading and trailing whitespace, and removes '.' from the end of the filenames.

Install pkg installs the script to /usr/local/bin

Example use: 
`cleanFileNames.py /path/to/directoryToCheck`
