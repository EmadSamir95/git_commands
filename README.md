# Basic commands of git
```bash
$touch index.html 
$touch app.js
```

```bash
$git init
```

```bash
$git config --global user.name 'your name'
$git config --global user.email 'youremail@example.com'
```

```bash
$git status
```

```bash
$git add index.html     //add this file only
$git add *.html        // add all .html files
$git add .            // add all files
```

```bash
$git rm --cached index.html
```

```bash
 $git commit -m 'initial commit or any comment you prefer'
```

```bash
$touch .gitignore       //open it
$touch log.txt         // Creat the file to be ignored
log.txt               // write the name of ignored file
/folder_name         // ignore directory
*.txt               // ignore all text files
```

```bash
$git branch mybranch        //create your branch
$git checkout mybranch     // switch to this branch
```

```bash
$git merge mybranch     //merge this with master, write a comment and use esc+:wq+enter
```

```bash
$git remote add origin http:// copy the link of the repo
$git push -u origin master
```

```bash
you can clone from an existing repository using
$git clone http:// the link of repo
```

```bash
$git pull       //get the pull request made by other teammate
```
