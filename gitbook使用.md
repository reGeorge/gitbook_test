##### 安装gitbook
1. 安装NodeJs
    https://nodejs.org/en/download/
2. 安装gitbook
    npm install -g gitbook-cli

##### 开始使用
1. 初始化
    gitbook init

    README.md —— 书籍的介绍写在这个文件里
    SUMMARY.md —— 书籍的目录结构在这里配置

# 目录

* [前言](README.md)
* [第一章](Chapter1/README.md)
  * [第1节：衣](Chapter1/衣.md)
  * [第2节：食](Chapter1/食.md)
  * [第3节：住](Chapter1/住.md)
  * [第4节：行](Chapter1/行.md)
* [第二章](Chapter2/README.md)
* [第三章](Chapter3/README.md)
* [第四章](Chapter4/README.md)

2. 构建文件
    gitbook init

3. 预览
    gitbook serve

4. 构建
    gitbook build [书籍路径] [输出路径]
    gitbook pdf ./ ./mybook.pdf
    gitbook mobi ./ ./mybook.mobi