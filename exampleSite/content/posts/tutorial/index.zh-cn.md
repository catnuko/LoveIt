---
title: "码农头秃导航"
date: 2023-01-15T15:39:36+08:00
lastmod:  2023-01-15T15:39:36+08:00
draft: false
images: ["/Apple-Devices-Preview.png"]
author: "catnuko"
authorLink: "https://github.com/catnuko"
description: "本页面收录经过精挑细选的优质开源免费的书籍或教程（收费的坚决不收录），包括不限于Vue3，React，Vite，Svelte，后端开发Golang，Rust，Java，C++。听说收藏就等于学习了😉"

lightgallery: true
tags: ["installation", "configuration"]
categories: ["documentation"]
math:
  enable: true
---
<!--more-->
文档纯手工打造，如有链接错误、失效、新增链接的情况，可联系作者更新。实时更新，可时刻关注。
## 前端 {#font-end}
前端不只是Vue等前端框架，也包括开发工具，打包工具，Css样式，Typescript或者Flow等类型注释。
### 框架

#### [Vue3](https://cn.vuejs.org/)
尤雨溪大佬熬夜开发的前端框架，其开箱即用的便利性，丰富的中文文档降低了国内大部分前端工
程师的上手难度。
1. [Vue3中文文档](https://cn.vuejs.org/guide/introduction.html) 由国内Vue爱好者搭建的教程，有教程，示例，演练场等，非常适合在线学习。
2. [Vue3生态](https://vue3js.cn/) 一些链接，包括文档，官方生态（Vue Cli，Vue Router等），Vue3组件库，基于Vue3的开源项目，基于Vue3的优秀实战项目，保证从入门到精通。
3. [awesome-vue ![stars](https://img.shields.io/github/stars/vuejs/awesome-vue?style=social)](https://github.com/vuejs/awesome-vue) Vue生态，包括Vue3
4. [awesome-vue-3 ![stars](https://img.shields.io/github/stars/vuesomedev/awesome-vue-3?style=social)](https://github.com/vuesomedev/awesome-vue-3) Vue3生态
#### [React](https://reactjs.org/){#font-end-react}
由FaceBook开发，用户量和下载量全球第一的前端框架，其设计理念给无数开发者打开了新思路。
1. [React中文官网](https://react.docschina.org/) 中文官方网站
2. [React中文官网的文档](https://react.docschina.org/docs/getting-started.html) 中文官方网站中的文档
3. [awesome-react ![stars](https://img.shields.io/github/stars/enaqx/awesome-react?style=social)](https://github.com/enaqx/awesome-react) React生态
#### [React Native](https://reactnative.dev/){#font-end-react-native}
用React开发移动端？不过听说有个Flutter也很厉害。
1. [React Native中文官网](https://www.reactnative.cn/) 中文官方网站
2. [React Native中文官网的文档](https://www.reactnative.cn/docs/getting-started) 中文官方网站中的文档
3. [awesome-react-native ![stars](https://img.shields.io/github/stars/jondot/awesome-react-native?style=social)](https://github.com/jondot/awesome-react-native) React Native 生态
#### [Svelte](https://svelte.dev/){#font-end-svelte}
emmm，号称无框架运行时的前端框架，目前用户较少，适合玩玩，不适合在生产中使用，文档示例较少，这就意味着坑较多，头铁者也要三思。
1. [Svelte中文官网](https://www.sveltejs.cn/) 中文官方网站，英文网站国内访问慢，建议国内用户访问中文官网。
2. [Svelte中文官网的文档](https://www.sveltejs.cn/tutorial/basics) 中文官方网站中的文档

#### [Typescript](https://www.typescriptlang.org/zh/)
1. [TypeScript 入门教程](https://ts.xcatliu.com/) 从 JavaScript 程序员的角度总结思考，循序渐进的理解 TypeScript，中文。
2. [Webpack TypeScript](https://webpack.docschina.org/guides/typescript/) webpack官网关于Typescript的配置
3. [Vite TypeScript](https://cn.vitejs.dev/guide/features.html#typescript) Vite官网关于Typescript的配置
4. [打造TypeScript的Visual Studio Code开发环境](https://zhuanlan.zhihu.com/p/21611724) 知乎文章，关于vscode配置typescript的
5. [TSDoc](https://tsdoc.org/) 用于给TypeScript代码生成文档，适用于TypeScript开发的库

#### [Flow](https://flow.org/)
1. [Flow文档](https://flow.org/en/docs/) Flow英文文档
2. [TypeScript vs Flow](https://juejin.cn/post/7032115620569153566) 作者主要探讨哪个更适合React项目？

#### [Jest](https://www.jestjs.cn/)
1. [Jest文档](https://www.jestjs.cn/docs/getting-started) Jest中文网文档


### 生成文档
1. [TSDoc](https://tsdoc.org/) 用于给TypeScript代码生成文档，适用于TypeScript开发的库
2. [JsDoc](https://jsdoc.app/) 用于给JavaScript代码生成文档
3. [storybook](https://storybook.js.org/) 用于给Vue，React等组件生成文档，十分方便

### 开发工具
#### [vscode](https://code.visualstudio.com/){#font-end-vscode}
人生苦短，少折腾点，强烈推荐使用vscode开发，别的就不推荐了。编辑器由微软开发，有丰富插件扩展，支持各种前端开发，git使用简单便利，同时支持golang，rust（深入调试请使用Clion），C，C++等开发，体验不错。

### 打包工具
#### [Vite](https://cn.vitejs.dev/)
1. [Vite文档](https://cn.vitejs.dev/guide/) Vite中文文档

#### [Webpack](https://webpack.docschina.org/)
1. [Webpack文档](https://webpack.docschina.org/concepts/) 中文官方网站中的文档

### 自动部署

#### [GitHub Actions](https://docs.github.com/zh/actions/quickstart)
很强大，相当于在github提供的docker容器内进行各项操作，主要是**全部免费！！**，可以和git钩子结合，实现提交代码后自动打包部署。
1. [github action demo](https://github.com/catnuko/book_reader/blob/main/.github/workflows/main.yml) 前端常用的打包，想nginx中传输文件
2. [如何评价 GitHub Actions？](https://www.zhihu.com/question/306195033) 知乎提问，答案干货满满

#### node脚本
如果不想编写github action，也可使用node脚本实现自动部署。

贡献一段自用的脚本，利用win10自带的ssh和scp命令实现自动打包，想服务器加密传输文件，支持利用公钥免授权。部署需要将本机的***公钥***拷贝到目标服务器的C:\Users\Administrator\.ssh\authorized_keys文件里。
```js
var spawn = require("cross-spawn");
const REMOTE_WINDOWS = "Administrator@150.158.103.75";
const REMOTE_DIR = "C:\\Users\\Administrator\\Desktop\\npm-doc\\nginx-1.20.2\\html\\storybook-static";
const DIST_DIR = "F:\\code\\zhonghaida\\ht-utils\\storybook-static";
function run(command, args) {
	return new Promise((resolve, reject) => {
		var workerProcess = spawn(command, args, { env: process.env });
		workerProcess.stdout.pipe(process.stdout);
		workerProcess.stderr.pipe(process.stderr);
		workerProcess.on("close", function (code) {
			if (code !== 0) {
				reject(code);
				return;
			}
			resolve();
		});
	}).catch((e) => {
		console.error(e);
	});
}
async function main() {
	//构建项目
	await run("yarn build-doc");
	//删除目标文件夹
	await run("ssh", [REMOTE_WINDOWS, "rd/s/q", REMOTE_DIR]);
	//创建目标文件夹
	await run("ssh", [REMOTE_WINDOWS, "mkdir", REMOTE_DIR]);
	//复制dist文件夹的内容到目标文件夹
	await run("scp", ["-v", "-r", DIST_DIR + "\\*", REMOTE_WINDOWS + ":\\" + REMOTE_DIR]);
}
main();
```

#### [jenkins](https://www.jenkins.io/)
1. [jenkins中文网](http://www.jenkins.org.cn/)
2. [Jenkins详细教程](https://www.jianshu.com/p/5f671aca2b5a) 简书教程，比较详细


## 后端{#back-end}