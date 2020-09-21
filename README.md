# ESLint Configured with Airbnb, React, TypeScript & Prettier

## How to install ?

1. Install the configuration

```
npm i -D eslint-config-airbnb-react-typescript-prettier
```

2. Install the peer dependencies of the config

If using **npm >5**

```
npx install-peerdeps --dev eslint-config-airbnb-react-typescript-prettier
```

If using **npm <5**

```
npm info "eslint-config-airbnb@latest" peerDependencies
```

> And then you need to install each peer dependency manually

3. Extends your eslint configuration with this one

```json
{
  "extends": ["eslint-config-airbnb-react-typescript-prettier"]
}
```

4. Don't forget to make your `.prettier` (you can use the one we provide in the repo)
5. Don't forget to also make your own `tsconfig.json` (you can also use the one we provide in the repo)
6. Enjoy using our configuration !
