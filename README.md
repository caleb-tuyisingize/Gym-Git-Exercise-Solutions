# Gym-Git-Exercise-Solutions
Github repository that I will use to paste your terminal history into after each exercise
## bundle 1
Exercises 1
```bash
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git checkout -b master
Switched to a new branch 'master'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (master)
$ git shift main
git: 'shift' is not a git command. See 'git --help'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (master)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git commit
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git checkout -b master
fatal: a branch named 'master' already exists

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git switch master
Switched to branch 'master'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (master)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (master)
$ git commit 
On branch master
nothing to commit, working tree clean

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (master)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git switch master
Switched to branch 'master'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (master)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git commit
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git checkout -b dev
Switched to a new branch 'dev'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git commit
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git checkout -b dev
Switched to a new branch 'dev'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean

nothing to commit, working tree clean

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git checkout -b dev
Switched to a new branch 'dev'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
$ git checkout -b dev
Switched to a new branch 'dev'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean

nothing to commit, working tree clean
nothing to commit, working tree clean

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git switch maste
fatal: invalid reference: maste

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git switch master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (master)
$ git switch dev
M       README.md
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git branch -d test
error: branch 'test' not found

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git checkout -b test
Switched to a new branch 'test'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (test)
$ git switch dev
M       README.md
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git branch -d test
Deleted branch test (was 5935dc5).

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git commit -m "branch test deleted"
[dev 50400c0] branch test deleted
 1 file changed, 2 insertions(+)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git push dev
fatal: 'dev' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git push Gym-Git-Exercise-Solutions dev
fatal: 'Gym-Git-Exercise-Solutions' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git add remote Gym-Git-Exercise-Solutions https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions
fatal: pathspec 'remote' did not match any files

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git remote add Gym-Git-Exercise-Solutions https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions
 
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git push Gym-Git-Exercise-Solutions dev
fatal: unable to access 'https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions/': Could not resolve host: github.com

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git remote add Gym-Git-Exercise-Solutions https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions
error: remote Gym-Git-Exercise-Solutions already exists.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ ipconfig flushdns

Error: unrecognized or incomplete command line.

USAGE:
    ipconfig [/allcompartments] [/? | /all |
                                 /renew [adapter] | /release [adapter] |
                                 /renew6 [adapter] | /release6 [adapter] |
                                 /flushdns | /displaydns | /registerdns |
                                 /showclassid adapter |
                                 /setclassid adapter [classid] |
                                 /showclassid6 adapter |
                                 /setclassid6 adapter [classid] ]

where
    adapter             Connection name
                       (wildcard characters * and ? allowed, see examples)

    Options:
       /?               Display this help message
       /all             Display full configuration information.
       /release         Release the IPv4 address for the specified adapter.
       /release6        Release the IPv6 address for the specified adapter.
       /renew           Renew the IPv4 address for the specified adapter.
       /renew6          Renew the IPv6 address for the specified adapter.
       /flushdns        Purges the DNS Resolver cache.
       /registerdns     Refreshes all DHCP leases and re-registers DNS names
       /displaydns      Display the contents of the DNS Resolver Cache.
       /showclassid     Displays all the dhcp class IDs allowed for adapter.
       /setclassid      Modifies the dhcp class id.
       /showclassid6    Displays all the IPv6 DHCP class IDs allowed for adapter.
       /setclassid6     Modifies the IPv6 DHCP class id.


The default is to display only the IP address, subnet mask and
default gateway for each adapter bound to TCP/IP.

For Release and Renew, if no adapter name is specified, then the IP address
leases for all adapters bound to TCP/IP will be released or renewed.

For Setclassid and Setclassid6, if no ClassId is specified, then the ClassId is removed.

Examples:
    > ipconfig                       ... Show information
    > ipconfig /all                  ... Show detailed information
    > ipconfig /renew                ... renew all adapters
    > ipconfig /renew EL*            ... renew any connection that has its
                                         name starting with EL
    > ipconfig /release *Con*        ... release all matching connections,
                                         eg. "Wired Ethernet Connection 1" or
                                             "Wired Ethernet Connection 2"
    > ipconfig /allcompartments      ... Show information about all
                                         compartments
    > ipconfig /allcompartments /all ... Show detailed information about all
                                         compartments

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git remote add Gym-Git-Exercise-Solutions https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions
error: remote Gym-Git-Exercise-Solutions already exists.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git push Gym-Git-Exercise-Solutions dev
fatal: unable to access 'https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions/': Could not resolve host: github.com

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git remote -v
Gym-Git-Exercise-Solutions      https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions (fetch)
Gym-Git-Exercise-Solutions      https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions (push)
origin  https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git (push)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git remote remove $ git remote -v
Gym-Git-Exercise-Solutions      https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions (fetch)    
Gym-Git-Exercise-Solutions      https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions (push)     
origin  https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git (push
error: unknown switch `v'
usage: git remote remove <name>

bash: syntax error near unexpected token `('
bash: syntax error near unexpected token `('
bash: syntax error near unexpected token `('
bash: syntax error near unexpected token `('

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git remote remove Gym-Git-Exercise-Solutions

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git push Gym-Git-Exercise-Solutions dev
fatal: 'Gym-Git-Exercise-Solutions' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git remote remove Gym-Git-Exercise-Solutions.git
error: No such remote: 'Gym-Git-Exercise-Solutions.git'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git remote -v
origin  https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git (push)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git remote add Gym-Git-Exercise-Solutions https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions
 
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git push Gym-Git-Exercise-Solutions dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions
   5935dc5..50400c0  dev -> dev

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$
```
