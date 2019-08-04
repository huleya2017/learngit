1:open .//open current account
2:mkdir  xxx//create new folder
3:touch xxx.txt//create new .txt file
4:ls :list all file under a folder


1:add file and commit it
git add filename
git commit -m “comment”
2:push local file to github
git push origin master

3:clone a repo from github to local
git clone git@github.com:huleya/reponame.git

3:tag
3.1:git tag<name>//create a new tag
3.2:git tag. //list all tags
3.3:git show <tagname> //show tag
3.4git log --pretty=oneline --abbrev-commit
3.4.1 git tag <tagname> logname