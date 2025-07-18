# 中文 | [English](https://github.com/Siriling/5G-Modem-Support/blob/main/EngLish.md) | [Русский](https://github.com/Siriling/5G-Modem-Support/blob/main/Russian.md)

# luci-app-modem

## Оглавление

- [1. Описание](#1-описание)
- [2. Поддерживаемые модемы](#2-поддерживаемые-модемы)

## 1. Описание

- Поддержка модемов с интерфейсами USB и PCIe
- Возможность настройки нескольких модемов для одновременного использования
- Поддержка IPv6
- Совместимость с модемами на платформах Qualcomm, UNISOC, MediaTek
- Поддержка популярных производителей модемов (например: Quectel, Fibocom и др.)

## 2. Поддерживаемые модемы

Ниже перечислены модемы, поддерживаемые данным плагином:

| Производитель | Название модема                                    | Платформа   | Режим передачи данных | Тип интерфейса               |
| ------------- | -------------------------------------------------- | ----------- | --------------------- | ---------------------------- |
| Quectel       | RG200U-CN (версия DONGLE)                          | UNISOC      | USB                   | ECM, MBIM, RNDIS, NCM        |
| Quectel       | RM500U-CN                                          | UNISOC      | USB                   | ECM, MBIM, RNDIS, NCM        |
| Quectel       | RM500U-EA                                          | UNISOC      | USB                   | ECM, MBIM, RNDIS, NCM        |
| Quectel       | RM500U-CNV                                         | UNISOC      | USB                   | ECM, MBIM, RNDIS, NCM        |
| Quectel       | RM500Q-CN                                          | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel       | RM500Q-AE                                          | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel       | RM500Q-GL                                          | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel       | RM502Q-AE                                          | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel       | RM502Q-GL                                          | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel       | RM505Q-AE                                          | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel       | RM520N-CN                                          | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel       | RM520N-GL                                          | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel       | RM500Q-GL                                          | Qualcomm    | PCIe                  | RMNET, MBIM                  |
| Quectel       | RG500Q-EA                                          | Qualcomm    | PCIe                  | RMNET, MBIM                  |
| Quectel       | RM502Q-GL                                          | Qualcomm    | PCIe                  | RMNET, MBIM                  |
| Quectel       | RM520N-GL                                          | Qualcomm    | PCIe                  | RMNET, MBIM                  |
| Quectel       | RG520N-EU                                          | Qualcomm    | PCIe                  | RMNET, MBIM                  |
| Fibocom       | FM650-CN                                           | UNISOC      | USB                   | ECM, MBIM, RNDIS, NCM        |
| Fibocom       | FM350-GL                                           | MediaTek    | USB                   | RNDIS                        |
| Fibocom       | FM150-AE-01, FM150-AE-11, FM150-AE-21, FM150-NA-01 | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |
| Fibocom       | FM350-GL                                           | MediaTek    | PCIe                  | MBIM                         |
| Fibocom       | FM150-AE-00, FM150-AE-10, FM150-AE-20, FM150-NA-00 | Qualcomm    | PCIe                  | QMI                          |
| Meig Smart    | SRM815                                             | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |
| Meig Smart    | SRM825                                             | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |
| Meig Smart    | SRM825N                                            | Qualcomm    | USB                   | RMNET, ECM, MBIM, RNDIS, NCM |

