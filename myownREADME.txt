bundle install
bundle update



bundle exec jekyll build --verbose
bundle exec jekyll s

git branch -M main
git branch -M gh-pages

git push origin gh-pages

