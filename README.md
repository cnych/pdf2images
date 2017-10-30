## pdf2images

将PDF转换成图片，利用`PyPDF2`获取PDF对象，将某页数据转换成图片保存即可

> 需要注意的是一般PDF文件较大，如果一次性转换整个PDF文件需要小心内存溢出的问题，我们这里将第一次载入的整个PDF文件保存到内存，避免每次读取的时候都重新载入

### 安装依赖
 ```shell
 pip install -r requirements.txt
 ```

### 执行
```shell
python app.py
```

> 可以根据需要循环或者异步的转换整个PDF文件
