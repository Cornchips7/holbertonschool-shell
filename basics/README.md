pwd, print working directory
ls, list contents in directory
cd, change directory to user's home directory
ls -la, list files in long format
ls -la, list all files including hiddien files (starting with .)
mkdir /tmp/my_first_directory, Make my_first_directory directory
mv /tmp/betty /tmp/my_first_directory/, move file to specified location
rm /tmp/my_first_directory/betty, remove file
rm -r /tmp/my_first_directory, Delete my_first_directory that is in /tmp directory
cd -, changes working directory to previous one
ls -la . .. /boot, List all files (including names beginning with a period) in the current and parent working directory and /boot directory (in this order), in long format
file /tmp/iamafile, The type of file
ln -s /bin/ls __ls__, Create symbolic link to /bin/ls, named __ls__
cp -u *.html .., Copies all HTML files from current working directory to parent of the working directory, but only files that did not exist in parent of working directory or were newer that the versions in the parent of working directory.
mv [[:upper:]]* /tmp/u, moves all files beginning with uppercase letter to directory /tmp/u
rm *~, Deletes all files in current working directory that end with the character ~
mkdir -p welcome/to/school, Creates directories welcome/to/school in current directory 
