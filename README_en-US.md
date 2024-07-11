<div align="right">
<a href="/README.md">中文</a> &nbsp;|&nbsp;
<a href="/README_en-US.md">EN</a>
</div>

<div align="center">
<h1>alist-ddns-go</h1>
</div>

This is a Magisk module that provides support for Alist and ddns-go services for Android

![Release](https://img.shields.io/github/tag/liangsuimansui/alist-ddns-go?style=flat-square&label=Release) ![Stars](https://img.shields.io/github/stars/liangsuimansui/alist-ddns-go?style=flat-square&label=Stars&logo=github "GitHub Repo stars") ![Downloads](https://img.shields.io/github/downloads/liangsuimansui/alist-ddns-go/total?style=flat-square&label=Download&logo=github)

# Module Working Directory
`data/alist-ddns-go`

# Using Tutorials & Instructions
> ## Alist Official Documents
> #### https://alist.nn.ci/
> ## GitHub repo for ddns-go
> #### https://github.com/jeessy2/ddns-go

> ## prompt
> The account that installed Alist for the first time was: `admin`
>
> Password lookup`Successfully created the admin user and the initial password is:`in file`/data/alist-ddns-go/logs/alist_run.log`
>
> In addition, here are some interfaces for ddns-go to get ip through interfaces
> ipv4:
> ```
> https://myip4.ipip.net,https://ddns.oray.com/checkip,https://ip.3322.net,https://4.ipw.cn,https://ipinfo.io,https://cip.cc,https://ident.me,https://v4.ident.me
> ```
> ipv6:
> ```
> https://ipv6.ddnspod.com,https://api-ipv6.ip.sb/ip,https://v6.myip.la/json
> ```

> [!NOTE]
> For the module, the command provided by the original document will not be used, the module provides a script to turn the corresponding function on or off, the script is located in the
> 
> `/data/alist-ddns-go/alist/tools`
> 
> `/data/alist-ddns-go/ddns-go/tools`
> 
> Of course, you can also control the function by command, the detailed command is as follows:
> ```
> # start Alist
> /data/alist-ddns-go/alist/script/alist.tool -s
> # stop Alist
> /data/alist-ddns-go/alist/script/alist.tool -k
> # update Alist
> /data/alist-ddns-go/alist/script/alist.tool -u
> # start ddns-go
> /data/alist-ddns-go/ddns-go/script/ddns-go.tool -s
> # stop ddns-go
> /data/alist-ddns-go/ddns-go/script/ddns-go.tool -k
> # update ddns-go
> /data/alist-ddns-go/ddns-go/script/ddns-go.tool -u
> ```
> In addition, the module automatically checks for updates at 8 a.m. every day




