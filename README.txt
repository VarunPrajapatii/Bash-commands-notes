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



mv   then file name  then new file name => it renames the file
mv   then file name  then the dir add => it moves the file in that directory
cp   then file name  then the folder or dir => it copies the file there
cp -r  then dir name and then dir address => copies the folder in the destination
rm   then file name => it removes the file
rm -r   then dir name => it removes the folder


chmod: Change file permissions, Modify the read, write and execute permissions of a file
You have to search the web or see that lecture for this section

pipe | character,
command 1 | command 2  => so whatever output comes from command 1 flows to command 2


wc    file name => to check how the file looks like or get the basic set of stats about the file

grep    the text/word/phrase in double quotes    then file name => 
this command that lets you find occurences of certain words, or phrases or any particular expression within a set of files or a directory or project

grep    the text/word/phrase in double quotes    then file name  | wc => it will give the stats
there are -c and -h commands you cna use and search more of them on the web
