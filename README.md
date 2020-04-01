# prettier-vscode-test

Testing detection of Prettier 2 in prettier-vscode extension

## Steps to test

- Clone this repo, and open it in VSCode
- Install [prettier-vscode extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) v3.20.0
- Run `yarn` to install dependencies
- Open [index.js](./index.js), and add trailingComma at the end of array
- Notice that prettier-vscode extension removes the trailingComma on Save

<img src="./prettier-vscode-removes-trailingComma.gif" />
