pwd - print working directory
less - pager, basic way to read
  q to quit

rmdir - remove directory
  -p for remove parents

rm - remove
  -r remove recursively

wc - word count
  -l line count

uniq - unique lines

man - manual for a command

su - Switch to superuser

sudo - Switch to superuser and do this command
  Better option

alias - give alias (name) to command/commands

chmod - set permissions
  rwxrwxrwx
  owner, then group, then others
    0 - no permissions
    1 - Execute
    2 - Write
    3 - WE
    4 - read
    5 - RE
    6 - RW
    7 - RWE

chown - Change owner
  `sudo chown dave:mary example.txt`

curl - get from internet

df - shows size and space used/available on filesystem
  -h human readable
  -x Exclude

diff
  -y (show side by side)
  -w change max width
  --suppress-common-lines don't show matching lines

echo

find - find a file
  -name the name of the file
  -type the type of the file
  -iname case insensitive

finger - shows user info

free - how much memory is available
  -h human readable

grep - search for things
  See man grep for more details, way too many to name
  -A lines after
  -B lines before

gzip - compress file
  -k keep original file

head - list first lines of file

history - show command history

kill - Kill the process
  Use different signals, like -9

ps - See processes running
  -u ianjungmann (see for a user)
  -e see every process

tail - See end of files

tar - Create an archive file (and potentially compress)

top - see general system data
