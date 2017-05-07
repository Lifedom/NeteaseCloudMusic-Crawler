# Music Reptile
概述：
---------
  一个使用Java实现的爬虫程序，用于爬取网易云音乐上高评论量的音乐。
  
想法来源：
----------
    歌单里的歌听腻了，就想到找一些热门，经典的歌曲换换口味。但单靠人力去曲库中成千上万首歌中寻找歌曲几乎是不可能的事情。
    作为一个学习计算机专业的学生，我自然而然地想到使用爬虫去获取上面的数据。
    
选用技术与实现方式：
-------------------
    使用Java语言，初步打算使用jsoup框架用于解析网页，用Java自带的HTTPCilent库抓取数据，
    将爬取的数据存入mysql数据库中，再通过Spring框架的技术将爬取的信息呈现在web网页上。
    
作者：
------------------
   个人作品

后续计划：
-------------------
   由于我是第一次接触爬虫，对于java的熟练度个人感觉也略有不足，因此打算先进行一段时间的学习，阅读jsoup的文档，尝试写几个爬虫的demo。
 
更新记录：
----------------------
	2017.3.9  完成一个练手程序可获取特定网址中的图片，链接信息。
  	2017.3.24 大致学习完Maven，并使用它构建项目。
	2017.4.2  编写数据模型与网页的解析方法。
	2017.4.10 实现爬虫对于一个歌单中歌曲评论数的爬取。
	2017.4.13 将爬虫改写为多线程。
	2017.4.24 更新一个简单的Spring Boot学习练习代码。
	2017.4.30 更新一个新的Spring Boot Demo。
	2017.5.7  用Spring boot改写项目。