# 软件文件布局格式

exe与必要的dll等依赖处于同级目录（如有可能应尽量单文件化）

其他所有文件，新建一个`LuatOS_Downloader_Data`文件夹存放

- LuatOS_Downloader_Data/
  - config.toml : 软件各项配置
  - packs/ : 芯片支持包
  - firmware/ : 芯片的官方固件与demo
  - logs/ : 存放软件日志与芯片调试打印日志
  - temp/ : 临时文件夹，每次启动或关闭软件时都会尝试清空
