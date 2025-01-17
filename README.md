# ESLint/Prettier & Airbnb's Style Guide for non React Apps
Forked and changed to facilitate usage in non-react ES6 apps where the airbnb-base ruleset is wanted instead of the react ruleset. 

**Make sure you `npm init`, or at least have a _package.json_ file before proceeding!**

## Installation
##### You will need _npm/npx_ installed. It will work on Windows, but just needs to be run in a bash shell, like VS Code's integrated terminal. 

1. Clone this repo somewhere on your machine, preferably in your home directory (~/), and _NOT_ in your app's directory.

```
cd
git clone https://github.com/EliantenHolder/eslint-prettier-airbnb-base style-config
```

2. Navigate to your app directory where you want to include this style configuration.

```
cd myApp
```

3. Run the shell script inside your app's root directory. (_The example below assumes you cloned this repo inside your home directory_)

```
~/style-config/eslint-prettier-config.sh
```

4. The shell script added two config files

- .eslintrc.json
- .prettierrc

This script loosely follows this [tutorial](https://blog.echobind.com/integrating-prettier-eslint-airbnb-style-guide-in-vscode-47f07b5d7d6a) by Jeffrey Zhen.
