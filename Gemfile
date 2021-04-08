source "https://rubygems.org"

gem 'github-pages', '>= 207'
gem 'html-proofer', '>= 3.13.0'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]
git fetch origin
git checkout -b master origin/master
git merge main
git checkout main
git merge --no-ff master
git push origin main
