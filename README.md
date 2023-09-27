# Nine-colored-deer (Deprecated)

**This app is no longer supported, please wait for the new Nine Colored Deer in the future！**

## Running

Make sure you have the following dependencies installed:

- nodejs `version = 16` (if you manage your nodejs versions with [nvm](https://github.com/nvm-sh/nvm) or [fnm](https://github.com/Schniz/fnm), you can just run `nvm use` or `fnm use` in the repo folder respectively)
- adb

1. Clone repo
2. `npm install`
3. Connect your phone to your computer and make sure it shows up with `adb devices`
4. Forward if you haven't done so already. `adb forward tcp:6000 localfilesystem:/data/local/debugger-socket`
5. `npm start`

tips：use `npm run make` to make a package
