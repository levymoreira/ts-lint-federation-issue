# TS-Loader - Webpack Federation - Issue

Demo project.  

## How to run
```
yarn # or npm install
yarn start # or npm start
```

## Behavior
Expected:  
Page loading with simple text showing the app name.
Current:
Webpack error that only happens if usin ts-loader
```
Uncaught (in promise) Error: Shared module is not available for eager consumption: webpack/sharing/consume/default/react/react
```