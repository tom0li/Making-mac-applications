# Making-mac-applications
Making mac applications
## 准备图标
1. 需要png图片
2. 设置ico 为icon_128x128@2x
sips -z 256 256 BurpSuite.png --out icons.iconset/icon_128x128@2x.png
3. 转icns格式
iconutil -c icns icons.iconset -o BurpSuite.icns

## Create程序
搜索 Automator 并启动, 选择应用程序

搜索shell、写入、运行、保存

## 替换图标
显示程序简介，复制

