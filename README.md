# Postman 中文版
最新中文版本：9.12.2  
更新时间：2022-02-06  

## 帮助
[Postman官方文档](https://learning.postman.com/docs)  
不使用联网工作区，可以点开右上角设置图标中的便笺(Scratch Pad)模式  
[**禁用自动更新❗❗❗**](#禁用自动更新)

## 1.下载Postman本体和汉化版app.zip

### [下载](https://github.com/hgztask/Postman-cn_win/releases)

## 2.安装Postman

## 2.安装中文包

1. **下载对应版本的** 
2. **进入**`Postman安装地址/版本/resources`**目录**
   > 桌面找到Postman应用程序右键 -> 打开文件所在位置 再进入`app-*.*.*/resources`  
   > 默认安装地址：`C:/Users/用户名/AppData/Local/Postman`  
   > 示例：`C:/Users/用户名/AppData/Local/Postman/app-8.8.0/resources`  
   > ![resources目录](https://user-images.githubusercontent.com/45023268/125588720-0ba27b65-26cc-47ce-9c1f-8e456797be09.png)
3. 复制`app.zip`到`resources`目录
   > 将`app.zip`解压到当前文件夹 会生成一个`app`目录  
   > 进入`app`目录看到以下图就可以了  
   > ![app目录](https://user-images.githubusercontent.com/45023268/125589699-3435c048-fd90-437a-8d74-35a9923ef4be.png)
4. 重启Postman就可以了

### 操作GIF
![Postman设置为中文](https://user-images.githubusercontent.com/45023268/119171249-e84aa980-ba96-11eb-8c84-28c65c7d0f6e.gif)

## 禁用自动更新❗❗❗
> 这是一项危险操作，将会使你的电脑无法与Postman下载服务器连接，当然这就可以使你的Postman应用程序不再更新  
> 如果想更新请将此解析注释或移除  
> Windows 删除安装目录的update.exe即可

将此解析加入你电脑的主机文件hosts
```
0.0.0.0         dl.pstmn.io
```
**hosts文件在**
> **Windows**：`C:/Windows/System32/drivers/etc/hosts`  



