#AutoProxy-Vimperator-Plugin
===========================

[AutoProxy](https://addons.mozilla.org/en-US/firefox/addon/autoproxy/)和[FoxyProxy](https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/)的Vimperator插件
修改于[marlonyao](http://marlonyao.iteye.com/blog/776775)的代码


###AutoProxy
* :ap [auto|disable|global] - 切换不同模式，无参数则显示当前的代理模式。
* :sp - 在自动和全局模式间切换。
* :spr - 在自动和全局模式间切换，切换后自动reload页面。
* :sdp [0|1|2...] - 切换不同的默认代理，参数为代理服务器的序号，从0计数。

---
###FoxyProxy
FoxyProxy目前需要修改脚本，把对应代理的id改为自己的。代理的id可以在Firefox Profile下的foxyproxy.xml中查找“<proxy name”看到。

* :fp [proxy name] － 切换不同模式，无参数则显示当前的代理模式。
* :fpr [proxy name] － 切换不同的模式，切换后自动自动reload页面。

---
这里还有我写的[Windows](https://github.com/AnyOfYou/Windows-AHK-SwitchProxy)下，和[Mac OS](https://github.com/AnyOfYou/GoAgentX-Alfred-Workflow)下的代理切换工具