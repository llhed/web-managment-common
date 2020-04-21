## Web管理端通用模板

### 写在前面的---致敬潘大
汲取开源力量，致敬PanJiaChen大神.vue-element-admin 是一个后台前端解决方案，它基于 vue 和 element-ui实现。它使用了最新的前端技术栈，内置了 i18 国际化解决方案，动态路由，权限验证，提炼了典型的业务模型，提供了丰富的功能组件，它可以帮助你快速搭建企业级中后台产品原型。

在阅读源码及相关的实践中发现，vue-element-admin 版本在快速构建项目前期前端脚手架时，多余的内容较多过于繁琐，儿template版本过于简单。针对上述情况，并结合公司实际，整理了本版本。

### 主要技术栈
>vue 2.6.10  
>element-ui 2.13.0  
>axios 0.18.1  
>eslint 5.15.3 

### 安装
```
# 克隆项目
git clone http://10.164.194.139:18080/limeng/web-management-common.git

# 进入项目目录
cd web-management-common

# 安装依赖
npm install

# 建议不要用 cnpm 安装 会有各种诡异的bug 可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 本地开发 启动项目
npm run dev
``` 


