---
sidebar_position: 2
title: Using Ledger on Conflux eSpace
---

## 简介

[Conflux eSpace](https://docs.conflux123.xyz/docs/espace/learn/overview) is the new EVM-compatible subsystem of [Conflux](https://confluxnetwork.org/). Conflux eSpace支持Conflux原生代币[CFX](https://docs.conflux123.xyz/docs/general/conflux-basics/glossary#cfx)，以及许多其他加密资产，包括[ERC20](https://evm.confluxscan.io/tokens)和[NFT](https://evm.confluxscan.io/tokens-nft)通证。 您现在可以使用您的 **Ledger Nano S** 或 **Ledger Nano X** 硬件钱包，在 eSpace 上安全地存储您的资产。 在本指南中，我们将向您展示如何在您的Ledger设备上安装Conflux eSpace应用程序，如何将您的账户导入MetaMask，并如何在eSpace上转移资产。



:::note
**The Conflux eSpace Ledger app is not yet available in Ledger Live as it is currently under review.**
:::

## 开始前的准备工作：

在您开始之前，请确保您已经做了以下工作：

- 初始化了您的 [Nano S](https://support.ledger.com/hc/en-us/articles/360000613793-Set-up-your-Ledger-Nano-S?docs=true) 或 [Nano X](https://support.ledger.com/hc/en-us/articles/360018784134-Set-up-your-Ledger-Nano-X?docs=true) 设备。
- 更新您的 [Nano S](https://support.ledger.com/hc/en-us/articles/360002731113-Update-Ledger-Nano-S-firmware?docs=true) 或 [Nano X](https://support.ledger.com/hc/en-us/articles/360013349800-Update-Ledger-Nano-X-firmware?docs=true) 设备到最新的固件版本。
- 安装 [Ledger Live](https://www.ledger.com/ledger-live) 并将其更新到最新版本。
- 在兼容的桌面浏览器上安装[MetaMask](https://metamask.io)。

如果你遇到任何问题，可以在 [Discord](https://discord.com/invite/aCZkf2C) 或 [Telegram](https://t.me/Conflux_English)上找到我们。我们很乐意帮助。

## 安装

您可以按照以下步骤在您的Ledger设备上安装**Conflux eSpace应用程序**：

1. 通过 USB 将您的Ledger Nano S 或 Ledger Nano X 设备连接到您的计算机。
1. 输入您的 PIN 码解锁您的设备。
1. 打开 Ledger Live。
1. 在左边的菜单中，点击“管理”打开Ledger Live 应用程序管理器。
1. 当您的Ledger设备显示“允许Ledger管理器”时，请按下两个按钮以继续。
1. 回到Ledger Live，在“App catalog”选项卡下，在搜索框中输入“Conflux eSpace”。
1. 一旦Ledger Live显示了Conflux eSpace应用程序，点击“安装”。
1. Conflux eSpace应用程序已经成功安装。


## 设置 MetaMask

### 连接您的 MetaMask 钱包到 Conflux eSpace

您可以通过以下步骤添加 Conflux eSpace 网络到您的 MetaMask 钱包：

1. 打开浏览器，访问 https://evmchainlist.org。
1. 搜索"Conflux eSpace"。
1. 点击“连接钱包”以允许该网站向MetaMask发送请求。
1. 点击“Conflux eSpace”下面的“添加到MetaMask”。
1. 当MetaMask提示“允许该网站添加网络？”时，点击“批准”。
1. 当MetaMask提示“允许此网站切换网络吗？”，点击“允许”。

你的 MetaMask 钱包现在已经连接到 Conflux eSpace。 您可以随时通过 MetaMask 中的网络选择下拉菜单切换到其他网络。

您也可以手动在“设置”、“网络”、“添加网络”下将 Conflux eSpace 添加到 MetaMask 中：

- **Network Name**: Conflux eSpace
- **New RPC URL**: https://evm.confluxrpc.com
- **Chain ID**: 1030
- **Currency Symbol**: CFX
- **Block Explorer URL**: https://evm.confluxscan.net


### 连接您的Ledger设备到MetaMask

你可以按照以下步骤将 Ledger 设备中的账户导入到 MetaMask 钱包中：

0. 如果当前打开了Ledger Live，请退出。
1. 通过 USB 将您的Ledger Nano S 或 Ledger Nano X 设备连接到您的计算机。
1. 输入您的 PIN 码解锁您的设备。
1. 找到您设备上的Conflux eSpace应用程序，然后按下两个按钮打开它。
1. 在 MetaMask 中，找到 "Settings"、"Advanced"、"Preferred Ledger Connection Type"，并选择 "WebHID"。
1. 在 MetaMask 中打开右上角菜单，然后点击“连接硬件钱包”。
1. 选择"Ledger"并点击"继续"。
1. 您将看到一个浏览器弹出窗口，上面显示着 "MetaMask 希望连接到 HID 设备"。 从列表中选择您的Ledger设备，然后点击“连接”。
1. 几秒钟后，MetaMask会显示“选择账户”页面。 请选择您想要导入到 MetaMask 的一个或多个账户，然后点击“解锁”。
1. 你的账户现在可以在 MetaMask 中看到，显示为 "Ledger 1"。


## 使用Ledger

### 发送加密资产

假设您在Ledger设备上的账户有一些CFX代币，以下步骤展示了如何在Conflux eSpace上进行CFX转账。

*注意：如果您没有 CFX，您可以在列出的交易所之一购买，[这里](https://123cfx.com/#Exchanges)列出了交易所。*

0. 确认您已经通过上一节中的步骤将您的 Ledger 账户导入到 MetaMask 钱包中。 . 如果当前打开了Ledger Live，请退出。
1. 通过 USB 将您的Ledger Nano S 或 Ledger Nano X 设备连接到您的计算机。
1. 输入您的 PIN 码解锁您的设备。
1. 找到您设备上的Conflux eSpace应用程序，然后按下两个按钮打开它。
1. 在 MetaMask 中选择您的 Ledger 账户(例如，“Ledger 1”)。
1. 点击“发送”并输入接收方地址(应以`0x`开头)。
1. 在“金额”下，输入要转移的 CFX 数量，然后单击“下一步”。
1. 仔细检查交易详情，然后点击“确认”。
1. 您的Ledger设备现在将显示“审核交易”。 **仔细检查交易金额和收款地址**，可以通过多次按下设备上的右按钮来完成。
1. 如果所有信息都正确，请按下“接受并发送”屏幕上的两个按钮以批准交易。 否则，按“拒绝”界面上的两个按钮来拒绝交易。
1. 交易被批准后，它现在已被签名并发送到Conflux网络。 你可以在 MetaMask 中查看交易状态。 如果你点击该交易并点击“在区块浏览器中查看”，你可以在[Conflux Scan](https://evm.confluxscan.io)上查看更多细节。

### 接收加密资产

为了将 CFX 和 ERC20 代币接收到您的 Ledger 钱包账户中，只需从 MetaMask 中复制您的地址并与发送方分享即可。 你只需要在发送资金时使用你的Ledger设备签名交易，而在接收资金时不需要签名交易。 MetaMask在“账户详情”下也可以为您提供易于使用的二维码。

### 获取CFX

有多种方法可以在 Conflux eSpace 上获得 CFX 和其他代币。

- 你可以通过多个中心化交易所(例如[KuCoin](https://www.kucoin.com))获取CFX并提取到Conflux eSpace。
- 你也可以使用去中心化交易所，如[Swappi](https://app.swappi.io/#/swap)进行交易。
- 最后，您还可以通过跨链应用程序，例如[Multichain](https://app.multichain.org/#/router)，[meson.fi](https://meson.fi/)，[cBridge](https://cbridge.celer.network/#/transfer)或[Conflux eSpace Bridge](https://confluxhub.io/espace-bridge)将加密资产从其他链转移到Conflux eSpace。


### 查看您的余额

最简单的检查您的Ledger账户中持有的CFX和ERC20代币余额的方法是在MetaMask中查看它们。

![conflux-app-in-ledger-live](./img/metamask-view-balance-9e558f0db402afa799f16d678e68c6e1.png)

另外一种查看您的Ledger账户中CFX和ERC20代币余额的方法是单击“在区块链浏览器中查看账户”，或者前往https://evm.confluxscan.net并手动搜索您的地址以查看您的代币余额和交易历史记录。

![conflux-app-in-ledger-live](./img/scan-view-balance-bf5b143069670feb9634e0b31c13296c.png)

