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

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git switch ft/service-redesign
warning: unable to rmdir 'git-cafe-exercise': Directory not empty
Switched to branch 'ft/service-redesign'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git add .
warning: adding embedded git repository: git-cafe-exercise
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> git-cafe-exercise
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached git-cafe-exercise
hint:
hint: See "git help submodule" for more information.
hint: Disable this message with "git config set advice.addEmbeddedRepo false"

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git commit -m "changes applied on service"
[ft/service-redesign 1dc4468] changes applied on service
 2 files changed, 3 insertions(+)
 create mode 160000 git-cafe-exercise

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git push origin ft/service-redesign
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
 ! [rejected]        ft/service-redesign -> ft/service-redesign (non-fast-forward)
error: failed to push some refs to 'https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git'   
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git pull origin ft/service-redesign
From https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions
 * branch            ft/service-redesign -> FETCH_HEAD
Auto-merging service.html
CONFLICT (content): Merge conflict in service.html
Automatic merge failed; fix conflicts and then commit the result.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign|MERGING)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign|MERGING)
$ git commit -m "changes applied on service"
[ft/service-redesign d9f1c79] changes applied on service

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 710 bytes | 355.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
   403335b..d9f1c79  ft/service-redesign -> ft/service-redesign

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git commit -m "tasks in readme md file"
[ft/service-redesign 10237eb] tasks in readme md file
 1 file changed, 69 insertions(+)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.19 KiB | 406.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
   d9f1c79..10237eb  ft/service-redesign -> ft/service-redesign

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git fetch origin

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git merge origin main
Auto-merging README.md
Merge made by the 'ort' strategy.
 README.md     | 445 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++--
 contact.html  |  13 ++
 faq.html      |  13 ++
 home.html     |   3 +-
 services.html |  13 ++
 team.html     |   2 +-
 tofooter.html |  16 +++
 7 files changed, 492 insertions(+), 13 deletions(-)
 create mode 100644 contact.html
 create mode 100644 faq.html
 create mode 100644 tofooter.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/service-redesign)
$

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
```
### Bundle 3

# Exercise 1

```bash
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git checkout -b ft/team-page

Switched to a new branch 'ft/team-page'
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page)
$ touch team.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page)
$ git commit -m "feat: team file"
[ft/team-page 9cbaba7] feat: team file
 1 file changed, 1 insertion(+), 1 deletion(-)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 311 bytes | 311.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions/pull/new/ft/team-page
remote:
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/team-page -> ft/team-page

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page)
$

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page|REVERTING)
$ git revert -m 1 6e6e42f89763432ad25ac2b2a4e8a3f3b02e21fc
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
error: could not revert 6e6e42f... readme files
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".
hint: Disable this message with "git config set advice.mergeConflict false"

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page|REVERTING)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page|REVERTING)
$ git commit -m "m"
[ft/team-page 28d39dc] m
 1 file changed, 2 insertions(+), 79 deletions(-)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page|REVERTING)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page)
$ git commit -m "changes by revert"
[ft/team-page e85a8da] changes by revert
 1 file changed, 23 insertions(+)

 user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 16 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (11/11), 1.63 KiB | 333.00 KiB/s, done.
Total 11 (delta 6), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (6/6), completed with 2 local objects.
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
   6e6e42f..e85a8da  ft/team-page -> ft/team-page

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/team-page)
$


user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LA
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git commit -m "changes back in main"
[main 6ba7619] changes back in main
 2 files changed, 10 insertions(+), 2 deletions(-)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 403 bytes | 403.00 KiB/s, done.
Total 4 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
   e561760..6ba7619  main -> main

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$
```

#### Bundle 4

# Exercises 1

```bash

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git remote add git-copy https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions-copy.git

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$


user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git commit -m "copy of files in another repo"
[main 73fc1ce] copy of files in another repo
 2 files changed, 22 insertions(+), 1 deletion(-)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git push origin
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 490 bytes | 490.00 KiB/s, done.
Total 4 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
   b88f081..73fc1ce  main -> main

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git push git-copy
Enumerating objects: 102, done.
Counting objects: 100% (102/102), done.
Delta compression using up to 16 threads
Compressing objects: 100% (101/101), done.
Writing objects: 100% (102/102), 22.15 KiB | 504.00 KiB/s, done.
Total 102 (delta 58), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (58/58), done.
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions-copy.git
 * [new branch]      main -> main

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$
```
## Exercises 2

```bash

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git checkout -b ft/footer
Switched to a new branch 'ft/footer'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/footer)
$ touch tofooter.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/footer)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/footer)
$ git commit -m "Footer branch"
[ft/footer 4155814] Footer branch
 2 files changed, 55 insertions(+), 1 deletion(-)
 create mode 100644 tofooter.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/footer)
$ git push origin ft/footer
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 821 bytes | 54.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions/pull/new/ft/footer
remote:
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/footer -> ft/footer

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/footer)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/footer)
$ git commit -m "Footer branch more changes"
[ft/footer 8f8f563] Footer branch more changes
 2 files changed, 4 insertions(+)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/footer)
$ git push origin ft/footer
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 394 bytes | 394.00 KiB/s, done.
Total 4 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
   4155814..8f8f563  ft/footer -> ft/footer

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/footer)
$

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (main)
$ git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/squashing)
$ git merge --squash ft/footer
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Squash commit -- not updating HEAD
Automatic merge failed; fix conflicts and then commit the result.

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/squashing)
$ git commit -m "footer changes squashing"
[ft/squashing df889a6] footer changes squashing
 3 files changed, 120 insertions(+), 4 deletions(-)
 create mode 100644 tofooter.html

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/squashing)
$ git push origin ft/squashing
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 16 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.20 KiB | 612.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions/pull/new/ft/squashing
remote:
To https://github.com/caleb-tuyisingize/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/squashing -> ft/squashing

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions (ft/squashing)
$


user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git push 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 337 bytes | 337.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/caleb-tuyisingize/git-cafe-exercise.git
   d1d3f9c..b08c545  main -> main

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git commit -m "another Welcome message changed"
[main c794833] another Welcome message changed
 1 file changed, 1 insertion(+), 1 deletion(-)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git push 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 323 bytes | 323.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/caleb-tuyisingize/git-cafe-exercise.git
   b08c545..c794833  main -> main

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git commit -m "reversed"
[main d37c1ef] reversed
 1 file changed, 1 insertion(+), 1 deletion(-)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git push 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 313 bytes | 313.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/caleb-tuyisingize/git-cafe-exercise.git
   c794833..d37c1ef  main -> main

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git checkout -b fx/index
Switched to a new branch 'fx/index'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fx/index)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fx/index)
$ git commit -m "fix: welcome message changed"
[fx/index 6270f11] fix: welcome message changed
 1 file changed, 1 insertion(+), 1 deletion(-)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fx/index)
$ git push origin fx/index
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 346 bytes | 346.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'fx/index' on GitHub by visiting:
remote:      https://github.com/caleb-tuyisingize/git-cafe-exercise/pull/new/fx/index
remote:
To https://github.com/caleb-tuyisingize/git-cafe-exercise.git
 * [new branch]      fx/index -> fx/index

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fx/index)
$
```


###### Bundle 6
# Exercises 1
```bash 
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fx/index)
$ git checkout -b ft/menu-page
Switched to a new branch 'ft/menu-page'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (ft/menu-page)
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (ft/menu-page)
$ git commit -m "fix: welcome to Menu message changed"
[ft/menu-page b8ced96] fix: welcome to Menu message changed
 2 files changed, 2 insertions(+), 1 deletion(-)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (ft/menu-page)
$ git push origin ft/menu-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 436 bytes | 436.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/menu-page' on GitHub by visiting:
remote:      https://github.com/caleb-tuyisingize/git-cafe-exercise/pull/new/ft/menu-page
remote:
To https://github.com/caleb-tuyisingize/git-cafe-exercise.git
 * [new branch]      ft/menu-page -> ft/menu-page

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (ft/menu-page)
$
```
# Exercises 2

```bash
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (ft/menu-page)
$ git checkout -b fix/contact-page
Switched to a new branch 'fix/contact-page'

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fix/contact-page)      
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fix/contact-page)      
$ git commit -m "fix: contact title added"
[fix/contact-page 8de5088] fix: contact title added
 1 file changed, 1 insertion(+), 1 deletion(-)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fix/contact-page)      
$ git push origin fix/contact-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 321 bytes | 321.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'fix/contact-page' on GitHub by visiting:
remote:      https://github.com/caleb-tuyisingize/git-cafe-exercise/pull/new/fix/contact-page
remote:
To https://github.com/caleb-tuyisingize/git-cafe-exercise.git
 * [new branch]      fix/contact-page -> fix/contact-page

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fix/contact-page)      
$
```
# Exercises 3

```bash
user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fix/contact-page)      
$ git add .

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fix/contact-page)      
$ git commit -m "fix: contact changed to new"
[fix/contact-page 0cbcefe] fix: contact changed to new
 1 file changed, 1 insertion(+), 1 deletion(-)

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fix/contact-page)      
$ git push origin fix/contact-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 323 bytes | 323.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/caleb-tuyisingize/git-cafe-exercise.git
   8de5088..0cbcefe  fix/contact-page -> fix/contact-page

user@LAPTOP-Q6O9PDFL MINGW64 /c/gymer/Gym-Git-Exercise-Solutions/git-cafe-exercise (fix/contact-page)      
$
```