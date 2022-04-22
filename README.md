# Introduction

This boilerplate is targeted towards large, serious projects and assumes you are somewhat familiar with Webpack and `weex-loader`. 

## Quickstart

To use this template, scaffold a project with [weexpack v1.1.1+](https://github.com/weexteam/weex-pack).

``` bash
$ npm install -g weex-toolkit
$ weex create my-project # default will create the webpack template
$ cd my-project && npm start
```

## How to use less/sass/pug

Take `sass` for example:

```
$ npm i node-sass sass-loader --save
```

Then, you just need to change the `style` tag as: `<style lang="sass"><style>`.

## How to create your own template

See [How-to-create-your-own-template](https://github.com/weex-templates/How-to-create-your-own-template).

## 错误解决办法

1. [weex build android 时无法设置 outputFile 的问题](https://blog.csdn.net/fenghuibian/article/details/86633783)
2. [AndroidStudio3.0 注解报错Annotation processors must be explicitly declared now.](https://blog.csdn.net/donkor_/article/details/79020482)
3. [weex build android 时出现 Annotation processors must be explicitly declared now 的问题](https://blog.csdn.net/fenghuibian/article/details/86634828)
4. 无法加载 com.alibaba:fastjson:1.1.27-android 依赖：将项目根目录 .m2 解压放到 `C:\Users\xxx\.m2`
