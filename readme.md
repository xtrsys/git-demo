# Prerequisites

Visual Studio Code <https://code.visualstudio.com/Download>
`winget install vscode`

Git for Windows <https://git-scm.com/download/win>
`winget install --id Git.Git -e --source winget`

Windows Terminal (optional) <https://docs.microsoft.com/en-us/windows/terminal/install>
`winget install --id=Microsoft.WindowsTerminal -e`

Oh My Posh (optional) <https://ohmyposh.dev/docs/installation/windows>
`winget install JanDeDobbeleer.OhMyPosh -s winget`

# Version control 101

### Local commands

To create or rather add existing folder as git repository use this command in terminal of your choice
`git init`

To clone already existing repository use
`git clone`

To switch between branches use
`git checkout branch_name_goes_here`

To create new branch use `-b` parameter
`git checkout -b branch_name_goes_here`

To merge changes from branch2 into branch1

`git checkout branch1`
`git merge branch2`

### Remote repository with task

1. Clone this repository `https://github.com/xtrsys/git-demo.git`
2. Make a new branch with following naming `features/your_name_first_letter_of_last_name`
3. Add new file to repository and commit it
4. Create a pull request to merge your branch into `master`

### This is to appear after merging into master
