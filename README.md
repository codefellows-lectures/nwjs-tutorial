# Welcome to NW.js! :smiley:

_This tutorial is part of a follow-along lecture originally presented by Rick Patci. Feel free to use this guide to walk through the steps at your leisure._

## Your _node_ environment:
- Please ensure you are using a version of node compatible with the latest NW.js build (at the time of this initial documentation, node-v6.1.0).  
- If you have nvm, nodenv, etc. you may also add that particular node version.
- After node install or upgrade completes: `npm i -g nw`

## Downloading NW.js:

## Converting this app:
1. Fork and clone this repo.
2. Open repo in editor.
3. Edit the package.json as follows: 
  - Append **`"start": "nw"`** to the scripts object.  
  ![package.json](https://cloud.githubusercontent.com/assets/12869788/15266877/e828f8ac-1966-11e6-9e03-b99739d24b26.png)

