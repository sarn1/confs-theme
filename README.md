# example-jekyll-github

An example project of using Jekyll through Github and hosting it on said platform.  Original theme has been [forked](https://github.com/WebConfs/confs-theme) from WebConf.  The website is hosted on Github and can be seen at: [https://sarn1.github.io/example-jekyll-github/](https://sarn1.github.io/example-jekyll-github/).

## Initial Setup

- [Forked](https://github.com/WebConfs/confs-theme) conf-theme by going to the page and clicking on fork.
- Renamed project to ExampleJekyllGithub
- In terminal did the following:
```
git init
git remote add origin git@github-sarn1:sarn1/example-jekyll-github.git
config user.name "sarn1"
git pull origin master
touch .gitignore
vim .gitignore
config user.name "sarn1"
config user.email “email@example.com”
git add .
git commit -m “first push”
git push origin master
git branch -b gh-pages
git checkout gh-pages
git merge master
git push origin gh-pages
```

## Tools
- Github
- Jackyll (through Github)
- PHPStorm
- [gitignore.io](https://www.gitignore.io/)