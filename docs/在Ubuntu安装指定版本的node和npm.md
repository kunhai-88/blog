# 在Ubuntu安装指定版本的node和npm
1. 从[node的淘宝的镜像](https://npm.taobao.org/mirrors/node/v10.13.0/node-v10.13.0-linux-x64.tar.gz)下载对应的node安装包。(可以使用wget下载)
2. 解压
  ```
  tar -xvf node-v10.13.0-linux-x64.tar.gz
  ```
3. 拷贝目录下的bin到user的bin目录下
```
cd node-v10.13.0-linux-x64/bin
cp node /usr/bin
```
node安装成功
4.使用node-v10.13.0-linux-x64/lib/node_modules/npm/下的npm-cli.js 安装npm
```
cd node-v10.13.0-linux-x64/lib/node_modules/npm/
./npm-cli.js install -g npm
```