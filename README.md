# React + TypeScript + Vite
Live link of the complete full stack project-https://main--proide.netlify.app/
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are ![Screenshot (36)](https://github.com/user-attachments/assets/cff87c91-e854-42b3-8171-0c0ef4cb2fb7)
available:![Screenshot (37)](https://github.com/user-attachments/assets/08c02d27-b74d-4610-a748-f1c60cd0d730)
![Screenshot (38)](htt![Screenshot (39)](https://github.com/user-attachments/assets/36fe4298-322f-487a-b77f-aefbc1d9314b)
ps://github.com/user-attachments/
![Screenshot (40)](https://github.com/user-attachments/assets/d620d640-f0cc-4ae4-950d-03c8c20fba06)
assets/62cc22f9-978a-4ef8-8d1e-d77f55c7401b)


- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
