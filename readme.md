# MSI-MAG-B460M-MORTAR

## 配置
|     -       |                                     |
| -----------|---------------------------------------|
| BIOS       | 7C82v15(2021-10-18)                   |
| OS         | macOS 15.4.1                            |
| Mobo       | MSI-MAG-B460M-MORTAR                  |
| CPU        | i5-10400F                              |
| RAM        | Kingbank REN DDR4 3600  16GBx2        |
| GPU        | 迪兰 RX460 4G                          |
| Network    | Realtek PCIe 2.5Gb Ethernet (RTL8125) |
| Disk       | 铠侠RC20 1T                           |
| Input      | RK 98                                 |


## 更新日志
1. 更新opencore 1.0.4
2. 更新其他驱动
3. 支持macOS 15.4.1


## BIOS 设置
### 1. Settings/高级/PCle/PCl子系统设置
- Above 4G memory/Crypto Currency mining -> 禁止
- Re-Size BAR Support -> 禁止

### 2. Settings/高级/整合周边设置/SATA设置
- SATA模式 -> AHCI 模式

### 3. Settings/高级/USB 设置
- XHCl Hand-off ->允许

### 4. Settings/高级
- BIOS CSM/UEFI Mode -> UEFI
- D.T.M -> 启用

### 5. Settings/启动
- 快速开机 ->禁止

### 6. Settings/安全/安全引导
- 安全启动 ->禁止

### 7. Settings/安全/Trusted Computing
- Security Device Support ->禁止

### 8. Overclocking/CPU 特征
- Intel 虚拟化技术 ->允许
- Intel VT-D 技术 ->禁止
- CFG 锁定 -> 禁止
- SW Guard Extensions(SGX)->禁止
