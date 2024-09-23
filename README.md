# go-1
go简单的通用后台管理项目
技术栈:  gin+gorm+swagger+redis+jwt+base64Captcha+mysql+yaml+javasprit+vue2+elementui ，
前后端完全分离的方式开发。

项目介绍 ：用户信息，角色信息，菜单信息，部门信息，岗位信息，操作日志，登录日志，个人信息。
根据实现了用户的登录和jwt-go的认证还有base64Captcha的验证码认证,利用element实现了图像界面设计
根据用户权限，展示不同界面和选项和权限认证。

项目亮点：利用jwt-go的认证实现用户的登录注册 ，实现了用户头像和坐标上传 ，base64Captcha的验证码认证
