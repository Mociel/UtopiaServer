# UtopiaServer
这是一个基于[Radmin](https://www.radmin-vpn.com/)构建的分布联机测试。由于Radmin并不支持MacOS，此方法仅适用于Windows联机。

## [服务器当前状态](https://mociel.pythonanywhere.com/)

# 快速上手

## 作为加入客机

1. 适用于[服务器当前状态](https://mociel.pythonanywhere.com/)已有地址声明的情况下
2. 确保你已经进入小伙伴的Radmin网络连接
3. 进入对应模组包，选择多人模式>直接连接
4. 将声明的地址复制至输入框
5. 若客户端版本，模组，网络无冲突或异常，即可顺利连接

## 作为开服主机

1. 确保你已经进入小伙伴的Radmin网络连接，记下你自己的IP地址（格式如"XX.XXX.XXX.XXX"）
2. 查看上面的[服务器当前状态](https://mociel.pythonanywhere.com/)，确保没有他人作为主机游玩中
3. 在这里选择已有的模组包备份（存档+模组），保证当前游玩的存档为最新状态
4. 启动对应模组包并选择更新的最新存档进入
5. 开启局域网，记下端口号（5位数字，0~65535）
6. 进入[服务器当前状态](https://mociel.pythonanywhere.com/)，声明当前你的主机作为服务器信息："Radmin地址:端口号"
7. 决定结束游玩时，通知服务器内在线玩家后方可关闭，同时关闭[服务器当前状态](https://mociel.pythonanywhere.com/)中的活跃地址
8. 将游玩的世界存档重新备份到这里的原文件夹

## 关于存档备份

+ CurseForge导入的模组包存档地址
默认地址：
```
C:\Users\<用户名>\curseforge\minecraft\Instances\<模组包名>\saves\<存档名>
```
+ 官方启动器下的存档地址
默认地址：(可通过“运行”内键入"%AppData%"快速到达"\Roaming")
```
C:\Users\<用户名>\AppData\Roaming\.minecraft\saves\<存档名>
```
请将这里的存档上传到这里，上传文件夹名称应为："<模组包名/缩写>_<当前日期>_<小时分钟(24小时制)>"

### 备份方式

根据模组包困难程度，我们将尝试三类备份方式。不同模组包的Readme下将会注明备份方式

1. 即更即存，始终保持一份存档。新备份后将无法回档
2. 只保留最新的两份完整备份。新存档备份后删除最老的备份
3. 全备份/筛选备份。保留每次备份/选择性保存特定备份

## 模组

+ CurseForge导入的模组包模组地址
默认地址：
```
C:\Users\<用户名>\curseforge\minecraft\Instances\<模组包名>\mods
```
+ 官方启动器下的模组地址
默认地址：(可通过“运行”内键入"%AppData%"快速到达"\Roaming")
```
C:\Users\<用户名>\AppData\Roaming\.minecraft\mods
```

在连接任何带有模组的服务器前，请确保启动的对应版本至少包含服务器在用的模组，以及使用对应的模组框架启动

模组依赖框架：
+ [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/)
+ [Fabric](https://fabricmc.net/)
+ [NeoForge](https://neoforged.net/)

