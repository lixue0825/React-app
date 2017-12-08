#  React-app
## react技术栈
-react react-router4 redux react-redux

## 安装前需要初始化package.json(用yarn安装，默认是开发依赖，如果生产依赖 -dev即可)
```
$ yarn init -y
```
## webpack(webpack 打包  webpack-dev-server 起服务 )
```
$ yarn add webpack webpack-dev-server
```
## babel(开发依赖，上线不需要)
```
$ yarn add babel-core babel-loader babel-preset-es2015 babel-preset-stage-0 babel-preset-react css-loader style-loader less less-loader html-webpack-plugin -dev
```

## react (生产依赖)
```
$ yarn add react redux react-redux react-router-dom react-dom
```

## fetch(获取数据，基于promise， （es6-promise 如果浏览器不兼容promise）， （whatwg-fetch 如果fetch不兼容，就会自动转为ajax）)
```
$ yarn add es6-promise whatwg-fetch -dev
```
## express(生产依赖)
```
$ yarn add express
```

## scripts(start:本地开发，  build：   --port 5000：如果需要改端口号，默认为8080)
```
"start","webpack-dev-server  --open --progress --colors",
"build","webpack -p"
```