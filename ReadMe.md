# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).


# This is Git's per-user configuration file.
[user]
    name = Tim James
    email = timbjames@gmail.com
[push]
    default = simple
    
[branch]
    autosetuprebase = always
    
[merge]
    ff = true   
[core]
    editor = \"C:\\Users\\Tim\\AppData\\Local\\Programs\\Microsoft VS Code\\Code.exe\" --wait
    autocrlf = true
[credential]
[filter "lfs"]
    clean = git-lfs clean %f
    smudge = git-lfs smudge %f
    required = true
[code]
    editor = code --wait    
[diff]
    tool = vscode
[difftool]
    prompt = true
[difftool "vscode"]
    cmd = code --wait --diff $LOCAL $REMOTE
[difftool "vscode"]
    keepbackup = false
[merge]
    tool = vscode
[mergetool]
    prompt = true
[mergetool "vscode"]
    cmd = code --wait $MERGED
    trustexitcode = true
[mergetool "vscode"]
    keepbackup = false
[alias]
    ec = config --global -e
    aa = add --all
    cm = commit -m
    cma = commit -am
    undo = reset --soft HEAD^
    recommit = commit -a -c ORIG_HEAD
    newb = checkout -b
    co = checkout
    lc = log --pretty=format:"%C(yellow)%h%Cred%d\\ %Creset%s%Cblue\\ [%cn]" --decorate
    ls = log --pretty=format:"%C(yellow)%h%Cred%d\\ %Creset%s%Cgreen\\ [%cn]" --decorate --numstat
    lbr = log --graph --oneline --decorate --all
    lbr2 = log --graph --pretty=oneline --abbrev-commit
    lsa = "!git config -l | grep alias | cut -c 7-"
    sl = stash list
    ss = stash save
    sa = stash apply
    st = status -s
    stl = status
    br = branch
    brr = branch -r
    fap = fetch -p
    df = diff
    dw = diff --word-diff
    dt = difftool
    ds = diff --stat --stat-width=200
    dl = diff --cached --stat HEAD^
    cif = clean -i -f
    ciff = clean -i -d
    tg = for-each-ref --sort=taggerdate --format '%(refname)' refs/tags
    yolo = "!git add --all; git commit -am \"DEAL WITH IT\"; git push origin master --force"
    find = log --pretty=\"format:%Cgreen%H %Cblue%s\" --name-status --grep
    
[color]
  ui = true
  
[color "diff"]
    meta = white blue reverse
    frag = reverse 
    old = yellow bold
    new = green bold
    
[color "branch"]
    current = green bold
    local = normal
    remote = red black bold
    
[color "status"]
  added = green bold
  changed = green bold
  untracked = yellow bold
[credential]
    helper = wincred

