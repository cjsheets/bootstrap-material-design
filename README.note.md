# Bootstrap Material Design

## Customization Overview

This repository is forked from [bootstrap-material-design](https://github.com/FezVrasta/bootstrap-material-design)
and contains custom color schemes and modifications for personal projects.

**Note:** I maintain this repository from a single endpoint and regularly squash pushed commits to keep the history clean. 

### Branches

All branches from upstream are unmodified.

* v4-dev-note
  * tracks the v4-dev branch and contains app-specific color schemes.
* dist-\*
  * contain builds from the parent branch of similar label

### NPM

For use with npm, add the following to package.json:

`"bootstrap-material-design": "https://github.com/cjsheets/bootstrap-material-design/tarball/dist-note"`


## Maintenance


**Modify**

* Clone repo: `git clone git@github.com:cjsheets/bootstrap-material-design.git`
* Install dependencies: `npm install && bower install`
* Perform maintenance tasks: ...
* Rebuild distribution: `grunt dist`
* Commit and push updates to v4-dev-note.

**Build Distribution**

* `git branch -d dist-note; git push origin --delete dist-note`
* `git checkout -b dist-note`
* Prepare dist: `mkdir dist; mv -t dist/ README.md .gitignore LICENSE.md package.json js scss`
* `rm *; rm .*; rm -R n* b*; mv dist/* .; rm -R d*`
* git push origin --delete dist-note
* Commit and push dist-note

[![Analytics](https://cjs-beacon.appspot.com/UA-10006093-3/github/cjsheets/bootstrap-material-design?pixel)](https://github.com/cjsheets/bootstrap-material-design)
