Read this in other languages: [English](README.md), [日本語](README.ja.md)

# SiTCP Netlist for Kintex7

Xilinx Kintex7用のSiTCP Netlist File(ngc file および EDIF file)です。


## SiTCP とは

物理学実験での大容量データ転送を目的としてFPGA（Field Programmable Gate Array）上に実装されたシンプルなTCP/IPです。

* SiTCPについては、[SiTCPライブラリページ](https://www.bbtech.co.jp/products/sitcp-library/)を参照してください。
* その他の関連プロジェクトは、[こちら](https://github.com/BeeBeansTechnologies)を参照してください。

![SiTCP](sitcp.png)


## 履歴

2013-10-18 Ver.8.0
* IPGの最小値を3～15の範囲で設定可能にしました。

2016-03-02 Ver.9.0
* MACアドレス表示ポートを追加しました

2017-03-23 Ver.10.0
* 受信時のバグを修正しました

2017-06-09 Ver.11.0
* IEEE802.3xフローコントロール（PAUSE）に対応しました。
* クライアントモードでのARPリクエスト機能を追加しました。
* SiTCP_RSTのタイミングを変更しました（EEPROM設定値の転送完了まで延長）。
* データ受信時のACK送信形式を変更しました。
* MIF初期化機能を設定可能にしました。

2024-01-16 Ver.11.0-release2
* SiTCP_XC7K_32K_BBT_V110.edfを追加しました。
* EDF_SiTCP.xdcを追加しました。