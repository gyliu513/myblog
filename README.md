git remote add origin git@github.com:gyliu513/myblog.git
git push -u origin master

echo "# myblog" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:gyliu513/myblog.git
git push -u origin master

npm install
hexo new "title"
hexo server
hexo deploy
