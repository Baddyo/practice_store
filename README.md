# 编程练习代码仓库
> 将学习知识点时写的 Demo 集中存放在此仓库中，便于分类、检索和更新。

## 类别
根据涉及到的技能分支，按照语言特性和框架类型组织目录结构：
- HTML
- CSS
- JavaScript
- TypeScript
- Vue
- ...

## 文件形式
Demo 文件一般以 `.html` 文件承载，便于在线阅读和本地调试。

## 工具

### Browsersync
```shell
Set-ExecutionPolicy -ExecutionPolicy Unrestricted
npm install -g browser-sync
browser-sync start --server --files "*/*.html,*/*.js,*/*.css"
```