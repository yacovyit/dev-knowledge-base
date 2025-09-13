# Linux Commands

1. pwd
2. ls
3. cd
4. cp
5. mv
6. rm
7. mkdir
8. sudo
9. exit
10. history
11. cat
12. grep
13. head
14. tail
15. cut
16. sed
17. awk

## Navigation
```bash
pwd        # print working dir
ls -la     # list with details
cd /path   # change dir
```

## File Operations
``` 
cp file1 file2    # copy
mv file1 file2    # move/rename
rm -rf dir/       # remove dir
mkdir  dir        # create directory
mkdir -p a/b/c.   # create directories recursive              
```

## Sudo - set user
```bash
sudu -i           # login as root user
exit              # logout from the logged in user 
```

## History command
```bash
history           # show previous commands
```

```bash
cat /etc/os-release   # os relase info
```

## grep
```bash
grep "pattern" file.txt             # search for "pattern" in file
grep -i "pattern" file.txt          # case-insensitive search
grep -r "pattern" /path/to/dir      # recursive search in files
grep -n "pattern" file.txt          # show line numbers
grep -v "pattern" file.txt          # invert match (exclude)

```

## head
```bash
head file.txt                       # first 10 lines
head -n 20 file.txt                 # first 20 lines
head -c 50 file.txt                 # first 50 characters
```

## tail
```bash
tail file.txt                       # last 10 lines
tail -n 20 file.txt                 # last 20 lines
tail -f file.txt                    # follow updates (e.g., logs)
```

## cut
```bash
cut -c1-5 file.txt                  # first 5 characters of each line
cut -d"," -f1 file.csv              # first column (CSV with comma)
cut -d":" -f1,3 /etc/passwd         # first and third fields
```

## sed
```bash
sed 's/foo/bar/' file.txt           # replace first "foo" with "bar" per line
sed 's/foo/bar/g' file.txt          # replace all "foo" with "bar"
sed -i 's/foo/bar/' file.txt        # replace first "foo" with "bar" per line and save to the file
sed -n '5,10p' file.txt             # print lines 5 to 10
sed '/pattern/d' file.txt           # delete lines matching pattern
```

## awk
```bash
awk '{print $1}' file.txt           # print first column
awk -F"," '{print $2,$3}' file.csv  # print 2nd and 3rd columns (CSV)
awk '{sum += $1} END {print sum}' file.txt   # sum of first column
awk '/pattern/ {print $0}' file.txt # print lines matching pattern
```
