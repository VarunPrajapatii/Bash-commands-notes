ls => command - gives list of files and folders the directory contain.
pwd => command - gives present working directory
ls -l => command - details of files and folders of the directory
ls -R     and then dir name - command - to look at what are the things that are present in each of the subdirectories
ls -t     and then dir name - command - to get list of directories and understand what was the last modified first
ls -lt => command - combine l and t command
ls -la => gives the hidden files too
ls -s => gives size of the subfolders and folders present


Nowe to find certine kind of files in the directory structure
lets say you want all the .js files in the particular directory,

ls -lR | grep .js => we are recursively looking at all the directories and the subdirectories
ls *.js => to get all the js files in the directory level
ls .. => gives list of directories present in the parent folder
ls Var* => gives all the thing containing Var in their name


cd => change directory
cd .. => to go back to the previous directory


cat => command to display the content of the file it can be used to concatenate data
touch    then file name => it creates a new file
cat >    then file name => it adds the data in file
cat >>    then file name => it appends the data
mkdir    then file name => it creates a new directory
mkdir -p    then dir name => it recursively creates directory



