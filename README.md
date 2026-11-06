# Ath11k-Firmware-DDWRT
源码地址：

https://github.com/mirror/dd-wrt/tree/master/src/router/firmwares/wireless/ath11k

## 固件同步（2026-11-07）

DD-WRT 固定来源：[c5b9d5d25e10](https://github.com/mirror/dd-wrt/tree/c5b9d5d25e10c170419729b19b2e1a79d58871d4/src/router/firmwares/wireless/ath11k)。
对应的最近固件更新提交为 `8fce77470c94`。

IPQ9574 和 QCN9074 更新至 `WLAN.HK.2.15.0.1-00553-QCAHKSWPL_SILICONZ-1`；
IPQ5018、IPQ6018、IPQ8074 和 QCN9074 的板级数据库同步上游新增条目。
WCN6855 保留上游 `hw2.1 -> hw2.0` 目录映射。

各硬件目录均提供 `fw_version.txt`。可识别的版本与固件内嵌
`QC_IMAGE_VERSION_STRING` 核对；QCN9074 修正了上游文本中的过期版本号。
QCN6122 仅包含 M3 载荷，其版本沿用已有来源元数据，文件中已注明这一限制。
