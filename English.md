# 中文 | [English](https://github.com/Siriling/5G-Modem-Support/blob/main/EngLish.md) | [Русский](https://github.com/Siriling/5G-Modem-Support/blob/main/Russian.md)

# luci-app-modem

## Table of Contents

- [1. Description](#1-description)
- [2. Supported Modules](#2-supported-modules)

## 1. Description

- Supports communication modules with USB and PCIe interfaces
- Supports configuring multiple communication modules for dial-up
- Supports IPv6
- Supports communication modules based on Qualcomm, UNISOC, and MediaTek platforms
- Supports popular module vendors (e.g., Quectel, Fibocom, etc.)

## 2. Supported Modules

The following modules are supported by the plugin:

| Manufacturer | Module Name                                        | Platform   | Data Transfer Mode | Port Mode                      |
| ------------ | -------------------------------------------------- | ---------- | ------------------ | ------------------------------ |
| Quectel      | RG200U-CN (DONGLE version)                         | UNISOC     | USB                | ECM, MBIM, RNDIS, NCM          |
| Quectel      | RM500U-CN                                          | UNISOC     | USB                | ECM, MBIM, RNDIS, NCM          |
| Quectel      | RM500U-EA                                          | UNISOC     | USB                | ECM, MBIM, RNDIS, NCM          |
| Quectel      | RM500U-CNV                                         | UNISOC     | USB                | ECM, MBIM, RNDIS, NCM          |
| Quectel      | RM500Q-CN                                          | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |
| Quectel      | RM500Q-AE                                          | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |
| Quectel      | RM500Q-GL                                          | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |
| Quectel      | RM502Q-AE                                          | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |
| Quectel      | RM502Q-GL                                          | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |
| Quectel      | RM505Q-AE                                          | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |
| Quectel      | RM520N-CN                                          | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |
| Quectel      | RM520N-GL                                          | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |
| Quectel      | RM500Q-GL                                          | Qualcomm   | PCIE               | RMNET, MBIM                    |
| Quectel      | RG500Q-EA                                          | Qualcomm   | PCIE               | RMNET, MBIM                    |
| Quectel      | RM502Q-GL                                          | Qualcomm   | PCIE               | RMNET, MBIM                    |
| Quectel      | RM520N-GL                                          | Qualcomm   | PCIE               | RMNET, MBIM                    |
| Quectel      | RG520N-EU                                          | Qualcomm   | PCIE               | RMNET, MBIM                    |
| Fibocom      | FM650-CN                                           | UNISOC     | USB                | ECM, MBIM, RNDIS, NCM          |
| Fibocom      | FM350-GL                                           | MediaTek   | USB                | RNDIS                          |
| Fibocom      | FM150-AE-01, FM150-AE-11, FM150-AE-21, FM150-NA-01 | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |
| Fibocom      | FM350-GL                                           | MediaTek   | PCIE               | MBIM                           |
| Fibocom      | FM150-AE-00, FM150-AE-10, FM150-AE-20, FM150-NA-00 | Qualcomm   | PCIE               | QMI                            |
| Meige        | SRM815                                             | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |
| Meige        | SRM825                                             | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |
| Meige        | SRM825N                                            | Qualcomm   | USB                | RMNET, ECM, MBIM, RNDIS, NCM   |

