# blazordemo

## Setup
```
git init
git add .
echo "# blazordemo" >> readme.md
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/bickeylam/blazordemo.git
git push -u origin main
```
or
```
git remote add origin https://github.com/bickeylam/blazordemo.git
git branch -M main
git push -u origin main
```

## Create `gh-pages`
```
git branch gh-pages
git checkout gh-pages
git push --set-upstream origin gh-pages
```