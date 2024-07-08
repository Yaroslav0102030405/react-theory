# react-theory

<h1>встановлення реакт програми</h1> 
1 npx create-react-app . означає у поточному проекті <br/>
2 npm install --save-dev prop-types https://www.npmjs.com/package/prop-types

2 Урок
1 Налаштовуємо лінтінг EsLink npm install --save-dev prettier husky lint-staged
Створюємо 3 файли...
.huskyrc { "hooks": { "pre-commit": "lint-staged" } }
.lintstagedrc { "src//*.{json,css,scss,md}": ["prettier --write"], "src//*.{js,jsx,ts,tsx}": ["prettier --write", "eslint --fix"] }
.prettierrc.json
{ 
    "printWidth": 80, 
    "tabWidth": 2, 
    "useTabs": false, 
    "semi": true, 
    "singleQuote": true, 
    "trailingComma": "all", 
    "bracketSpacing": true, 
    "jsxBracketSameLine": false, 
    "arrowParens": "avoid", 
    "proseWrap": "always" 
}
