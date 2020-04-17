---
title: 欢迎来到PKUer的Minecraft服务器！
---
> 请确保自己读完全文,以免造成信息遗漏!

<center><h1>我如何才能开始游玩？</h1></center>

-------


### 如果你是新手

- windows

	1. 点击[这里](http://cdn.alicespace.cn/Alice_space.zip)下载整合包,解压到一个文件夹

	2. 点击名字带有`HMCL`的应用程序

	3. 取一个昵称**只由字母，数字和下划线构成，长度限制为3-16位**填写进去,启动游戏,点击多人游戏
	
	4. 享受!

- macOS
  1. 安装java运行环境,自己百度.点击[这里](http://cdn.alicespace.cn/Alice_space.zip)下载整合包,解压到一个文件夹
  2. 下载[HMCL](https://github.com/huanghongxun/HMCL/releases/download/v3.3.163/HMCL-3.3.163.jar)启动器,放在解压的根目录
  3. 双击运行启动器,取一个昵称**只由字母，数字和下划线构成，长度限制为3-16位**填写进去,启动游戏,点击多人游戏
  4. 享受!
  
- Linux

  你都用`Linux`了,自己安装`Minecraft 1.15.2`
  
### 不是新手

- 版本`1.15.2`,纯净生存
- 服务器地址`mc.alicespace.cn`


<center><h1>我如何才能联系到大家?</h1></center>

---


| <a href="http://qr.liantu.com/api.php?text=https://weixin.qq.com/g/Aarp41Goo0gmEe26"><i class="fa fa-weixin fa-3x"></i></a>     | <a href="https://t.me/joinchat/HW1QVxPQH74HaCiaKRmTnQ"><i class="fa fa-telegram fa-3x"></i></a> |
| ---------- | ----------------------------------------------------- |
| [二维码](http://qr.liantu.com/api.php?text=https://weixin.qq.com/g/Aarp41Goo0gmEe26) | [链接](https://t.me/joinchat/HW1QVxPQH74HaCiaKRmTnQ)  |


<center><h2>我们提供了在线地图</h2></center>

---

| 主生存世界(main)    | PKU建筑还原世界(pku)          |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| <a href="http://mc.alicespace.cn:8124/index.html"><img height="30px;" src="https://img.shields.io/badge/map-available-green.svg"></a> | <a href="http://mc.alicespace.cn:8125/index.html"><img height="30px;" src="https://img.shields.io/badge/map-available-green.svg"></a> |

<center><h1>社区守则(建议稿)与新手指南</h1></center>

---
[社区守则建设中,欢迎贡献](https://github.com/Alice-space/pkuMinecraft-web.git)

## 总则
Alice_space(A pkuer minecraft server)服务器(以下简称"本服")，是由几个来自北京大学的对于minecraft有浓厚兴趣的同学出于爱好目的**无偿自愿**搭建的，与北京大学官方**无任何关系**。本服成员亦不得以学校官方名义做任何宣传活动。

## 服务器概述
本服分为两个子服：

- 生存服：`Paper`服务端 `1.15.2`原版纯净生存模式

- 创造服：`Paper`服务端 `1.15.2`创造模式，主题为还原pku建筑情况

## 生存服规范
### 1. 所有制

以**公有制**为基础，多种所有制共同发展。

1. **所有权**指对minecraft世界中方块，实体和物品的拥有，更改，转化和消灭的权力，**所有制**是所有权的制度。
2. 服务器实行**自由地权**制度，任何人可以取得**任意大小，数量不限**的**建筑规划区**，用于建造**公共设施**，**住宅**，**观赏性私有建筑**等。建筑规划区的大小视内部建筑的大小和建筑情况进行动态调整。
3. **公共设施**的方块、实体不能随意破坏，但物品可以随意取用，有特殊说明时除外。
4. **住宅**，**观赏性私有建筑**的方块、实体、物品，**除非得到所有者同意**，否则不得以任何形式破坏、取用，可逆的状态改变（如开门）在无特殊说明时除外。
5. **公共区域**指不属于任何**建筑规划区**的方块，其中非玩家实体和容器内的物品默认属于公有，可任意取用。
6. **特殊说明的建议方式**：在方块容器（如箱子，漏斗，投掷器）上用告示牌标注私有或公有，生物可以命名（如驴，羊驼），需要禁止可能的状态改变的方块（如活版门）也可用告示牌标注。

### 2. 地图标记

本服设置了在线地图，任何玩家可以在地图上设置点、线、区域。

1. 标示方法：

```
#标示点(用指定值替换尖括号参数，方括号为可选参数)
/dmarker add <label> set:<set_name> icon:<icon_name>： 在当前坐标处添加标记点到集合set_name，名为label
/dmarker delete <label> ： 删除标记点，名为label，更改位置请删除原有再重新添加
/dmarker list [set:<markerset-id>] ： 列出指定集合中的点，一般不需填写集合
```
icon-name请看[这里](https://github.com/webbukkit/dynmap/wiki/Using-markers#marker-icons)
```
#标示线和区域(用指定值替换尖括号参数，方括号为可选参数)

/dmarker addcorner : 将自己坐标添加到列表
/dmarker addcorner <x> <z> <world> : 将指定坐标点添加到列表,必须指定world为当前所在维度,如main,main_nether,main_the_end
/dmarker clearcorners : 清除列表


/dmarker addarea <label> color:<RRGGBB> fillcolor:<RRGGBB> set:<set_name> ：使用列表的点围成区域,添加到集合set_name，名为label，填充颜色RRGGBB，未指明set将添加至默认集合，which is irregular
/dmarker deletearea id:<area-id> set:<markerset-id> : 删除区域, id 从listareas可知
/dmarker listareas set:<markerset-id> : 列出指定集合中的区域，可以找到需要的id


/dmarker addline <label> color:<RRGGBB> set:<set_name> : 添加列表的点连接的线，添加到集合set_name，名为label，颜色RRGGBB,原则上线应添加入railway集合
/dmarker deleteline id:<line-id> set:<markerset-id> : 删除线，id从listlines可知
/dmarker listlines set:<markerset-id> : 列出指定集合中的线，一般markerset-id是railway
```

2. 举例说明：

```
# 在扫荡过一个结构后添加记录
/dmarker add structure_name_<structure_id>  set:struct <icon:icon_name>: 建议使用pirateflag等易于辨识的icon

# 绘制矩形

# 添加列表
/dmarker addcorner <xA> <zA>
/dmarker addcorner <xB> <zB>

#矩形
/dmaker addarea label color:RRGGBB fillcolor:RRGGBB set:set_name ：使用AB点作为对角添加区域，添加进集合set_name，名为label，颜色RRGGBB

# 绘制多边形、折线ABCDE
# 添加列表
/dmarker addcorner <xA> <zA>
/dmarker addcorner <xB> <zB>
/dmarker addcorner <xC> <zC>
/dmarker addcorner <xD> <zD>
/dmarker addcorner <xE> <zE>

# 多边形
/dmarker addarea label color:RRGGBB fillcolor:RRGGBB set:set_name：使用ABCDE点围成区域,添加到集合set_name，名为label，颜色RRGGBB

# 折线
/dmarker addline label color:RRGGBB set:set_name: 添加ABCDE连接的线，添加到集合set_name，名为label，颜色RRGGBB

#绘制结束后ABCDE会被自动清理

# 添加道路
/dmarker addcorner <xA> <zA>
/dmarker addcorner <xB> <zB>
...

/dmarker addline <label> color:RRGGBB set:railway

```

### 3. 公共设施管理办法

**公共设施**指建筑在**建筑规划区**内，由建筑规划区的所有者决定，开放给公众并提供公共服务的设施。

1. 在开始您的建设之前，请对地图进行大致的浏览并查看以下的**公共设施列表**

2. 在完成了上述事项之后，您可以选择**任意**大小的一片区域进行建造，并将您选择的区域的坐标、您的游戏id、添加时间添加到**公共设施列表**中。

3. 铁路请添加到集合`railway`，公共建筑添加到`public`，私人领地添加到`private`,**扫荡过的**天然结构(末地门,遗迹)添加到`struct`.为自己选择**一种**颜色，**并为自己的所有设施添加该颜色**。

4. 如您在建造过程中遇到以下问题，请联系该区域的建造者协商解决。
   - 空间冲突；
   - 希望对已完工的建筑区域进行修改或统一建筑风格；
   - 希望承包已荒废较长时间的建筑区域；
   - 其他可能与他人产生矛盾的问题。

5. 建筑规划列表

   在[这里](https://www.wjx.cn/jq/72214601.aspx)回答问卷，等待被添加

   | 编号 | 游戏id | 项目名称 | 添加时间 | 坐标 |
   | ---- | ------ | -------- | -------- | ---- |
   | 1    |        |          |          |      |
   | 2    |        |          |          |      |
   | 3    |        |          |          |      |
   
6. 颜色登记表
   
   在[这里](https://www.wjx.cn/jq/72213601.aspx)回答问卷，等待被添加
   
   | 游戏id          | 色号      |
   | --------------- | --------- |
   | 北大红（专属）  | `#820010` |
   | Lokdora         | `#4C7F99` |
   | Viktor_He       | `#DC143C` |
   | berilliumcopper | `#006BAC` |
   | TemplarBruno    | `#1453AD` |
   | a1q2w3s         | `#89CFF0` |
   

 ## 创造服规范

待修订

   




<center><h1>一些信息</h1></center>

-------


## 关于Minecraft
1. Minecraft已售出1.8亿份，月活跃玩家超一亿，是当之无愧的全世界最畅销/活跃的游戏（这个必须得吹一波


## 友情链接

1. 官方wiki，你的大多数问题在这里都有解答 [Official Minecraft Wiki(chs)](https://minecraft-zh.gamepedia.com/Minecraft_Wiki)
2. mc画圆专用 [Plotz Modeller For Minecraft](https://www.plotz.co.uk/)
3. 找结构专用，本服[种子](https://minecraft-zh.gamepedia.com/种子（世界生成）)公开 [chunkbase](https://www.chunkbase.com/)
4. 本服设有创造服，添加了[worldedit](https://worldedit.readthedocs.io/en/latest/)插件方便快速建造
