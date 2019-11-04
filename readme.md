

react設定 history
```shell script
mkdir react-app 
cd react-app
yarn init
yarn add react react-dom
yarn add --dev @babel/core @babel/preset-env @babel/p
yarn add --dev @babel/core @babel/preset-env @babel/preset-react babel-loader
touch .babelrc
yarn add --dev webpack webpack-cli webpack-dev-server
touch webpack.config.js
```

vue.js設定 history
```shell script
mkdir vue-app
cd vue-app
yarn init
yarn add vue
yarn add -D @babel/core @babel/preset-env babel-loader vue-loader vue-template-compiler webpack webpack-cli webpack-dev-server
yarn add vue-custom-element
mkdir src
touch index.js App.vue
```

yarnでのプロセスをkillする場合
```shell script
ps aux | grep yarn | grep -v grep | awk '{ print "kill -9", $2 }' | sh
```