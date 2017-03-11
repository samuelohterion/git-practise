## Welcome to My GitHub Pages

Remember link: [editor on GitHub](https://github.com/samuelohterion/git-practise/edit/master/docs/README.md) to maintain and preview the content for your website in Markdown files.

### This is my practise git page

Here i log what i've done to come to where

# LOG
## First clone repo from github
git clone https://github.com/samuelohterion/git-practise.git
## prepare github pages via docs folder
### in local git-practise directory
1. > mkdir docs
2. > mv README.md docs/
3. > git add .
4. > git commit -m "create /docs and move README.md into it"
5. > git push
### on github edit README.md
1. pull the repo
2. > git pull
3. > gedit /docs/README.md
- Write this here
- Save, leave
4. > git add .
5. > git commit -m "update README.md LOG3"
6. > git push
## now force a conflict
edit README.md, add and commit LOG6local
analogous on github

