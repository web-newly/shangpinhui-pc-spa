# day01：

## 1.Home模块组件拆分

--先把静态页面完成

--拆分出静态组件

--获取服务器的数据

--动态业务

## 2.三级联动组件完成

--由于三级联动，在home，search，detail都有，所以把三级联动注册为全局组件。

好处：只需要注册一次，就可以在项目任意地方使用

## 3.axios二次封装

--为什么需要进行二次封装axios：请求拦截器，响应拦截器，可以在发送请求之前处理一些业务逻辑，在接到数据之前进行业务逻辑处理

--在项目当中经常api文件夹放【axios发送请求的逻辑】

## 4.nprogress进度条的使用

--调用nprogress的start方法：进度条开始

--调用nprogress的done方法：进度条结束
