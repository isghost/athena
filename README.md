# athena
守护雅典娜
# 项目背景
这是一个dota2自定义地图《守护雅典娜》的**模仿**地图，非官方，主要目的是学习
# 学习目标

* 地图编辑
* 关卡设计
* 技能设计(ability_lua)
* 自定义物品以及合成路线
* 自定义UI
* 网络交互与用户验证
* 自定义模型与特效

# 配置方法

```
# var currentDir = D:\dev
# var dota2Dir = D:\steam_game\steamapps\common\dota 2 beta
git clone https://github.com/isghost/athena
新建D:\steam_game\steamapps\common\dota 2 beta\content\dota_addons\athena 并将D:\dev\game下面的文件， 剪切到该目录下
新建D:\steam_game\steamapps\common\dota 2 beta\game\dota_addons\athena 并将D:\dev\content下面的文件， 前切到该目录下
mklink /j "D:\dev\athena\content" "D:\steam_game\steamapps\common\dota 2 beta\content\dota_addons\athena" 
mklink /j "D:\dev\athena\game" "D:\steam_game\steamapps\common\dota 2 beta\game\dota_addons\athena" 
# 注意， 外部目录链接到dota_addons目录， 启动工具无法识别
```
# 提交MR规范
//todo
# 学习资源
 * https://www.bilibili.com/read/cv6435062 B站UP主的中文教程，内容比较少，胜在容易懂
 * https://moddota.com/scripting-introduction/ 海外的英文教程，资料稍微全一点，资料比较老， 很多已经过期了
 * https://developer.valvesoftware.com/wiki/Dota_2_Workshop_Tools 官方教程，资料还行， 但缺少一个好的目录
 * https://developer.valvesoftware.com/wiki/Dota_2_Workshop_Tools/Scripting 还是官方教程，脚本目录， 开发大部分时间花在这上面