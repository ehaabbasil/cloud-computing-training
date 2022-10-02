# 02 Oct 2022

### Basic Commands of Git
To initialize a new Local repository. Here the command

```
git init

```

for adding single file
```
git add filename
```

for adding multiple files (all files) in the current directory

```
git add .
```

How do i push. You can't push without a
server. Please map to the remote the server using a custom ```alias``` name.

```
git remote add `alias` officeServer https://repoUrl

```

if you have only single remote
```
git push 
```

for multiple remote servers. You need to tell the alias name to push

```
git push -u origin <branch>
```

git add session-4-02-ct-2022.md
git add .

git commit -m "added initial commands"
