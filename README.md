## Setup this theme
1. Install shopify CLI
```bash
   npm install -g @shopify/cli@latest
```
2. Install node packages
```bash
   npm install
```

3. Run watch tailwind for develop and build for deploy
- Develop
```bash
   npm run tailwind:watch
```

- Deploy
```bash
   npm run tailwind:build
```
3. Run theme and connect to store
```bash
shopify theme dev --store front-end-demo-theme
```