# Making-applications
## nmap-silent-installation
nmap silent installation on windows

### Step 0  
Download nmap.exe(SFX file)

### Step 1  
run nmap.exe in cmd and the nmap directory will be extracted.

### Step 2  
cd nmap run nmap.exe

### version
nmap 7.91
winpcap 4.13

### Refer
https://www.lz1y.cn/2019/04/30/Windows%E4%B8%8B%E9%9D%99%E9%BB%98%E5%AE%89%E8%A3%85%E4%BD%BF%E7%94%A8nmap/


## Making mac applications
## 准备图标
1. 需要png图片
2. 设置ico 为icon_128x128@2x
```sips -z 256 256 BurpSuite.png --out icons.iconset/icon_128x128@2x.png```
3. 转icns格式
```iconutil -c icns icons.iconset -o BurpSuite.icns```

## Create程序
搜索 Automator 并启动, 选择应用程序

搜索shell、写入、运行、保存
![搜索shell、写入、运行、保存](https://raw.githubusercontent.com/tom0li/Making-mac-applications/master/15815053716918.jpg)

## 替换图标
显示程序简介，复制

