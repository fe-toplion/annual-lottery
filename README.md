# annual-lottery
年会抽奖程序，3D 球体抽奖，支持奖品信息配置，参与抽奖人员信息`Excel`导入，抽奖结果`Excel`导出

## 技术

技术：Node + Express + Three.js

后台通过`Express`实现

前端抽奖界面通过`Three.js`实现 3D 抽奖球，引用了`Three.js`的官方 3D 示例

## 功能描述：

1. 可将抽奖结果进行保存实时下载到 excel 中🎉
2. 已抽取人员不在参与抽取，抽中的人员不在现场可以重新抽取🎁
3. 刷新或者关掉服务器，会保存当前已抽取的数据，不会进行数据重置，只有点击界面上的重置按钮，才能重置抽奖数据🧧
4. 每次抽取的奖品数目可配置🎈
5. 抽取完所有奖品后还可以继续抽取特别奖(例如：现在抽取红包，追加的奖品等)，此时默认一次抽取一个🧨


## 安装

```
git clone https://github.com/fe-toplion/annual-lottery.git

cd annual-lottery

# 服务端插件安装
cd server
npm install

# 前端插件安装
cd ../product
npm install

# 打包
npm run build

# 运行
npm run serve

# 开发调试
npm run dev

```
