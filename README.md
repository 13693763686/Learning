# bilibili
* bilibili视频及UP主信息爬取
* 信息爬取通过python的requests库，信息提取主要通过re模块，信息转入excel通过pandas,输入数据库通过psycopg2与PostgreSQL交互
* 信息的爬取不是通过对html标签内容的提取，而是通过json格式转换成的python字典进行提取.
* 信息在处理过程中均转化为字符串方便读入excel文件
* crontab 文件考虑到业务需要,均定时为每天早上的5:00和每周一的早上5:00,此时各种数据应该是相对静态的
* bilibili.py是将信息提取并且输出到excel文件中去
* todatabase.py是将信息通过嵌入sql与PostgreSQL交互,输入到数据库中,数据库内创建了一个数据库和一个用户,两张表为Video和Up_Info,分别记录视频相关信息和Up主相关信息
* url.txt是将待爬取的url整理到一起,便于python直接读取然后循环抓取
* backup.txt是crontab文件的备份,ubuntu操作系统下
* bilibili.xlsx 存放相应的excel数据
* video.png 是数据库视频信息的相关截图,主键为aid,外键为up_id
* up_info.png是数据库UP主信息的相关信息，主键为Up_id
* python代码中也有详细注释，尽管可能不符合python规范

## 利用ｄｏｃｋｅｒ部署微服务未成功
* requirements.txt 用于存放该爬取程序的python依赖包
* Dockerfile 是用于利用docker自动化创建一个映像，但因为依赖无法安装，PostgreSQL无法安装而失败．
