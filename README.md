Read this in other languages: [English](README.md), [日本語](README.ja.md)

# SiTCP Netlist for Kintex7

SiTCP Library (ngc file and EDIF file) for Xilinx Kintex7.


## What is SiTCP

Simple TCP/IP implemented on an FPGA (Field Programmable Gate Array) for the purpose of transferring large amounts of data in physics experiments.

* For details, please refer to [SiTCP Library page](https://www.bbtech.co.jp/en/products/sitcp-library/).
* For other related projects, please refer to [here](https://github.com/BeeBeansTechnologies).

![SiTCP](sitcp.png)


## History

2013-10-18 Ver.8.0
* Added minimum IPG resistor (programmable range from 3 to 15).

2016-03-02 Ver.9.0
* Added MAC address output port

2017-03-23 Ver.10.0
* RX bug fixed

2017-06-09 Ver.11.0
* Modified for corresponding to the pause frame(IEEE802.3x flow control).
* Arp request function added in Client mode.
* SiTCP_RST modified.
* Change of ACK transmission method.
* MIF Initialization modified.

2024-01-16 Ver.11.0-release2
* Added SiTCP_XC7K_32K_BBT_V110.edf
* Added EDF_SiTCP.xdc