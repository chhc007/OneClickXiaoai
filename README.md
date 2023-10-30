# OneClickXiaoai
exe一键快速唤醒PC版小爱同学

Bilibili: 老年人Captain

原Gitee上的项目，全部迁移至Github

重大更新，支持直接语音唤醒电脑小爱同学，无需点击直接对话。

注意：必须替换唤醒词为自己的文件，因为一个唤醒词只能激活三台电脑

***使用说明：***

下载最新版！！！

解压缩到你希望永久存放这个工具的文件夹，而不是桌面或者临时文件夹。

去https://console.picovoice.ai/ 登入，按照视频教程做一个自己的唤醒词，然后下载，解压，重命名为Wakeup.ppn，然后替换文件夹中的Wakeup.ppn！！！

然后在配置文件set.ini中修改key为你的key！！！！！！视频忘说这一步了。

最后就可以使用设置工具来启动语音监听功能了。


其中Wakeup.ppn是唤醒词文件，set.ini是设置灵敏度的，xiaoai.exe就是原来那个启动小爱的工具，你也可以继续绑定鼠标宏。

PS：porcupine_params_zh.pv文件是中文模型，如果你希望使用英文唤醒词，请下载官方英文模型然后重命名为porcupine_params_zh.pv替换现有的。https://github.com/Picovoice/porcupine/tree/master/lib/common

***下载地址：在release中***


3.绑定任意快捷键指定为启动一键唤醒的exe

4.使用快捷键

PS：基本完善的版本，没啥大bug就不更新了
