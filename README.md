# Scarpy_91porn
my python code
说明：这是一个用scarpy写的爬虫程序，爬取91论坛上原创申请区里面被顶次数大于N次的链接里面的图片。只爬取原创申请区前10页的符合条件的链接。爬取整个申请区需修改pagelink = LinkExtractor(allow=r"fid=19&page=\d$")为pagelink = LinkExtractor(allow=r"fid=19&page=\d+$")
运行前操作：在“Spider91porn2/Spider91porn/spiders”目录下创建Image文件夹，不创建会报错
运行环境：Linux/Python2.7
运行命令：scrapy crawl 91pornSpider
