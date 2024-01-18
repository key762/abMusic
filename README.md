# abMusic
针对椒盐音乐(android)和Light Player(ios/android)的Q歌单进行处理(保持歌单顺序),仅需要歌单id即可

# 运行Jar
## 通过接口处理歌单
- http://127.0.0.1:8088/disst?id=歌单id
## Light Player歌单上传
- http://127.0.0.1:8088/upload?id=歌单id&ip=手机IP(接受文件网页的IP)&port=手机PORT(接受文件网页的PORT)
## 获取单个歌曲的flac地址
- http://127.0.0.1:8088/flac?mid=歌曲的songmid

