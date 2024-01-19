# electron-forge-windows-exe


---------------------------------------USING ELECTRON BUILDER------------------------------------------------------------------------------------
Must have node version of 18.16.0 to execute

Creating windows store app:
```bash
1- Git clone:
https://github.com/Krallt-com/Phaser-Electron-Client/tree/main

In the project root directory do following commands:

2- npm i

3- npm i electron-builder -g

3- electron-builder
```

After running electron-builder you will get dis directory

Save the directory for phase3 Setup 1.0.0.exe for windows store setup found in dist folder after building. 

In order to run app; In win-unpacked folder, you will find phase3.exe, but before that you should have server running. https://github.com/Krallt-com/Phaser-Electron-Server at port 1444
 
Setting up msix package for windows store

Download msix packager
https://apps.microsoft.com/detail/9N5LW3JBCXKF?hl=en-us&gl=US

And follow steps from this website after step 3
https://www.codiga.io/blog/submit-electron-app-to-microsoft-store/


At this point (Create new Package) you have to share location of setup file i.e.  "phase3 Setup 1.0.0.exe"
Follow the steps as mentioned on website, after complete, you will get msix package that you can publish on windows store 


To change the endoint of server in client application, you have to modify variable urlToCheck in src/index.js
Thankyou

-------------------------------------------------------USING ELECTRON FORGE-----------------------------------------------------------
Must have node version of 18.16.0 to execute

Creating windows store app:
```bash
1- Git clone:
https://github.com/Krallt-com/Phaser-Electron-Client/tree/main

In the project root directory do following commands:

2- npm i

3- npm i electron-forge/cli -g

3- npm run make
```

After running make you will get out directory

Save the directory for out\make\squirrel.windows\x64\phase3-1.0.0 Setup.exe for windows store setup found in out folder after building. 

In order to run app; In out\phase3-win32-x64, you will find phase3.exe, but before that you should have server running. https://github.com/Krallt-com/Phaser-Electron-Server at port 1444
 
Setting up msix package for windows store

Download msix packager
https://apps.microsoft.com/detail/9N5LW3JBCXKF?hl=en-us&gl=US

And follow steps from this website after step 3
https://www.codiga.io/blog/submit-electron-app-to-microsoft-store/


At this point (Create new Package) you have to share location of setup file i.e.  "phase3-1.0.0 Setup.exe"
Follow the steps as mentioned on website, after complete, you will get msix package that you can publish on windows store 


To change the endoint of server in client application, you have to modify variable urlToCheck in src/index.js
Thankyou



