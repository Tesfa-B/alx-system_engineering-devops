*All scripts for the task
echo "Hello,World" : 0-hello_world: for printing hello world in standard output.
echo "/"(Ôo)'" : 1-confused_smiley for displaying "(Ôo)'.
cat /etc/passwd : for displaying content of the path.
cat /etc/passwd  /etc/hosts : for displaying the content of  both paths.
tail -10 /etc/passwd : display the last 10 lines of the content of the path
head -10  /etc/passwd : dispaly the first 10 lines of the content of the path.
head -n 3 iacta | tail -1 : for displaying slected line  of the file.
echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\): for the file name and content BEst school.
ls -la > ls_cwd_content: list all content of the current dirctory.
tail -n 1 iacta >> iacta : duplicate the last line.
find . -type f -name "*.js" -delete : delete files that end with js.
find . -type d ! -path . | wc -l :list the number of directories and sub directories.
ls -t . | head : display 10 newest files in current directory.
sort | uniq -u :sort in unique way. 
egrep "root" /etc/passwd  :find root in the path.
egrep -c "bin" /etc/passwd :number of lines that contain "bin" in the path.
egrep -A 3 "root" /etc/passwd :display the 3 lines after "root".
egrep -v "bin" /etc/passwd :display the line that do not contain "Bin" in the path.
egrep ^[[:alpha:]] /etc/ssh/sshd_config :display the only  alphabets  in the path.
tr 'Ac' 'Ze' :replace characters 'Ac' to "ze" 
tr -d cC : remove th character Cc .
rev :reverse
cut -d ':' -f 1,6 /etc/passwd | : display all users and thier dirctories  sorted by user.
find . -empty | rev | cut -d '/' -f 1 | rev :display an empty file in the dirctory .
find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f: display files that end with(*gif) in sorted.

cut -c 1 | paste -s -d :decodes the first letter of each line.
tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev | cut -d ' ' -f -1 | rev :display 11 parsed web serers logs in TSV format sorted by request load 

