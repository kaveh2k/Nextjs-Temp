# Next.js-Template

- ### :floppy_disk: This is a [Next.js] ready to code template

- ### Clone this template:

```bash
git clone https://github.com/kaveh2k/Nextjs-Temp.git
```

### :warning: Make sure you already have these extensions on your editor:

- Eslint
- Prettier
- Editorconfig
- Git
- Storybook

### :paperclip: .storybook folder is default Storybook folder, feel free to delete:

# Getting Started

## 1- Install dev dependencies:

```bash
npm install

```

## 2- Initial eslint:

```bash
npm init @eslint/config

```

then add <"prettier"> into .eslintrc.json:

```json
{
  "extends": ["some-other-config-you-use", "prettier"],

  "plugins": ["some-other-config-you-use", "prettier"]
}
```

## 3- Change project name:

```
=> package.json -> "name":"nextjs-temp"
=> package-lock.json -> "name":"nextjs-temp"
```

## 4- Run the development server:

```bash
npm run dev

```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

---

# State-management:

There is no state-management in this template

I prefer to use zustand as state-management:

```bash
npm install zustand

```

### You can also use other state-managements like:

- Redux
- Mobx
- Recoil
- React-query
- XState
- And much more (you can find more on [www.npmjs.com](https://www.npmjs.com/) )

---

# material-ui

Use [mui.com](https://mui.com/material-ui/) to find your materials and learn how to use them.

---

# packages :

```bash

1- npx create-next-app@latest # Next.js

2- npm i --save-dev @types/react #If react didnt install well

3- npm i eslint --save-dev # Eslint

4- npm install --save-dev --save-exact prettier # Config prettier and eslint on ur code

5- touch .prettierrc.json # Create .prettierrc.json file

6- npm install --save-dev eslint-config-prettier # Config prettier and eslint on ur code

7- npm i @emotion/css # Css in js

8- npx storybook init # For UI development

9- npm install --save-dev jest babel-jest @babel/preset-env @babel/preset-react react-test-renderer # Download and config testing system

10- npm install @apollo/client graphql # Config apollo for graphql which is a data query and manipulation language for APIs

11- npm install --save styled-components # Css in js

12- npm install --save-dev babel-plugin-styled-components # Css in js babel plugin

13- npm install @material-ui/core # Material-ui

```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!
