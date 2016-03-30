# communication-between-ionic-apps
这是一个演示如何在ionic apps中通信的例子。

## 使用到的命令行

```bash
#安装inoic和cordova
npm i -g ionic cordova

#创建ionic app：handler 和 sender
ionic start handler tabs
ionic start sender tabs

#在handler中安装plugin：URL Scheme
ionic plugin add cordova-plugin-customurlscheme --variable URL_SCHEME=handler

#在sender中安装plugin：inappbrowser
ionic plugin add cordova-plugin-inappbrowser
```
