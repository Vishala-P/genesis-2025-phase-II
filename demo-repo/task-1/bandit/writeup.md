Bandit Level 0
Command used: ls
Command used: cat readme
Password found: ZjlJTmM6FvvyRnrB2rfNW0ZOTa6ip5If

Bandit Level 1
Command used: cat ./-
Password found: 263JGjpFGU6LtdEvgfWU1XP5yac29mFx

Bandit Level 2
Command used: ls
Command used: cat "--spaces in this filename--"
Password found: MNk8KNH3Usiio41PRUEoDFPqfxLPLSmx

Bandit Level 3
Command used: ls
Command used: cd
Command used: ls -a
Command used: cat ...Hiding-From-You
Password found: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

Bandit Level 4
Command used: ls
Command used: cd inhere
Command used: cat./-file*
Password found: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

Bandit Level 5
Command used: ls
Command used: cd inhere
Command used: find .-size 1033c
Command used: cat
Password found: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

Bandit Level 6
Command used: find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
Command used: cat
Password found: morbNTDkSW6jIlUc0ymOdMaLnOlFV
Bandit Level 7
Command used: ls
Command used: cat
Password found: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

Bandit Level 8
Command used: ls
Command used: sort data.txt | uniq -u
Password found: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

Bandit Level 9
Command used: ls
Command used: strings data.txt | grep =
Password found: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

Bandit Level 10
Command used: ls
Command used: base64 -d data.txt
Password found: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

Bandit Level 11
Command used: cat data.txt
Command used: cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
Password found: 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

Bandit Level 12
Command used: mkdir /tmp/vishala
Command used: cd /tmp/vishala
Command used: cp ~/data.txt .
Command used: xxd -r data.txt data
Command used: file data
Command used: mv data data.gz
Command used: gunzip data.gz
Command used: mv data data.bz2
Command used: bunzip2 data.bz2
Command used: mv data data.tar
Command used: tar -xf data.tar
Command used: mv data5.bin data5.tar
Command used: tar -xf data5.tar
Command used: mv data6.bin data6.bz2
Command used: bunzip2 data6.bz2
Command used: mv data6 data6.tar
Command used: tar -xf data6.tar
Command used: mv data8.bin data8.gz
Command used: gunzip data8.gz
Command used: cat data8
Password found: FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn

Bandit Level 13

Command used: ls
Command used: cat sshkey.private
Command used: chmod 600 sshkey.private
Command used: ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220
Command used: cat /etc/bandit_pass/bandit14
Password found: MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
