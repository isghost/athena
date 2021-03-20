# athena
守护雅典娜
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
