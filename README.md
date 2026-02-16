# drwiki-zh-maps
deltarune中文wiki地图仓库 zh.deltarune.wiki
关于如何创建地图敬请参考https://undertale.wiki/d/t/interactive-maps-project/318 ，一般来说翻译地图不需要修改原地图，仅需翻译文本。
## 修改翻译一定要先从本仓库下载文件，再本地修改。改完后先传到本仓库，再传Wiki，不要直接在Wiki上改地图代码。这样大家可以协作翻译！
### 翻译地图简要流程
1. 从本仓库或https://github.com/utdrwiki/maps 下载zip解压，或git clone到本地，现有游戏地图基本都已包含
2. 下载并安装Tiled软件https://www.mapeditor.org/
3. 用Tiled打开仓库文件夹里的“deltarune.tiled-session”，它会提示安装插件，插件一定要装。
<img width="543" height="105" alt="image" src="https://github.com/user-attachments/assets/7248ca8b-ef81-4972-b54f-6e52694c2d79" />

4. 侧栏的所有父级（紫色图标）的名字都不需要改，wiki会自动识别。依次展开侧栏里的对象，**Wiki language选择简体中文**，左边一列是你的翻译，右边一列是原文参考。翻译的语法跟wiki编辑页面的语法相同。底部Page一栏是这个注释本身链接的页面，一般对照英文版的找到中文对应页面即可。Image也是对应英文，大部分都空着的。注意无论哪里要包含中文wiki页面，建议每个都要直接去那个页面的地址把"/w/"后面的文字复制过来，否则容易因简体繁体的字符不同而找不到页面，也因为在这里编辑没有wiki的联想功能。

<img width="522" height="500" alt="image" src="https://github.com/user-attachments/assets/e4096c73-c634-41f7-89ba-3730eec9e523" />

<img width="602" height="424" alt="image" src="https://github.com/user-attachments/assets/cd4a3539-375f-4393-9834-fe8690065214" />

5. 编辑完后，**先将你编辑的地图tmx文件传到本仓库**，然后点击菜单栏File下的Publish to wiki，**Wiki language选择简体中文**，点OK，它会打开一个页面，再点Allow，然后会有一个白底的网页，点Copy code，复制到Tiled里面，点OK。

<img width="505" height="238" alt="image" src="https://github.com/user-attachments/assets/e514fee6-175e-4afa-8ebd-ec5254d4e2fb" />

<img width="489" height="271" alt="image" src="https://github.com/user-attachments/assets/0084394a-919d-4edc-9f42-f20942738822" />

<img width="608" height="123" alt="image" src="https://github.com/user-attachments/assets/6902a540-3db6-4600-9fc7-0a0f6c841463" />

6. 在中文wiki里搜索“Map:你上传的地图名”即可查看你的地图。
7. 在对应的页面里，一般在第一段概述的下面插入
```
  {{Clear}}
  
  == 地图 ==
  {{Map:XXXXX}}
  {{Clear}}
```
8. 大功告成
