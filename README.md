# breakwall
Automatically exported from code.google.com/p/breakwall

VERSION 9.6（2015.4.15）

1、修复 Snova 已失效的地址段，更新可用版本（注：此操作用户均可自行完成，在“其他功能”下的“修复代理”一项内，请定期执行，以确保 Snova 的可用）。

2、移除个人博客下载最新 Hosts 的选项，实测基本已无效。

3、关于 3.2.3 版 Goagent 在 Mac 系统中无法使用的说明：请尝试三种解决方案：a）更换一批最新可用的谷歌 IP（手动操作）；b）删除系统 Hosts 文件内的全部过期谷歌 IP 段，再重启电脑；c）如果以上两种依旧无法解决问题，请先去 https://github.com/alterstep/dnscrypt-osxclient/releases 下载最新的 Mac 版 DNSCrypt，安装后打开，并切换系统 DNS 地址到 okTurtles，然后再次运行 Goagent 即可使用（OSX 10.10.3 下实测有效）。

![2015-04-15 6 50 21](https://cloud.githubusercontent.com/assets/1466011/7159533/6ebb5d9e-e3b5-11e4-8807-96206a4cc99b.jpg)
![2015-04-15 6 50 30](https://cloud.githubusercontent.com/assets/1466011/7159534/6ed2ef04-e3b5-11e4-89ea-8bfab035ecce.jpg)
