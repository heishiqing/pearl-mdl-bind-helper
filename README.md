# pearlhash 池 MDL 钱包绑定签名助手

这是 Vminer 提供的 pearlhash 池 MDL 钱包绑定签名辅助工具。

工具用于在本地 Pearl 钱包里生成绑定签名：

```text
I set <MDL 钱包地址>
```

生成签名后，把签名复制到 pearlhash 池子绑定页面里的 `Signature` 输入框，即可完成 PRL 钱包和 MDL 钱包的绑定验证。

## 下载

[下载最新版 P.MDL.zip](https://github.com/heishiqing/pearl-mdl-bind-helper/releases/download/v1.0.0/P.MDL.zip)

文件校验：

```text
SHA256: B99E780AA1587CE5193253CACC072539AFE2AB10AFC38DFA489D44DBB3D62D38
```

## 使用方法

1. 下载 `P.MDL.zip` 并解压。
2. 先打开本地官方 Pearl 钱包 APP，并保持钱包正在运行。
3. 确认这个 Pearl 钱包里已经有你要绑定的 PRL 地址。
4. 双击运行 `双击运行脚本.bat`。
5. 按提示输入 PRL 钱包地址。
6. 按提示输入 MDL 钱包地址。
7. 脚本会生成签名，并自动复制到剪贴板。
8. 回到 pearlhash 池子绑定页面，把签名粘贴到 `Signature` 输入框。

## 重要提醒

- 交易所钱包不能用于签名绑定，因为交易所钱包的私钥不在你本地。
- 本脚本不会询问、保存或上传助记词、私钥。
- 运行脚本期间，请保持本地 Pearl 钱包 APP 打开。
- 如果 Pearl 钱包设置了密码，脚本可能会提示输入钱包密码，用于临时解锁 60 秒完成签名。
- 本仓库只发布签名助手，不包含任何钱包数据、助记词、私钥或 `wallet.dat`。

## 常见问题

### 未检测到本地 Pearl 钱包服务

请先打开官方 Pearl 钱包 APP，等待十几秒后重新运行脚本。

### PRL 地址不在当前本地钱包

说明输入的 PRL 地址不属于当前打开的本地 Pearl 钱包，脚本无法为这个地址签名。请切换到包含该 PRL 地址的钱包后再试。

### No command specified

请下载最新版压缩包，并通过 `双击运行脚本.bat` 启动，不要直接运行 `prlctl.exe`。

## Vminer

Vminer 主页：[https://vminers.com](https://vminers.com)
