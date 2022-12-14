# Nicewow

#### 介绍
一个让魔兽世界以及类似网游多开玩法更有趣的工具应用。
此工具易于使用且功能强大，使WOW多开冒险更加愉快。由于暴雪已经禁止了 FollowUnit API，所以很多支持“auto follow”功能的插件都无法正常工作了，比如 autofollow、FollowMePls。该工具不仅提供了按键同步功能，还修复了损坏的“自动跟随”功能。本工具依赖autofollow插件,因为autofollow的停止跟随宏是我们需要的。

#### 安装教程

- 下载发布的版本： 
-  [正式版1.6.6]https://pan.baidu.com/s/1KHn_fFVu40jD1h0giqIDjg  提取码：3fvj
- 解压缩到任意文件夹，解压后文件夹内容结构如下：
- ![image](https://user-images.githubusercontent.com/7961235/200767841-4752ee8a-6656-4347-993c-97d2bbef3857.png)

#### AutoFollow 插件安装
- 怀旧服安装AutoFollow插件到"World of Warcraft/\_classic\_/Interface/AddOns"目录
- 正式服安装AutoFollow插件到"World of Warcraft/\_retail\_/Interface/AddOns"目录
- 怀旧服AutoFollow插件版本下载地址:
  链接: https://pan.baidu.com/s/1zpe6Gxc3PX9o5gFfa8JY4g 提取码: j2ya 
- 正式服AutoFollow插件版本下载地址:
  链接: https://pan.baidu.com/s/16ictqjJ6UHXXyIGxw2Nwlw 提取码: xawv 

#### 软件运行                            
- 先多开运行游戏，本应用最多支持5开 
- 游戏已运行后，运行本软件。如果是怀旧服，运行wowclassic.bat, 正式服运行wow.bat

#### 模式选择
- 输入A进入一键宏模式
- 输入S进入按键同步模式 

#### 一键宏模式
前提： - 桌面鼠标右键-显示设置-缩放与布局 100%
![image](https://user-images.githubusercontent.com/7961235/195110919-1cfa45e7-90db-48ec-a586-f5e1d865e1e7.png)
启用一键宏模式后，程序需要你输入几个参数
- 是否开启后台wow防掉线(Y/N): 开始启用建议输入N，设置好了可以选Y，让后台挂机的号防止AFK
- 请输入一键攻击键位: 输入将来的一键宏绑定的键位
- 要使用一键宏模式，必须安装一个技能优先级提示的插件，正式服强烈推荐Hekili，怀旧服部分职业可以使用Hekili，亦可以用TellMeWhen和WA替代，你要你会设置，插件能够提示下一个该释放的技能图标即可.
- 本说明以Hekili为例子
- 首先安装号Hekili 汉化版下载地址： https://img.nga.178.com/attachments/mon_202210/25/axsjQjmf-k1auXcZ3d.zip?filename=Hekili%5fWLK%5fzhCN%2ezip
- 按enter键，输入/hekili再回车，呼出Hekili配置界面
- 把Hekili的Primary部分拖拽到一个不会被遮挡的位置（建议聊天窗口的上方右对齐），如图所示
  ![image](https://user-images.githubusercontent.com/7961235/200771307-a78073a7-8da2-4f13-bf6b-583eb88b4ba1.png)
- 把鼠标移动到第一个图标的右上方非底色区域，然后按一下INS，选定当前位置为取色点坐标
  ![image](https://user-images.githubusercontent.com/7961235/200771661-dad419ed-9645-4568-ab87-26d2cd4b0270.png)
- 按下INS键后，NiceWow窗口会显示
  ![image](https://user-images.githubusercontent.com/7961235/200773688-1dd3c0d0-fc68-42fe-8081-5e4e2baa0e2e.png)
- 制作一键攻击宏，宏很简单, /施放 攻击 即可，然后把它绑定在你前面输入的一键宏绑定键位上，我这里是Q，因为我前面就输入了Q
![image](https://user-images.githubusercontent.com/7961235/200775187-cc855264-3440-4447-978b-83a8c924c22e.png)
- 在游戏里按一下一键宏绑定按键，我这里是Q，回到NiceWow窗口，你会看到提示提示当前取色点的RGB值
![image](https://user-images.githubusercontent.com/7961235/200776113-7ccb72cf-bc7d-46df-aaa9-3e2c361143bf.png)
- 按一下F11，把当前图标对应的技能按键输入，让当前取色点的颜色跟技能按键对应起来
![image](https://user-images.githubusercontent.com/7961235/200777300-67920e84-ff44-4b70-8ec3-5ac27c913a7f.png)
- 在游戏里按一下一键宏绑定按键，我这里是Q，你会发现提示的技能被释放，Hekili会提示你释放下一个技能，NiceWow窗口里也有相应提示
 ![image](https://user-images.githubusercontent.com/7961235/200778371-c002ebe0-4216-4b02-a520-ff52fddc064b.png)
- 按照上面的步骤，把所有出现的技能提示都设置一遍
- 在游戏里按一下F10，则Nicewow会把所有上面的设置保存
  ![image](https://user-images.githubusercontent.com/7961235/200780688-b78af486-6a62-4100-897b-b38b955e04eb.png)
- 在游戏里按一下F9，则会开始自动攻击，再按一下F9，自动攻击暂停
- 如果你要配置下个角色，请在配置前把当前的record.dat备份
![image](https://user-images.githubusercontent.com/7961235/200781391-9bb0d51a-9549-438a-bda1-760fe448c05c.png)
- 如需启动备份的配置，只要将备份的配置更名为record.dat即可（当然你要将原来的record.dat改成别的名字）
- 如NiceWow目录下存在record.dat,启动选择一键宏模式时，会提示是否读取已有的按键录制记录，如输入Y回车，则record.dat储存的颜色按键对应置被直接加载，无需再次配置
  ![image](https://user-images.githubusercontent.com/7961235/200782844-05be5cec-d3e8-44f1-bdc8-a597d625ccea.png)

### 一键宏模式教学视频
https://www.bilibili.com/video/BV1m24y1f7Py/


#### 按键同步模式参数输入
启用按键同步模式后，程序需要你输入几个参数
- 请输入您的前进按键: 就是你魔兽里面人物前进的按键，大多数人应该都是W（不分大小写）
- 请输入您的左转按键：往左按键，大多数人应该都是A（不分大小写）
- 请输入您的右转按键：往右按键，大多数人应该都是D（不分大小写）
- 请输入召集跟随按键,注意这个键位将绑定跟随宏: 这个键位对于跟随者来说，绑定是跟随宏，默认值是T（不分大小写）
- 请输入停止跟随按键，注意这个键位将绑定停止跟随宏:这个键位对于跟随着来说，绑定是停止跟随宏，默认值是G（不分大小写）
- 是否开启近战跟随模式(Y/N):如果跟随者有近战，[请参考近战跟随者额外配置](#近战跟随者额外配置)
- 请输入您的跟随角色与目标互动的按键(默认值E，不区分大小写):如果你选择了开近战跟随模式，则必须要提供近战跟随者与目标互动的键位
- 请输入请输入最大同步延迟单位毫秒，有了这个参数，各个跟随者的键盘同步会随机加上一定延迟
- 是否开启鼠标移动同步(Y/N): 如果你要玩几个法师往一处放暴风雪，这个就是为你准备的，鼠标指向宏会做的吧
- 跟随宏和停止跟随宏如何设定，[请参考核心宏设定小节](#核心宏定义及宏键位绑定)
- 一般的程序启动输入情况如图所示
![image](https://user-images.githubusercontent.com/7961235/200783625-8bf4a8c6-1b74-4dd3-93ef-1f9798edfd29.png)



#### 功能初步验证
程序正常启动后，玩家操作主控角色，按一下空格键（Space），如果所有多开的角色都会同时起跳，说明键位同步功能已正常启用。

#### 核心宏定义及宏键位绑定

核心宏仅为二个, 因为玩家主要操作主控角色，那么所有跟随角色必须要做两个宏，即“跟随宏”和“停止跟随宏”

- 跟随宏 （建议放置在跟随角色的T键位上）
```
/f 主控角色id
```

- 停止跟随宏 （建议放在跟随角色的G键位上），注意最后一句/f player就是player, player代表玩家自己，当然你把player改成自己的跟随号的id也是可以的
```
/af stop
/f player
```

上面的宏含义af指令，这个是安装AutoFollow插件才有的，所以AutoFollow是必装的
#### 重要移动控制键位
- DEL键，键位同步开关键，用户可通过按DEL来关闭/打开键位同步功能，在非游戏的时候，关闭键位同步是个不错的主意
- 召集跟随键，默认是T，实际由用户启动时输入，命令所有跟随角色重新跟随主控角色的键位
- 停止跟随键位， 默认是G，实际由用户启动时输入，命令所有跟随角色停留在原地
- 主控移动键位，默认是W、A、D，实际由用户启动时输入，命令主控角色行走，插件也会根据此按键下按事件自动发送"召集跟随键"到所有跟随者客户端，命令所有跟随者重新跟随主控角色


#### 协同行动
- 玩家按一下T键，则跟随者会主动跟随主控角色。玩家按一下G键，则所有跟随者停留在原地。
- 经过测试，术士法师等职业施放瞬发和读条技能，不会脱离跟随状态，但是如果施放通道魔法（吸取灵魂，奥术飞弹等），则会脱离跟随状态。目前插件已经在绝大多数情况下，可以让跟随者自动重新跟随主控角色行动，如果在意外的情况下，跟随者没有及时跟上，可按一下T，主动让跟随者重新跟随主控角色。

#### 近战跟随者额外配置
- ESC-界面-游戏-鼠标-点击移动（勾选）， 点击移动视角模式--总是调整视角
![image](https://user-images.githubusercontent.com/7961235/194624099-47db275e-e44b-41bf-93b8-28dfb2216970.png)

- ESC-按键设置-选中目标-与目标互动-E(强力建议E键，很顺手） 
![image](https://user-images.githubusercontent.com/7961235/194624128-00de8714-95ee-4296-aff3-18098a58f2c3.png)

- 如果近战跟随者，离主控攻击的怪有距离，无法攻击到，玩家按一下E键，则近战跟随者会主动调整视角并靠近目标怪物攻击

#### 多法师暴风雪AOE
- 是否开启鼠标移动同步(Y/N): Y，在程序启动时，如果你想玩多法师同步鼠标指向下雪，这个启动选项必须选择Y。
- 要调整好主控角色和跟随角色的镜头，视角，最好让多窗口的镜头和视角一致，调整好了测试一下，如果多法师放暴风雪基本位置重合，接下来玩游戏时，不要调整镜头和视角了，切记。
- 参考视频链接[NiceWow 一坦多法A怪指南](https://www.bilibili.com/video/BV13d4y1z74i)

#### 宏设定简单范例
- 现有2个盗贼，一个id为Ttx, 一个id为Ttz,其中Ttx为主控角色，Ttz为跟随角色，因为是近战组合，所以程序启动时应该选择开启近战跟随模式，也需要提供近战跟随者与目标互动的键位

- 主控角色Ttx可以不设定任何宏，由于是个低级盗贼，键位设置也很简单
![image](https://user-images.githubusercontent.com/7961235/194626450-80ed3057-32b1-4778-9aad-2d0564b7771f.png)

- 跟随角色Ttz则每个对应的攻击键位都要绑定宏，对应的键位和宏，而且[请参考近战跟随者额外配置](#近战跟随者额外配置)
![image](https://user-images.githubusercontent.com/7961235/194626882-463752e0-ac7f-4eab-b71c-2cf414952633.png)
- 影袭宏:                                                                                                     
![image](https://user-images.githubusercontent.com/7961235/194627070-0e9f8123-57ef-494a-b666-937f257b8b3a.png)
- 刺骨宏:                                                                                                    
![image](https://user-images.githubusercontent.com/7961235/194627154-54af70b7-7ae7-4c15-8948-290d51413429.png)
- 跟随宏:                                                                                                    
![image](https://user-images.githubusercontent.com/7961235/194627239-b6877397-2fd0-4159-832b-a293e6c8a147.png)
- 停止宏:                                                                                                    
![image](https://user-images.githubusercontent.com/7961235/194627316-f437720e-ce74-4f45-87c2-102548b5af54.png)

- 攻击宏里必须带有
```
/target 主控角色id
/assist
/cast ...
```
- 作战场景： 玩家操控Ttx去接近怪，跟随者TTz会主动跟随Ttx,当Ttx开始攻击时，如果Ttz没法攻击到怪，这时玩家只要按一下跟随角色与目标互动的按键，则Ttz会主动接近怪并协助攻击怪。

#### 防止AFK掉线功能
- 离开电脑后，Nicewow会自动在10分钟后启用防掉线挂机模式，把你个人物放到一个安全的角落，做一个安静的美少女或者美男子即可。
- 主玩一个号，其他号挂机，按一下DEL，暂停按键复制，其他后台的wow都进入防呆模式。
- 终极防掉线模式需要一下操作：（终极防掉线只有1.4.0及以后的版本支持）
- 桌面鼠标右键-显示设置-缩放与布局 100%
![image](https://user-images.githubusercontent.com/7961235/195110919-1cfa45e7-90db-48ec-a586-f5e1d865e1e7.png)
- 所有战网客户端大小一致，并严格堆叠在一起
![image](https://user-images.githubusercontent.com/7961235/195111362-7366cd3a-f5ea-482b-8043-1ea88aaee067.png)
- 在NiceWow已运行时，把鼠标位置放在战网“进入游戏”按钮正中间，并按一下INS键
![image](https://user-images.githubusercontent.com/7961235/195112789-18bccb9c-5daf-431a-b8ed-d0d98c015601.png)

- 调整每个wow的图形设置，都以窗口运行，并且窗口尺寸不宜过大，推荐1920*1440
![image](https://user-images.githubusercontent.com/7961235/195112283-2270ce89-b4a5-4ac0-9009-2be8cc986768.png)
-[深度防掉线教学视频](https://www.bilibili.com/video/BV1MB4y177ev/)


#### 玩家已开发的玩法样例
- 每个玩家开发的样例占有一个目录，目录下至少有2个文件，一个是键位同步设置文件keyclone.txt,一个是md文件，描述了玩法角色的宏设定，键位宏绑定，以及一般的战斗过程描述。
- [兽王猎+恶魔术组合](https://gitee.com/aiyuntang/nicewow/tree/master/%E7%8E%A9%E6%B3%95%E7%9B%AE%E5%BD%95/%E7%8C%8E%E4%BA%BA+%E6%9C%AF%E5%A3%AB%20From%20GA)
- [战斗贼+暗牧组合](https://gitee.com/aiyuntang/nicewow/tree/master/%E7%8E%A9%E6%B3%95%E7%9B%AE%E5%BD%95/%E7%9B%97%E8%B4%BC+%E6%9A%97%E7%89%A7%20From%20GA)

#### 视频攻略
- [二人转的王者，dk+惩戒骑来袭，双开爽玩](https://www.bilibili.com/video/BV17P4y1Z795)
- [自动跟随重生，nicewow让你多开体验重回巅峰](https://www.bilibili.com/video/BV1Pd4y1V7Aw)
- [WLK如何愉快的玩耍,多开党的福利送到](https://www.bilibili.com/video/BV1de4y1a7iU/)

- [正式服支持以及近战组合练级心得](https://www.bilibili.com/video/BV13P411V7eu/)


#### 软件密钥设置
- 软件密钥定义在key.txt内，用户只有得到合法的密钥后并复制到key.txt内，本软件才能正常使用

- key.txt初始内容为试用key，可能会过期

- 从管理员得到key后，运行该软件后，key会跟当前电脑绑定

#### 键位同步设置 keyclone.txt

- 本软件内置可同步的键位为：` **A-Z(26个字母键),  0-9（10个数字键）， SPACE(空格键），OEMMINUS（减号），OEMPLUS（加号）, F1-F4 (F5-F9是快速切换游戏窗口键 F11,F12被windows系统用作其他用途，所以F5~F12都是不能同步的）** `

- 用户可自定义被同步的键位，打开keyclone.txt, 初始内容为： 

```
D0 D1 D2 D3 D4 D5 D6 D7 D8 D9 SPACE W E J Q T G Z X Y K H OEMMINUS OEMPLUS F1 F2
```

  初始键位同步设定含义为： 数字键0-9，空格键，字母键 W E J Q T G Z X Y K H, 减号, 加号,F1,F2 这些键位会复制，其他键位会忽略 

- 用户可自行增加或者减少里面定义的键位，但是增加的键位仅允许在本软件内置可同步的键位内。

- 本软件仅会同步在keyclone.txt里定义的键位，其他未出现在keyclone.txt里的键位会被忽略


#### 其他MMORPG网游支持（实验性，有效性有待玩家探索）
- 多开网游客户端
- 按CRL+ALT+DEL键，打开windows 任务管理器，选则详细信息Tab页，找到该网游客户端的进程，例如魔兽怀旧服的进程如图所示
![image](https://user-images.githubusercontent.com/7961235/194624222-07c1debd-cd4d-4674-aa64-c2c03c8ad97d.png)

- 假设该网游的客户端的进程名称为 xyz.exe
- 在软件目录下制作一个文本文件，xyz.txt,里面的内容如下

```
@echo off
start NiceWow.exe xyz
exit
```
- 改变xyz.txt后缀名为bat，则软件文件目录结构类似
![image](https://user-images.githubusercontent.com/7961235/194624294-1f3a852b-64fb-4e51-bb96-96f8381f2362.png)

- 多开玩游xyz，点击运行xyz.bat即可


#### 技术支持
- 微信： zhuiyingderen
- QQ： 15520929

#### 开源合作
- 欢迎各位爱好者提供玩法PR
- 玩法PR请在目录 "玩法目录"里建立你自己的目录
- 你自己的目录下至少包含2个文件，1个为keyclone.txt，描述了你要键位复制的配置，另外一个为md文件，描述键位上宏的设定，以及典型玩法描述
- 如果你有更好的想法，请你体现在你的PR里，欢迎之至
- 玩法PR review通过被收录，免费送月卡1张

#### 软件试用和收费

- 下载后可免费使用，免费版使用30分钟后功能就会失效，需重新启动应用方可再次使用,免费版不提供防掉线及自动重启游戏功能
- 长期使用月卡20元一张，支持5号同开，良心价格，童叟无欺


#### 免责申明

- 本软件完全出于个人兴趣爱好，由本人在业余时间开发，是一款安全，绿色，可靠的软件产品
- 本软件不会收集任何用户数据，使用时无任何网络通讯,欢迎任何专业人士验证
- 利用本软件所做出的任何行为，和本人无关
- 因使用本软件而引致的任何意外、疏忽、合约毁坏、诽谤、版权或知识产权侵犯及其所造成的任何损失，本人概不负责，亦概不承担任何民事或刑事法律责任
- 当你第一次开始使用本人所提供的任何软件及资源的那一刻起就将被视为对本声明全部内容的认可。同时您必须认可上述免责条款，方可使用本软件及资源。如有任何异议，建议立刻删除本软件及资源并且停止使用
- 以上内容，本人保留最终解释权
