# ElasticSearch_jd
狂神说 ElasticSearch
# 项目介绍
ElasticSearch入门，利用爬虫技术获取京东信息，放置到es，通过es进行检索
# 开发
1. IDEA 2019
2. SpringBoot
3. VUE
4. ElasticSearch 7.6.1
5. Jsoup
# 运行
1. 启动ElasticSear
2. 启动ElasticSearch-head
3. 运行主启动类EsJdApplication.class
4. 浏览器输入http://localhost:9090/parse/java (要爬取的书籍)(将爬取结果放入es)
5. http://localhost:9090 ，在搜索栏中输入java，就得到结果了，不过要先执行第4步，在es中有相应的东西才能有结果，目前中文不支持(即可以放进es，但得不到搜索结果)
# 参考
[狂神说](https://www.bilibili.com/video/BV17a4y1x7zq) 他公众号有相应资源  
[nodejs安装](https://www.runoob.com/nodejs/nodejs-install-setup.html)  
[cnpm安装](https://blog.csdn.net/wjnf012/article/details/80422313)  
[ElasticSearch](https://mirrors.huaweicloud.com/elasticsearch/?C=N&O=D)  
[logstash](https://mirrors.huaweicloud.com/logstash/?C=N&O=D)  
[kibana](https://mirrors.huaweicloud.com/kibana/?C=N&O=D)  
