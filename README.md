# Welcome to this NW.js tutorial! :smiley:

Today we will be shipping out our :apple: **Mac** OSX-developed application to a **Win64** OS.  :computer:  
_Please note: this tutorial is based on an instructional lecture originally presented by Rick Patci.   
Feel free to use this guide to walk through these steps at your leisure._

## Your _node_ environment:
- Please ensure you are using a version of node compatible with the latest NW.js build (at the time of  
this initial documentation, node-v6.1.0).  
- If you have nvm, nodenv, etc. you may also add that particular node version.

## Converting this app:

1. Fork and clone **this** repo 
2. `cd nwjs-tutorial`
3. `npm install nw`
4. Open in editor.
5. ####The following steps will enable you to develop and test not only this app, but **any** app before bundling it up for desktop use.
  1. Navigate to `package.json`
  2. Append **`"start": "nw"`** to the scripts option.  
![package.json](https://cloud.githubusercontent.com/assets/12869788/15266877/e828f8ac-1966-11e6-9e03-b99739d24b26.png)  

  3. Recommended: append some explicit `window` options after the scripts option.
    ```javascript
    "window": {
      "title": "Sample NW.js App",
      "toolbar": false,
      "fullscreen": false,
      "width": 700,
      "height": 400,
      "resizable": false
    },
    ```  

## Downloading NW.js Binaries:  
1. In your browser, navigate to [NWjs.io](www.nwjs.io)
2. We want to specifically build for Windows 64 in this example, which can be found by clicking on the [`DOWNLOADS`](http://nwjs.io/downloads/) link:
![nwjs home](https://cloud.githubusercontent.com/assets/12869788/15453014/d65fc77e-1fb8-11e6-900f-5a17751f2be5.png)



