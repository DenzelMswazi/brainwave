# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

settings.json
{
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.formatOnSave": true,
"editor.codeActionsOnSave": {
"source.fixAll.eslint": "explicit",
"source.addMissingImports": "explicit"
},
"prettier.tabWidth": 2,
"prettier.useTabs": false,
"prettier.semi": true,
"prettier.singleQuote": false,
"prettier.jsxSingleQuote": false,
"prettier.trailingComma": "es5",
"prettier.arrowParens": "always",
"[javascriptreact]": {
"editor.defaultFormatter": "esbenp.prettier-vscode"
},
"[css]": {
"editor.defaultFormatter": "vscode.css-language-features"
},
"[svg]": {
"editor.defaultFormatter": "jock.svg"
}
}
