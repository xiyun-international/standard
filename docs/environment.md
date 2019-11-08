# 打造舒适的开发环境

## Chrome 插件
目前最流行，最强大的浏览器，也是前端开发必备的浏览器。下面我们来介绍使用Chrome浏览器的一些小技巧。  

- [沙拉查词](https://chrome.google.com/webstore/detail/cdonnmffkdaoajfknoeeecmchibpmkmg) 必装的插件，划词翻译功能是我目前用过的最舒服的；  
- [fe-helper](https://www.baidufe.com/fehelper) 百度推出的非常强大的前端工具，功能非常的强悍，如 JSON查看、代码美化、代码压缩、图片 Base64、二维码生成器等等；  
- [vue-devtools](https://github.com/vuejs/vue-devtools) 开发 Vue 应用时的辅助工具；  
- [octo-tree](https://github.com/ovity/octotree) 方便你查看 GitHub 项目结构
- [octo-linker](https://github.com/OctoLinker/OctoLinker) 查看 GitHub 文件时可以一键打开引入文件的路径；

## VSCode 快捷键

### 左边栏快捷键，定制化

`cmd + k + s` -> `keybinds.json`

添加以下配置
```json
{
  "key": "cmd+1",
  "command": "workbench.view.explorer"
},
{
  "key": "cmd+2",
  "command": "workbench.view.search"
},
{
  "key": "cmd+3",
  "command": "workbench.view.scm"
},
{
  "key": "cmd+4",
  "command": "workbench.view.debug"
},
{
  "key": "cmd+5",
  "command": "workbench.view.extensions"
},
```

## VSCode 插件
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) 英文单词拼写错误检查插件；这个插件是从 [vue-next](https://github.com/vuejs/vue-next/blob/master/.vscode/settings.json) 项目接触到的，可以有效避免拼写错误等低级错误。
- [Regex Previewer](https://marketplace.visualstudio.com/items?itemName=chrmarti.regex) 正则表达式辅助工具，在写正则表达式时右侧能实时的看到匹配效果。
