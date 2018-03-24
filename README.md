# 使用express+multer实现node中的图片上传

在前端中，我们使用ajax来异步上传图片,使用file-input来上传图片，使用formdata对象来处理图片数据，post到服务器中

在node中我们使用multer中间件来对上传路由接口进行处理
[multer文档](https://github.com/expressjs/multer/blob/master/doc/README-zh-cn.md)