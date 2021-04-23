# Hello-Puppeteer
Puppeteer与Cypress均是用于前端E2E测试的一个工具，二者的比较可参考这里：[https://chercher.tech/puppeteer/puppeteer-vs-cypress](https://chercher.tech/puppeteer/puppeteer-vs-cypress)

## Specification

- [Element UI](https://element.eleme.io/#/zh-CN)
- Vue(2.x) + Vuex + Vue Router
- Typescript
- less

## Build Setup

Requires Node.js 6+

## Prepare to run in local environment

- yarn / npm install
- yarn serve / npm run serve
- visit http://localhost:8080/
- npm run cypress / yarn cypress (启动Cypress服务之后，你可以在根目录下看到命名为`cypress`的文件夹，下面存放着很多测试用例的例子)
- 录屏功能: `npm run cy:video`
- Cypress还有一个正在实验的功能就是，根据用户在界面上的点击操作，成成code到你使用的IDE中，不再需要用户自己手写测试用例了。需要添加`"experimentalStudio": true`到`cypress.json`文件中，插件下载：[https://chrome.google.com/webstore/detail/cypress-recorder/glcapdcacdfkokcmicllhcjigeodacab](https://chrome.google.com/webstore/detail/cypress-recorder/glcapdcacdfkokcmicllhcjigeodacab)
## Demo演示
