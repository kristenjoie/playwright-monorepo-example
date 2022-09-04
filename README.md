# playwright-monorepo-example

This is an example of monorepo with Playwright framework

## 🏗️ Install
```
npm i
```

## 🚀 Run
- For package `@site/backoffice`:
```
npm run test --w=@site/backoffice
```

- For package `@site/client`:
```
npm run test --w=@site/client
```

- For both packages:
```
npm run test --ws
```

## 🤔 Why this ?
The monorepo allows us to share code between different project.  
For example, we can imagine 2 distincts team working on 2 different web application (`@site/backoffice` and `@site/client`) but we want to share some code as api requests, page objects, reporters or everything related to the ci/cd.

