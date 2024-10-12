bundle install
bundle update



bundle exec jekyll build --verbose
bundle exec jekyll s

git branch -M main
git branch -M gh-pages

git push origin gh-pages



git remote set-url origin git@github.com:syediu/syediu.github.io.git


siu@siu-g3:~/syediu.github.io$ bundle exec jekyll serve


copy http://127.0.0.1:4000

and paste it in a web browser
