# mui_dashboard (React + TypeScript + Vite)

## environment

- windows10
- node v22.13.0
- npm  10.9.2

## [React templates](https://mui.com/material-ui/getting-started/templates/)

- [material-ui-vite-ts](https://github.com/mui/material-ui/tree/master/examples/material-ui-vite-ts)

```bash
curl https://codeload.github.com/mui/material-ui/tar.gz/master | tar -xz --strip=2 material-ui-master/examples/material-ui-vite-ts
mv material-ui-vite-ts mui_dashboard
cd mui_dashboard
npm install
```

## pull Dashboard

- [from here](https://github.com/mui/material-ui/tree/master/docs/data/material/getting-started/templates/dashboard)
- remove all *.js files

### install dependency

- [ref](https://github.com/mui/material-ui/tree/master/docs/data/material/getting-started/templates/dashboard)

```bash
npm install @mui/material @emotion/react @emotion/styled
npm install @mui/x-charts
npm install @mui/x-date-pickers
npm install @mui/x-data-grid
npm install @mui/x-tree-view
npm install dayjs
npm install react-router-dom @types/react-router-dom
```

### execute

```bash
npm run dev
```


# React + TypeScript + Vite (without template, obsolate on this project)

## environment

- windows10
- node v22.13.0
- npm  10.9.2
  
```bash
tomi@DESKTOP-GFD5L8A MINGW64 ~/react_ws
$ npm create vite@latest crud_test --template react
Need to install the following packages:
create-vite@6.1.1
Ok to proceed? (y) y

> npx
> create-vite crud_test react

√ Select a framework: » React
√ Select a variant: » TypeScript

Scaffolding project in C:\Users\tomi\react_ws\crud_test...

Done. Now run:

  cd crud_test
  npm install
  npm run dev
```
