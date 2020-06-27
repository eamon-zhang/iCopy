[<img src="https://f002.backblazeb2.com/file/jsuforum-upload/optimized/1X/cff2835c1652bb57a18aac42a3eee34b51cd9b89_2_1380x386.gif" width="50%" alt="jclone">](https://bbs.jsu.net/c/official-project/icopy/6)  

[![iCopy Telegram-Bot](https://img.shields.io/badge/iCopy-Telegram%20BOT-red?style=flat-square&logo=appveyor)](https://bbs.jsu.net/c/official-project/icopy/6)
[![Programming Language](https://img.shields.io/badge/LANGUAGE-Python%203.6%2B-success?style=flat-square&logo=appveyor)](https://bbs.jsu.net/c/official-project/icopy/6)
[![Version](https://img.shields.io/badge/Version-0.1.6-ff69b4?style=flat-square&logo=appveyor)](https://bbs.jsu.net/c/official-project/icopy/6)
[![License](https://img.shields.io/github/license/fxxkrlab/iCopy?style=flat-square&logo=appveyor)](https://bbs.jsu.net/c/official-project/icopy/6)  

[iCopy Forum](https://bbs.jsu.net/c/official-project/icopy/6) |
[TELEGRAM GROUP](https://t.me/sharegdrive) |
[CHANGELOG](CHANGELOG.md) |
[Future Version](https://github.com/fxxkrlab/iCopy/projects/1)  
 
**Send commands to [Telegram](http://telegram.org) BOT for get a _convience way_ to control [gclone](https://github.com/donwa/gclone) resources copy missions.**  

## Install  
1.Python 3.6+ is Required  
2.Pre-install screen  
3.Pre-install and Configured [gclone](https://github.com/donwa/gclone) is Reqired  
&nbsp;&nbsp;&nbsp;&nbsp;For Linux directly use this command  
&nbsp;&nbsp;&nbsp;`bash <(wget -qO- https://git.io/gclone.sh)`  
4.`git clone https://github.com/fxxkrlab/iCopy.git && cd iCopy`  
5.`python3 -m venv .`  
6.`. ./bin/activate`  
7.`pip3 install -r requirements.txt`  
8.`cp settings.py.example settings.py`  
9.&nbsp;Edit settings.py   

* _token : Bot API Token generated by BotFather  
* _usr_id : Your telegram user id. Only enabled users can use this bot.  
            You can find your telegram user id from "@get_id_bot"  
* Remote : Your gclone config name.like "gc"  
* Clone : The Clone Program Name which you using.(rclone / gclone)  
* Pre_Dst_id : Pre-Assigned Google Drive Destination Folder ID for quick mode  
* sa_path : The directory where your "service_accounts.json" is. End without slash "/".  
            NOTICE : "~" is not supported in the path.  

#### Start iCopy BOT :   
##### Start :  
`python3 -u iCopy.py`  

##### Start via screen :  
``screen -dmS iCopy `which python3` -u iCopy.py``  

#### 本项初愿本意通过学习 方便群友自定义转存机器人以及快捷命令  
#### 是一个 example 通过机器人 简单转存 Google Drive 资源的示例代码项目
#### 由于需求扩大 决定转为一个最终成品目标项目 慢慢完善  
#### 由于目前出于持续更新和半成品状态 给大家造成了麻烦 真的很抱歉
#### 目前计划所有预期的功能会在 v0.2.0-beta中全部放出 正在重构
#### 若有网上的朋友不明白的欢迎加TG群 [Google Drive 资源互通](https://t.me/sharegdrive)  