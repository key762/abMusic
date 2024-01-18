# abMusic
针对椒盐音乐(android)和Light Player(ios/android)的Q歌单进行处理(保持歌单顺序),仅需要歌单id即可

# 运行Jar
## 说明
为了不扩大影响,请留言您的机器码,会给出对应文件,classfinal-fatjar-1.2.1.jar可以[点此下载](https://gitee.com/gcl2940397985/akby/releases/download/res/classfinal-fatjar-1.2.1.jar)
```
java -jar classfinal-fatjar-1.2.1.jar -C
```
运行后会打印如下,下边Server code is: 后边的就是您的机器码
```
=========================================================
=                                                       =
=       Java Class Encryption Tool v1.2.1   by Mr.K     =
=                                                       =
=========================================================

Server code is: xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

## 通过接口处理歌单
- http://127.0.0.1:8088/disst?id=歌单id
## Light Player歌单上传
- http://127.0.0.1:8088/upload?id=歌单id&ip=手机IP(接受文件网页的IP)&port=手机PORT(接受文件网页的PORT)
## 获取单个歌曲的flac地址
- http://127.0.0.1:8088/flac?mid=歌曲的songmid

