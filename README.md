# Welcome to NW.js! :smiley:

_This tutorial is part of a follow-along lecture originally presented by Rick Patci. Feel free to use this guide to walk through the steps at your leisure._

## Your _node_ environment:
- Please ensure you are using a version of node compatible with the latest NW.js build (at the time of this initial documentation, node-v6.1.0).  
- If you have nvm, nodenv, etc. you may also add that particular node version.

## Converting this app:

1. Fork and clone **this** repo 
2. `cd nwjs-tutorial`
3. `npm install nw`
3. Open in editor.
4. The following steps will enable you to develop and test any app before bundling it up. 
  - Navigate to `package.json`
  - Append **`"start": "nw"`** to the scripts object.  
![package.json](https://cloud.githubusercontent.com/assets/12869788/15266877/e828f8ac-1966-11e6-9e03-b99739d24b26.png)  

  - Optional: append any explicit `window` properties after the scripts object:
  ```javascript
  "window": {
    "title": "Sample NW.js App",
    "toolbar": false,
    "fullscreen": false,
    "width": 700,
    "height": 350,
    "resizable": false
  },
  ```  

## Downloading NW.js:  
- This part coming soon! 

