https://www.electronjs.org/docs/latest/tutorial/tutorial-first-app
https://www.electronjs.org/docs/latest/tutorial/tutorial-packaging

## EXE Packager
`npm install electron-packager -g`
`electron-packager . --platform=win32 --arch=x64 OurCodeWorld`

## MSI Installer
https://www.youtube.com/watch?v=KDVahubc_54
https://ourcodeworld.com/articles/read/927/how-to-create-a-msi-installer-in-windows-for-an-electron-framework-application
`npm install electron-wix-msi --save-dev`
`node build_installer.js`
