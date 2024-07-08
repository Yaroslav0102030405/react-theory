# react-theory

<h1>встановлення реакт програми</h1> 
1 npx create-react-app . означає у поточному проекті <br/>
2 npm install --save-dev prop-types https://www.npmjs.com/package/prop-types <br/>

2 Урок <br/>
1 Налаштовуємо лінтінг EsLink npm install --save-dev prettier husky lint-staged <br/>
Створюємо 3 файли... <br/>
.huskyrc { "hooks": { "pre-commit": "lint-staged" } } <br/>
.lintstagedrc { "src//*.{json,css,scss,md}": ["prettier --write"], "src//*.{js,jsx,ts,tsx}": ["prettier --write", "eslint --fix"] } <br/>
.prettierrc.json { "printWidth": 80, "tabWidth": 2, "useTabs": false, "semi": true, "singleQuote": true, "trailingComma": "all", "bracketSpacing": true, "jsxBracketSameLine": false, "arrowParens": "avoid", "proseWrap": "always" } <br/>

Налаштовуємо VS Code заходимо в налаштування codeActionOnSave заходимо до setting.json і додаємо "editor.codeActionsOnSave": { "source.fixAll.eslint": true } <br />

Налаштуванння modern-normalize link - https://www.npmjs.com/package/modern-normalize Install $ npm install modern-normalize <br />
Підключаємо файл в папку src - index.js Usage import 'modern-normalize/modern-normalize.css'; <br />

Inline style in React <br />
const styles = { <br />
option: { <br />
display: "block", <br />
width: 40, <br />
margin: 4, <br />
} <br />
} <br />

Додати в свій проект SASS - npm install sass <br />

Loayut and children
