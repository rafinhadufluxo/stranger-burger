## Aula 26 [ Dia 05/01/2023]

- v-show use para formularios, com sucesso de envio. Exemplo : Fazendo cadastro 
num formulario de compras, quando finalizado, manda uma mensagem de confirmação;
- component: vincula um dado na pagina solicita, no caso home precisa dos component nav;


obs.: Aulas vistas do Matheus Battisti via youtube.

__________________________________________________________________________________________
arquivo .eslintrc.js
module.exports = {
  root: true,
  env: {
    node: true,
  },
  extends: [
    "plugin:vue/vue3-essential",
    "eslint:recommended",
    "plugin:prettier/recommended",
  ],
  parserOptions: {
    parser: "@babel/eslint-parser",
  },
  rules: {
    "no-console": process.env.NODE_ENV === "production" ? "warn" : "off",
    "no-debugger": process.env.NODE_ENV === "production" ? "warn" : "off",
    "vue/multi-word-component-names": 0,
    "prettier/prettier": [
      "error",
      {
        EndOfLine: "auto",
      },
    ],
  },
};

