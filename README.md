# Hello-Puppeteer
Puppeteer与Cypress均是用于前端E2E测试的一个工具，二者的比较可参考这里：[https://chercher.tech/puppeteer/puppeteer-vs-cypress](https://chercher.tech/puppeteer/puppeteer-vs-cypress)
- Cypress相比较Puppeteer而言，对用户更加友好
- 近5年的下载量显示，使用Cypress的人越来越多

## Specification

- [Element UI](https://element.eleme.io/#/zh-CN)
- Vue(2.x) + Vuex + Vue Router
- Typescript
- less

## Build Setup

Requires Node.js 6+

## Prepare to run in local environment

- env PUPPETEER_SKIP_CHROMIUM_DOWNLOAD=true npm i puppeteer –D (这种方式是为了在安装过程中不下载`Chormium`，因为下载`Chormium`的过程非常慢，甚至会导致失败)
- Cypress还有一个正在实验的功能就是，根据用户在界面上的点击操作，成成code到你使用的IDE中，不再需要用户自己手写测试用例了。需要添加`"experimentalStudio": true`到`cypress.json`文件中，插件下载：[https://chrome.google.com/webstore/detail/cypress-recorder/glcapdcacdfkokcmicllhcjigeodacab](https://chrome.google.com/webstore/detail/cypress-recorder/glcapdcacdfkokcmicllhcjigeodacab)

## Demo演示


