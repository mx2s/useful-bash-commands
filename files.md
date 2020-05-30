# Useful files commands
print count of files by extension

`find . -type f | sed -e 's/.*\.//' | sort | uniq -c | sort -n`
