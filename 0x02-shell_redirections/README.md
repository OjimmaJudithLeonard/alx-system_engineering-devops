shell redirection scripts
 #!/bin/bash
echo “Hello, World”
echo ‘ "(Ôo)'\’
 #!/bin/bash
cat /etc/passwd
 #!/bin/bash
cat /etc/passwd /etc/hosts
 #!/bin/bash
echo 'Best School' > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)
 #!/bin/bash
ls -la > ls_cwd_content
 #!/bin/bash
tail -n 1 < iacta >> iacta
 #!/bin/bash
find -name "*.js" -type f -delete
 #!/bin/bash
find . -type d -not -name '.' | wc -1
 #!/bin/bash
ls -t1 | head -n 10
 #!/bin/bash
sort | uniq -u
 #!/bin/bash
grep -i "root" /etc/passwd
 #!/bin/bash
grep -c -i "bin" /etc/passwd
  #!/bin/bash
grep -i "root" -A 3 /etc/passwd

 #!/bin/bash
grep -v "bin" /etc/passwd

 #!/bin/bash
grep ^[[:alpha:]] /etc/ssh/sshd_config

 #!/bin/bash
tr "A" "Z"  | tr "c" "e"

 #!/bin/bash
tr -d "c" | tr -d "C"

 #!/bin/bash
rev

 #!/bin/bash
cut -d : -f 1,6 /etc/passwd | sort
 
 #!/bin/bash 
find . -empty | rev | cut -d '/' -f 1 | rev

 #!/bin/bash 
find -type f -name "*.gif" | rev | cut -d "/" -f 1 |cut -d '.' -f 2- | rev | LC_ALL=C sort -f


 #!/bin/bash 
cut -c 1 | paste -s -d ''


 #!/bin/bash 
tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev | cut -d ' ' -f -1 | rev

