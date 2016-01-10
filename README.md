

#recompress-apk

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-recompress--apk-green.svg?style=true)](https://android-arsenal.com/details/1/2996)

Compress a signed apk without destroy its original signature.

重新压缩一个已经签名了个apk，而不会破坏apk原始的签名。

#USAGE

> add to `$PATH` 

> recompress-apk weixin638android680.apk 

```
	BEFORE:-rw-r----- 1 ram staff 32M  1  9 11:42 weixin638android680.apk
	AFTER :-rw-r--r-- 1 ram staff 30M  1  9 11:43 weixin638android680.apk
```


#TIPS

压缩后的apk在试用art运行环境的系统上没影响，dalvik上可能会降低运行效率。
 
work perfectly on ART, maybe a little low efficiency on dalvik.

#More

### [Shoturl](https://github.com/hyongbai/shoturl)

A shell that shorten a long url into a very shot one. [bit.ly](http://bit.ly) [t.cn](http://t.cn) ... is supported now.
