# typecho-theme-next

简洁大方的 Hexo 主题 [Next.Mist](https://github.com/iissnan/hexo-theme-next) 的typecho移植版。



Fork 自 [zgq354/typecho-theme-next](https://github.com/zgq354/typecho-theme-next) ，主要是根据我使用中遇到的情况做了一些调整。



fork源版本 - 修改前：[预览](http://blog.izgq.net/)

此fork版本 - 修改后：[预览](https://heary.cn)



NexT.Pisces传送门：[NexT.Pisces](https://github.com/newraina/typecho-theme-NexTPisces)



## 1  修改说明

### 1.1  可读性改进

- 加深字体颜色，提高页面视觉对比度；

### 1.2  美观性改进

- 放大了页首site-title及item的大小（字体、行高、margin等整体调整），改善了选中交互效果；
- 启用了首页文章篇目间分割线，调整了长度及上下margin等参数；
- 配色微调（灰度）；


### 1.3  性能改进

- 取消对Google Font的调用，避免因境内网络问题导致加载超时，大幅提高了页面打开速度；

### 1.4  安全性改进

- 修改了Gravatar调用链接，现采用官方https源，速度稳定且加密，与全站https兼容；





## 2  使用方法

1. 点击 download zip 下载最新源码，解压，将其中文件夹重命名为 next 并上传至博客的 /usr/themes 目录下
2. 在Typecho后台点击启用
3. 新建分类页，缩略名为 categories ，自定义模板选择 categories 
4. 新建归档页，缩略名为 archive ，自定义模板选择 archive
5. 新建标签页，缩略名为 tags ，自定义模板选择 tags
6. 前往外观设置设置头像，昵称等等



## 3  License

Open sourced under the MIT license.
