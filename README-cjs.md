# Bootstrap Material Design

## Customization Overview

This repository is forked from [bootstrap-material-design](https://github.com/FezVrasta/bootstrap-material-design)
and contains custom color schemes and modifications for personal projects.

**Note:** I maintain this repository from a single endpoint and regularly squash pushed commits to keep the history clean. 

### Branches

All branches from upstream are unmodified.

* master-cjs
  * tracks the master branch and contains personal-site configurations.
* v4-dev-note
  * tracks the v4-dev branch and contains app-specific color schemes.
* dist-\*
  * contain builds from the parent branch of similar label

### NPM

For use with npm, add the following to package.json:

`"bootstrap-material-design": "https://github.com/cjsheets/bootstrap-material-design/tarball/dist-cjs"`


## Maintenance


**Modify**

* Clone repo: `git clone git@github.com:cjsheets/bootstrap-material-design.git`
* Install dependencies: `npm install && bower install`
* Perform maintenance tasks: ...
* Rebuild distribution: `grunt dist`
* Commit and push updates to master-cjs.

**Build Distribution**

* `git branch -d dist-cjs; git push origin --delete dist-cjs`
* `git checkout -b dist-cjs`
* Prepare dist: `mv -t dist/ README.md .gitignore LICENSE.md package.json scripts`
* `rm *; rm .*; rm -R t* s* n* l* g* b* .s*; mv dist/* .; rm -R d*`
* git push origin --delete dist-cjs
* Commit and push dist-cjs

[![Analytics](https://cjs-beacon.appspot.com/UA-10006093-3/github/cjsheets/bootstrap-material-design?pixel)](https://github.com/cjsheets/bootstrap-material-design)
