`git log --oneline` 

yields:

`c2d2fd4 status script and configs for rasp pi prototype`

if that isn't enough and you need author and date, try:

`git log --pretty=format:"%h%x09%an%x09%ad%x09%s"`

which yields

`c2d2fd4 steven_pack     Sun Feb 23 10:37:16 2014 +0000  status script and configs for rasp pi prototype`