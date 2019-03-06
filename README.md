## 1.安装node.js

## 2.配置npm

~~~
npm config set registry https://registry.npm.taobao.org --global
npm config set disturl https://npm.taobao.org/dist --global
~~~

## 3.安装docsify

~~~
npm i docsify-cli -g
~~~

## 4.在git 的 docs-temp仓库下初始化项目

~~~
docsify init ./
~~~

## 5.启动项目

~~~
docsify serve ./
~~~

