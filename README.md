## Install NVM

https://github.com/nvm-sh/nvm

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

## Install Node

nvm install node

## Create React App

npx create-react-app tdd-amplify-react

## Set Up ESLint
https://dev.to/knowankit/setup-eslint-and-prettier-in-react-app-357b

- npm install eslint --save-dev
- npx eslint --init

✔ How would you like to use ESLint? · style
✔ What type of modules does your project use? · esm
✔ Which framework does your project use? · react
✔ Does your project use TypeScript? · No
✔ Where does your code run? · browser
✔ How would you like to define a style for your project? · guide
✔ Which style guide do you want to follow? · airbnb
✔ What format do you want your config file to be in? · JSON
✔ Would you like to install them now? · Yes
✔ Which package manager do you want to use? · npm

## Set Up Prettier
https://dev.to/knowankit/setup-eslint-and-prettier-in-react-app-357b

- npm install eslint-config-prettier eslint-plugin-prettier prettier --save-dev

## Prevent committing credential
- npm install secretlint @secretlint/secretlint-rule-preset-recommend --save-dev
- npx secretlint --init

## Promise linting
- npm install eslint-plugin-promise --save-dev

