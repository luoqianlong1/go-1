# go-1
go简单的通用后台管理项目
技术栈:  gin+gorm+swagger+redis+jwt+base64Captcha+mysql+yaml+javasprit+vue2+elementui ，
利用gin和gorm编辑简单的通用后台管理系统

项目介绍 ：用户信息，角色信息，菜单信息，部门信息，岗位信息，操作日志，登录日志，个人信息。
根据实现了用户的登录和jwt-go的认证还有base64Captcha的验证码认证,利用element实现了图像界面设计
根据用户权限，展示不同界面和选项和权限认证。

项目亮点：利用jwt-go的认证实现用户的登录注册 ，实现了用户头像和坐标上传 ，base64Captcha的验证码认证
效果展示 这是用户登录界面 
![image](https://github.com/user-attachments/assets/0af383eb-1ae9-4e5a-b08e-ecfff4b70f49)
这是权限管理可以点击右边进行不同的权限管理
![image](https://github.com/user-attachments/assets/c0c65928-cf00-49f3-b44f-2000d61de7b0)
