# DogCs4.4
4.4修改版


关于64不上线bug:profile文件里添加如下:
```
http-stager {
    set uri_x86 "/XXXXn";
    set uri_x64 "/XXXXXX";
        }
```
# 修复2022.09.21 dogcsv2.1  fix CVE-2022-39197

新出了个漏洞,就简单更新一下吧。简单修复了一下最新出来的xss漏洞.

1.新加主机ip归属地查询,用本地纯真ip地址库.

2.修改默认配置文件存放文件名.也可以自行对比代码，自行修改文件名.

3.修复CVE-2022-39197造成的xss漏洞

看需求下载吧.

# Ps 用winrar解压,或者mac解压

# 注：CVE-2022-39197并没有完全修复,应该做全局过滤才行.下个版本修复！！！ 2022.09.26
# 修复补丁直接用这个哥们的patch补丁即可:https://github.com/burpheart/CVE-2022-39197-patch

# 2022.09.30 v2.2 修复上线主机ip归属地功能.

# 2022.10.09 v2.3 修复ipv6归宿地显示bug问题.(下载最新版替换客户端jar即可)

# 2022.10.19 v2.4 修复ui显示图标bug 感谢这位@D1sAbl4 提出的问题和修复方法.

# 2022.11.09 预计今年过年更新dogcs4.5。

# 新版本已更新(密码不同):https://github.com/TryGOTry/CobaltStrike_Cat_4.5
