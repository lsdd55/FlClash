<div align=center>

[![Release Downloads](https://img.shields.io/github/downloads/lsdd55/FlClash/vVERSION/total?style=flat-square&logo=github)](https://img.shields.io/github/downloads/lsdd55/FlClash/vVERSION/)

**第三方构建版 · 新增 `socks5s` 协议支持**

本构建基于 [chen08209/FlClash](https://github.com/chen08209/FlClash)，内核替换为带 `socks5s` 协议实现的分支。
未获上游作者背书的非官方构建，问题请反馈到本仓库，不要提交到上游。

</div>

**Download based on your OS:**

<div align=left>
<table>
    <thead align=left>
        <tr>
            <th>OS</th>
            <th>Download</th>
        </tr>
    </thead>
    <tbody align=left>
        <tr>
        <td>Android</td>
            <td>
                <a href="https://github.com/lsdd55/FlClash/releases/download/vVERSION/FlClash-VERSION-android-arm64-v8a.apk"><img src="https://img.shields.io/badge/APK-ARMv8-168039.svg?logo=android"></a><br>
                <a href="https://github.com/lsdd55/FlClash/releases/download/vVERSION/FlClash-VERSION-android-armeabi-v7a.apk"><img src="https://img.shields.io/badge/APK-ARMv7-45bf55.svg?logo=android"></a><br>
                <a href="https://github.com/lsdd55/FlClash/releases/download/vVERSION/FlClash-VERSION-android-x86_64.apk"><img src="https://img.shields.io/badge/APK-x64-96ed89.svg?logo=android"></a>
            </td>
        </tr>
        <tr>
            <td>Windows</td>
            <td>
                <a href="https://github.com/lsdd55/FlClash/releases/download/vVERSION/FlClash-VERSION-windows-amd64-setup.exe"><img src="https://img.shields.io/badge/Setup-x64-2d7d9a.svg?logo=windows"></a><br>
                <a href="https://github.com/lsdd55/FlClash/releases/download/vVERSION/FlClash-VERSION-windows-amd64.zip"><img src="https://img.shields.io/badge/Portable-x64-67b7d1.svg?logo=windows"></a>
            </td>
        </tr>
    </tbody>
</table>


</div>

<div dir="ltr">

**新增：`socks5s` 代理协议**

```yaml
proxies:
  - name: socks5s-node
    type: socks5s
    server: 1.2.3.4
    port: 62330
    encryption: mlkem768x25519.native.<base64url>
```

`encryption` 为服务端下发的凭据，三段式结构：算法、模式、Base64URL 编码的公钥/种子。

**List of all changes:** [ChangeLog](https://github.com/lsdd55/FlClash/blob/main/CHANGELOG.md)

</div>
