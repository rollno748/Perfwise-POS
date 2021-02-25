#Packaging instructions
- Import Electron Forge to your app folder
    ```npx @electron-forge/cli import```
- Create a distributable
    ```npm run make```
- Electron-forge creates the out folder where your package will be located
    ```// Example for MacOS
    out/
    ├── out/make/zip/darwin/x64/my-electron-app-darwin-x64-1.0.0.zip
    ├── ...
    └── out/my-electron-app-darwin-x64/my-electron-app.app/Contents/MacOS/my-electron-app```


Thanks 


#References:
https://www.electronjs.org/docs/tutorial/quick-start#create-a-basic-application