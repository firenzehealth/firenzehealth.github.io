# Firenzehealth.com

Default Development Branch: `dev`
Deploy Target Branch: `master` (See [question on StackOverflow](http://stackoverflow.com/questions/29758952/have-github-pages-render-gh-pages-branch-rather-than-jekyll-content-on-master-br) 

## Configuration
```bash
PROJECT_NAME=your-project
GITHUB_USER=your-user
REPO_URL="git@github.com:$GITHUB_USER/$PROJECT_NAME"
```

## Fork Boilerplate
```bash
git clone git@github.com:gronke/gh-pages-boilerplate "$PROJECT_NAME"
cd "$PROJECT_NAME"
git remote rm origin
git remote add origin "$REPO_URL"
git push origin master:master
```

## Install Dependencies
```bash
npm -g install bower
npm install
bower install
```

## Run Development Server
```bash
gulp
```

## Deploy with
```bash
gulp deploy
```
