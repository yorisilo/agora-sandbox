2021-05-29 03:23:56

# agora-sandbox

# starting
cf.
- [React × Typescript × ESLint × Prettier × VSCodeなSetup 2021](https://zenn.dev/sh090/scraps/3a6fed549d4716)
- [Prettier 入門 ～ESLintとの違いを理解して併用する～ \- Qiita](https://qiita.com/soarflat/items/06377f3b96964964a65d)


``` shell
# npx create-react-app . --template typescript
yarn create react-app . --template typescript
yarn run eslint --init
yarn add -D @typescript-eslint/eslint-plugin @typescript-eslint/parser
npx install-peerdeps --dev eslint-config-airbnb
yarn add -D prettier eslint-config-prettier

# 衝突ルールの確認
(/ º﹃º)/ < npx eslint-config-prettier 'src/**/*.{js,jsx,ts,tsx}'
No rules that are unnecessary or conflict with Prettier were found.
```
