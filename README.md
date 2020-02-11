# native-shopify
Taking a look at React Natives built in components. A mobile app similar to Amazons wishlist.

## Installation && Usage

Use the package manager [npm](https://www.npmjs.com/get-npm) to install native-shopify. It is installed with [Node.js](https://nodejs.org/en/)
- - - -
Make sure react-native-cli is installed globally on your machine.
* On Mac run
```bash
sudo npm i -g react-native-cli
```
- - - -
* On Windows
* I first had to install [chocolatey](https://chocolatey.org/) to run certain commands through the admin shell.

      
Run this command through the Admin Shell to install chocolatey
  
 ```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

run this to see if it installed correctly

```bash
choco
```

  * After Chocolatey is installed run this command in an Admin Shell as instructed in [React Natives Documentation](https://facebook.github.io/react-native/docs/getting-started)
```bash
choco install -y nodejs.install python2 jdk8
```
  * For addition information about adding Android studios SDK to the PATH as an Eviromental Variable & Adding the SDKs platform-tools to the PATH as an Enviromental variable.
    * Click this link [React Native Getting Started](https://facebook.github.io/react-native/docs/getting-started)
- - - -
```bash
git init
```
```bash
git clone https://github.com/johnbroaddusivccv/native-shopify.git
```
```bash
cd native-shopify
```
```bash
cd shoppinglist
```
```bash
npm install
```

## In Addition
Depending on your operating system. 
* You can use this via Emulation one of a few ways.
  * On Mac download Xcode and follow the Installation Wizard once complete run..
```bash
react-native run-ios
```
  * On Windows download Android Studios and follow the Installation Wizard once complete run..
```bash
react-native run-android
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
