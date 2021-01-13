# react-ts-electron-template
My react-typescript-electron project template

## Build Directories
* **build/ui** : react webpack build files
* **build/app** : electron build files

## Scripts

* **build** : react & electron build project
* **develop** : start webpack-dev-server & electron
* **lint** : eslint rule check
* **lint-fix** : modify the code to eslint rules

## Config

`scripts/config.js`

* **src** : source code directory path
* **out** : build result directory path
* **assets** : assets directory path
* **public** : public directory path
* **useLint** : if useLint is true, Check the eslint rules
* **useAnalyzer** : if useAnalyzer is true, Visualize the capacity of the bundle
* **showLintError** : if showLintError is true, Show errors in eslint
* **`devServer`**
  * **host** : development server host
  * **port** : development server port
* **`analyzer`**
  * **host** : analyzer page server host
  * **port** : analyzer page server port
