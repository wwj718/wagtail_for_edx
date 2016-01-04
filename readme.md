#wagtail for edx
使用wagtail来管理edx的视频(文档)

采用自建视频服务器的话（nginx），需要一个上传管理界面。使用wagtail

wagtail应该返回视频的链接，方法是将/media 指向nginx指向的视频目录

此外wagtail也可以以django app的方式集成到edx中。wagail也可以用于作为edx首页呀

又django 存储层是可编程的，可以控制实际存储的静态文件位置


