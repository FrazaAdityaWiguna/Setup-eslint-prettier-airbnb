Setup 2
1. npm i eslint prettier eslint-plugin-prettier eslint-config-prettier --save-dev
2. npx install-peerdeps --dev eslint-config-airbnb
3. Creata file .eslintrc.json
4. isi di file .eslintrc.json
{
  "extends": ["airbnb", "prettier"],
  "plugins": ["prettier"],
  "rules": {
    "prettier/prettier": "error",
    "react/jsx-filename-extension": [1, { "extensions": [".js", ".jsx"] }],
    "no-unused-vars": "warn",
    "no-console": "off",
    "func-names": "off",
    "no-process-exit": "off",
    "object-shorthand": "off",
    "class-methods-use-this": "off",
    "import/no-named-as-default": "off",
    "import/no-named-as-default-member": "off"
  }
}
5. create file .prettierrc
6. isi di file .prettierrc
{
  "singleQuote": true
}
7. npm i styled-component

Source: https://www.youtube.com/watch?v=m2osVgjKeOU

Note: dont use npm audit fix
