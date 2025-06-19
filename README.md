## wxy-OES内核测试项目

### 使用方法:
### 手动
在armbian 根目录创建update目录<br>
下载内核文件解压上传到update目录<br>
执行命令 cd /update && armbian-install<br>
### 自动
cd / && mkdir /update && cd /update wget https://github.com/2602575766/kernel/releases/download/kernel_stable/6.1.141.tar.gz && tar -zxvf 6.1.141.tar.gz && armbian-install

## License

The kernel © OPHUB is licensed under [GPL-2.0](https://github.com/ophub/kernel/blob/main/LICENSE)
