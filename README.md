**毕业设计所有选题地址： https://github.com/Good-Night-Unicorn?tab=repositories**

**完整代码收费可以加QQ：3042127848 咨询接毕业设计论文**

**作者QQ：3042127848 备用q：2777345948 (支持修改、部署调试、支持代做毕设)**

**接网站建设、小程序、H5、APP、各种系统等**

**选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt都可以做**
**详细视频演示**

## 基于SSM+Vue的音乐播放器小程序+LW(源码+数据库)

## 一、系统介绍
本系统分为用户和管理员两个角色，用户的操作主要为微信端，管理员的操作为服务端。用户在微信端可以根据不同的分类浏览歌曲，可以播放、收藏和评论，办理会员和管理收藏信息等；管理员可以管理歌曲信息、用户信息、会员优惠信息以及会员办理和会员信息等。用户和管理员的功能相互串连形成完整的基于微信小程序的音乐播放器。
根据用户和管理员的功能可以分为微信端和服务端两个界面，在微信端中主要的功能为：
（1）歌曲信息功能，根据不同的分类进行歌曲的展示；
（2）查询功能，用户可以根据不同的字段来进行特定歌曲的搜索，本功能是一个系统最基本的功能；
（3）评论功能，在歌曲的详情里可以直接评论；
（4）用户管理功能，包括注册用户和对用户资料的信息；
（5）会员优惠信息功能，可以查看管理员发布的会员优惠；
（6）会员办理功能，可以购买会员卡成为会员享受优惠；
（7）收藏管理功能，可以管理收藏记录。
本系统的管理员服务端功能包括：
（1）歌曲信息管理功能，对歌曲进行上传、删除、编辑；
（2）个人中心管理功能，对管理员账号、密码进行管理；
（3）会员优惠管理功能，对会员优惠进行发布和管理；
（4）歌曲分类信息管理功能，可以管理分类信息；
（5）会员办理管理功能，包括查询会员办理信息和审核会员办理信息；
（6）会员信息管理功能，可以管理会员信息；
（7）用户管理功能，查询和管理用户的信息。
本系统的服务端功能模块结构图如下图3.2所示：
## 二、所用技术

后端技术栈：

- SpringMvc
- mybatis
- mysql
- shiro


前端技术栈：
- Vue
- layui
- axios
- bootstrap
- uniapp
- 小程序

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK 1.8, Mysql5.7及以上, Maven3.6, HBuilder

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面演示
![图片](https://github.com/user-attachments/assets/b99a2b5d-e30f-4c5b-9634-71a831f85c1d)
![图片](https://github.com/user-attachments/assets/85d59eb8-5f33-4e2d-a11d-41c6d9e8e32c)
![图片](https://github.com/user-attachments/assets/5199aa5a-7c6c-4f8c-a26d-a37e1b8ac029)
![图片](https://github.com/user-attachments/assets/f37aecf9-5646-4155-9547-c8cefb3cebeb)
![图片](https://github.com/user-attachments/assets/e9d019c0-4417-4b77-bb89-77fcdbee5ab7)
![图片](https://github.com/user-attachments/assets/f156f29d-5584-4310-b782-ed60a42cb565)
![图片](https://github.com/user-attachments/assets/4550dc48-104b-4dc1-9011-938edad55a98)
![图片](https://github.com/user-attachments/assets/f6fe87d4-1f0a-4aa2-9ce2-280cc3069c8c)
![图片](https://github.com/user-attachments/assets/b59d2cc3-8bab-4583-96a9-6a595b056d77)

## 五、浏览地址

后台访问地址：http://localhost:8097
- 管理员账号/密码：sysadmin/123456
- 超级管理员账号/密码：admin/admin123

app端用户名密码：
lilong/123456

## 六、部署教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件；
2. 使用IDEA/Eclipse导入Hospital-register项目，若为maven项目请选择maven，等待依赖下载完成；
3. 进入src/main/resources修改application.yml里面的profile文件路径配置和application-druid.yml的数据库配置
4. 启动项目后端项目
5. hbuilder打开Hospital-register-wx项目，修改manifest.json的微信小程序配置，点击运行到小程序模拟器
6. 执行运行后会跳转到微信小程序开发工具
