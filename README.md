# React-app
##react技术栈
-react react-router4 redux react-redux

##webpack
```
$ yarn install webpack webpack-dev-server
```
## babel(开发依赖，上线不需要)
```
$ yarn install babel-core babel-loader babel-preset-es2015 babel-preset-stage-0 babel-preset-react css-loader style-loader less less-loader html-webpack-plugin -D
```

## react (生产依赖)
```
$ yarn install react redux react-redux react-router-dom -S
```

## fetch()
```
$ yarn install es6-promise whatwg-fetch -D
```
## express(生产依赖)
```
$ yarn install express -S
```

## scripts
```
"start","webpack-dev-server --port 5000 --open --progress --colors",
"build","webpack -p"
```