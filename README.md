# Adding ESLint/Prettier & Airbnb's Style Guide To Your Project

**Make sure you `npm init`, or at least have a package.json file before proceeding!**

## Installation
##### You will need _npm/npx_ installed. It will work on Windows, but just needs to be run in a bash shell, like VS Code's integrated terminal. 

1. Clone this repo somewhere on your machine, and _NOT_ in your project's directory.

```
git clone https://github.com/ChenLi0830/eslint-prettier-airbnb style-config
```

2. Navigate to your project directory where you want to include this style configuration.

```
cd myProject
```

3. Run the shell script under **your project's root directory**. 
* For backend project, run
```
~/your-style-config-path/style-config/eslint-prettier-config-backend.sh
```
* For frontend project that uses React, run 
```
~/your-style-config-path/style-config/eslint-prettier-config-frontend.sh
```

4. The shell script added two config files

- .eslintrc.json
- .prettierrc

This script follows this [tutorial](https://blog.echobind.com/integrating-prettier-eslint-airbnb-style-guide-in-vscode-47f07b5d7d6a) by Jeffrey Zhen.
