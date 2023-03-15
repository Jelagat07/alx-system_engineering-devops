echo "Hello, World"
find . -type f -and -name "*.js" -delete
find . -mindepth 1 -type d | wc -l
ls -t|head
sort|uniq -u
grep "root" /etc/passwd
grep "bin" /etc/passwd|wc -l
grep "root" -A 3 /etc/passwd
grep "bin" -v /etc/passwd
grep "^[[:alpha:]]" /etc/ssh/sshd_config
cat|tr 'Ac' 'Ze'
echo '"(Ôo)'\'
cat |tr -d 'Cc'
cat|rev
cat /etc/passwd|cut -d: -f 1,6 |sort
less /etc/passwd
less /etc/passwd /etc/hosts
ls -lt|tail /etc/passwd
ls -lt|head /etc/passwd
head -3 iacta | tail +3
echo "Best School"> \*\\'"Best School"\'\\*$\?\*\*\*\*\*:)
ls -la>ls_cwd_content
22.tail -1 iacta>>iacta
