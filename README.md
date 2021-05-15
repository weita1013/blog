# blog
利用Django框架，html，css，js，jquery，bootstrap，ORM，mysql数据库搭建的一个拥有博客基本功能的前后端不分离web项目，
进行了数据库设计的优化，通过ajax向python后端发送请求，后端利用序列化组件渲染数据，将数据转成json格式，然后通过Django模版语法渲染到前端页面，
在数据安全方面，前端和后端都进行了数据的校验，通过session保存用户登陆状态，通过Django中间件进行全局限制
使用Django中的auth模块快速搭建博客后台，利用PIL模块快速生成验证码通过BytesIO模块临时存储
利用bs4模块组织xss攻击
