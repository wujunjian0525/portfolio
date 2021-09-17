# 博客使用说明
## 前提
安装好Hexo框架-[hexo官网](https://hexo.io/zh-cn/docs/)

## 下载
```
git clone https://github.com/wujunjian0525/portfolio.git
```
## 安装
- 安装命令
```
npm install
```
- 修改源码：找到目录node_modules/hexo-asset-image， 打开index.js文件。将24行代码修改为
```javascript
else {
  var endPos = link.length-1;
}
```
## 运行
```
npm run server
```

## 打包
```
npm run build
```