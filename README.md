# Gym-Git-Exercise-Solutions
Github repository that I will use to paste your terminal history into after each exercise
## bundle 1
# Exercises 1
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


# Exercises 2
```bash
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ touch home.html
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ touch about.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ touch team.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git add team.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git stash
Saved working directory and index state WIP on dev: fca81a4 changes on bundle 1 exercise1

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git add home.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git stash
Saved working directory and index state WIP on dev: fca81a4 changes on bundle 1 exercise1

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git add about.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git stash
Saved working directory and index state WIP on dev: fca81a4 changes on bundle 1 exercise1

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git stash list
stash@{0}: WIP on dev: fca81a4 changes on bundle 1 exercise1
stash@{1}: WIP on dev: fca81a4 changes on bundle 1 exercise1

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   about.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{1} (d68d9a03d3f17322ae411df4a307ec4d97d54399)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git commit -m "current changes"
[dev 43429f7] current changes
 4 files changed, 337 insertions(+), 3 deletions(-)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git push
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 2.49 KiB | 637.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
   fca81a4..43429f7  dev -> dev
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   team.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{0} (667815a751d63fd69ed8cb71c474739c1dfaf833)
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git reset
Unstaged changes after reset:
M       team.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$
```

### Bundle 2

# Exercise 1
```bash
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ touch services.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git commit -m "feat: new-featuer-added"
[ft/bundle-2 3a00187] feat: new-featuer-added
 3 files changed, 106 insertions(+), 2 deletions(-)
 create mode 100644 services.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git push Gym-Git-Exercise-Solutions ft/bundle-2
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 1.25 KiB | 428.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions
 [new branch]      ft/bundle-2 -> ft/bundle-2

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/bundle-2)
$

```
# Exercises 2

```bach
  user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git add README.md

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git stash
Saved working directory and index state WIP on ft/bundle-2: 3a00187 feat: new-featuer-added

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 913 bytes | 304.00 KiB/s, done.
From https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions
   5935dc5..dbfab27  main       -> origin/main
Updating 5935dc5..dbfab27
Fast-forward
 README.md     | 440 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 about.html    |  13 ++
 home.html     |  13 ++
 services.html |   0
 team.html     |  13 ++
 5 files changed, 479 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 services.html
 create mode 100644 team.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git stash list
stash@{0}: WIP on ft/bundle-2: 3a00187 feat: new-featuer-added

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git stash pop stash@{0}
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{0} (1e90289d641744eae91f9873dea83446bbefe699)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ touch service.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git commit -m "feat: new-feature-service-file"
[ft/service-redesign 23d9f2d] feat: new-feature-service-file
 2 files changed, 103 insertions(+)
 create mode 100644 service.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.22 KiB | 1.22 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign  
remote:
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git switch ft/service-redesign
Switched to branch 'ft/service-redesign'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git stash pop stash@{0}
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
On branch main
Your branch is up to date with 'origin/main'.

Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add <file>..." to mark resolution)
        both modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
The stash entry is kept in case you need it again.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 928 bytes | 77.00 KiB/s, done.
From https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions
   dbfab27..f2c9648  main       -> origin/main
Updating dbfab27..f2c9648
error: Your local changes to the following files would be overwritten by merge:
        README.md
Please commit your changes or stash them before you merge.
Aborting

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git add README.md

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git stash
Saved working directory and index state WIP on main: dbfab27 Merge pull request #2 from caleb-tuyisingize/ft/bundle-2

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git pull
Updating dbfab27..f2c9648
Fast-forward
 README.md    | 103 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 service.html |   0
 2 files changed, 103 insertions(+)
 create mode 100644 service.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git add service.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git stash
Saved working directory and index state WIP on main: f2c9648 Merge pull request #3 from caleb-tuyisingize/ft/service-redesign

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$


user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 921 bytes | 184.00 KiB/s, done.
From https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions
   f2c9648..1bf216a  main                -> origin/main
   23d9f2d..53fbd6e  ft/service-redesign -> origin/ft/service-redesign
Auto-merging README.md
Auto-merging service.html
CONFLICT (content): Merge conflict in service.html
Automatic merge failed; fix conflicts and then commit the result.

