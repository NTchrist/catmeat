# catmeat
cat only the meat of a file (no comments, no empty lines)

Useful for condensing large config files down to just the meat and potatoes

--

usage:

catmeat /path/to/file [DELIM]

if no [DELIM] is specified, it will default to "#"

--

Install with (as root):

wget https://raw.githubusercontent.com/NTchrist/catmeat/main/catmeat -O /usr/bin/catmeat; chmod +x /usr/bin/catmeat
