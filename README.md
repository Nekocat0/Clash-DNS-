# 防止DNS泄露
Clash配置

使用方法：
1.使用订阅转换的工具把你的订阅链接转换成以下方式的链接。

示例（此链接中没有任何节点仅作示例用）：https://api.dler.io/sub?target=clash&url=%E3%80%82&insert=false&config=https%3A%2F%2Fraw.githubusercontent.com%2FMeilieage%2Fwebcdn%2Fmain%2Frule%2FArea_Media_NoAuto.ini&emoji=true&list=false&xudp=false&udp=false&tfo=false&expand=true&scv=false&fdn=false&new_name=true

2.在你转换好的链接中找到“false&config=”，然后把“=”后面的链接内容替换为“https://raw.githubusercontent.com/Nekocat0/-/main/nodnsleak.ini”

3.最后导入Clash就可以使用了。

不敢确保100/100防止DNS泄露。

只能作为一个参考。
