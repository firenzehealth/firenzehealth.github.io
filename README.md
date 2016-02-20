# :fire: Warning! Not serving from the gh-pages branch at present. :fire:
 master branch controls everything! See http://stackoverflow.com/questions/29758952/have-github-pages-render-gh-pages-branch-rather-than-jekyll-content-on-master-br for fix

# GitHub Pages Boilerplate

- Bootstrap 3
- Gulp
- Livereload
- Sass

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
