# GitHub practice

Scenario: Created branch from master, but need to replace folders on branch back to master
1. `git clone https://github.com/address-here`
2. `git checkout -b YOUR-GITHUB-USERNAME-HERE`
3. `git add`
4. `git commit -m "commit message here"`
5. `git push origin YOUR-GITHUB-USERNAME-HERE`
6. then you realize that you need to restore your branch folder to master!
7. what do you do?



Test Method:
METHOD 1: use `git checkout origin/master filename` to retrieve master's filename to local repo

    1. stay in the local folder file-of-interest

    2. `git checkout origin/master filename`

    3. `git add --all`

    4. `git commit -m "message here"`

    5. git push origin "YOUR-GITHUB-USERNAME-HERE"
