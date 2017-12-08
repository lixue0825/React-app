#  React-app
## react技术栈
-react react-router4 redux react-redux
## react(用yarn安装，默认是开发依赖，如果生产依赖 -dev即可)
```
$ yarn init
```
## webpack
```
$ yarn add webpack webpack-dev-server
```
## babel(开发依赖，上线不需要)
```
$ yarn add babel-core babel-loader babel-preset-es2015 babel-preset-stage-0 babel-preset-react css-loader style-loader less less-loader html-webpack-plugin -dev
```

## react (生产依赖)
```
$ yarn add react redux react-redux react-router-dom
```

## fetch()
```
$ yarn add es6-promise whatwg-fetch -dev
```
## express(生产依赖)
```
$ yarn add express
```

## scripts
```
"start","webpack-dev-server --port 5000 --open --progress --colors",
"build","webpack -p"
```