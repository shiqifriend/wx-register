# 智慧医疗-医疗挂号小程序

#### 介绍
智慧医疗是一个在线挂号的小程序，旨在搭建一个医疗在线挂号平台，解决日常生活中的“挂号难题”，同时搭载疫苗预约、图文咨询、医师课堂等功能，解决医患之间沟通不便的难题。

技术栈: Vue3.2 + sq-cli + TypeScript + uniapp + vite。


#### 使用说明
1.打开src/manifest.json文件，微信小程序配置里，更改为你自己的 小程序APPID

2.打开src/pages/login-page/index.vue，第37行， 把appid和secret秘钥改为你自己的小程序appid和秘钥

3.在根目录下执行 npm install 安装依赖，成功后， 再执行npm run dev:mp-weixin
