# Add ESLint to your project

It's recomended to complete this step early on in the project so you don't have to fix lint errors later.

Use [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) which includes plugins for Import, React, and a11y.

```
npx install-peerdeps --dev eslint-config-airbnb
```

Then, create `.eslintrc` file with following content:

```
{
  "plugins": [
    "jsx-a11y"
  ]
}
```



