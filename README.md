# Power Policy Settings

## none

### 唤醒时需要密码
当计算机从睡眠状态唤醒时，需要使用密码以解除锁定


### 电源计划类型
默认的 Windows 电源计划类型包括“平衡”、“节能”和“高性能”。这三种类型设计用于在提供所需性能的同时平衡电源节省量、最大限度的节能或最大化性能。许多系统组件使用电源计划类型决定是优化电源节省量还是优化性能


### 设备空闲策略
指定系统运行时用于关闭设备的策略


### 断开连接待机模式
指定断开连接待机模式


### 待机状态下的网络连接性
待机状态下的网络连接性


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 硬盘

### AHCI Link Power Management - HIPM/DIPM
配置 LPM 状态

Active/HIPM/HIPM+DIPM/DIPM/Lowest

**Active**为性能档


### APST ITPT for non-operational power states (ms) on Hybrid Optane drive
APST ITPT，用于 Hybrid Optane 驱动器上的非运行电源状态 （ms）

0-60000(ms)

**0**为性能档


### 最大电量水平
指定存储设备不应超过的功耗水平

0-100(%)

**100**为性能档


### APST ITPT for non-operational power states (ms) on Hybrid Nand drive
APST ITPT 用于混合 Nand 驱动器上的非工作电源状态 （ms）

0-60000(ms)

**0**为性能档


### APST ITPT for non-operational power states (ms) on any NVMe drive
APST ITPT 适用于任何 NVMe 驱动器上的非运行电源状态 （ms）

0-60000(ms)

**0**为性能档


### 在此时间后关闭硬盘
指定关闭磁盘前硬盘驱动器处于非活动状态的时间

0-70999999(s)

**0**为性能档


### APST ITPT for operational power states (ms) on any NVMe drive
APST ITPT 适用于任何 NVMe 驱动器上的运行电源状态 （ms）

0-60000(ms)

**60000**为性能档


### 硬盘脉冲忽略时间
确定磁盘是否空闲时，忽略指定时间之前的磁盘活动脉冲

0-70999999(s)

**0**为性能档


### APST ITPT for operational power states (ms) on Hybrid Nand drive
APST ITPT 用于 Hybrid Nand 驱动器上的运行功率状态 （ms）

0-60000(ms)

**60000**为性能档


### APST ITPT for operational power states (ms) on Hybrid Optane drive
APST ITPT 用于 Hybrid Optane 驱动器上的运行功率状态 （ms）

0-60000(ms)

**60000**为性能档


### Secondary NVMe Idle Timeout
指定 NVMe 设备在过渡到辅助非工作电源状态之前必须处于主要非运行电源状态的时间量

0-60000(ms)

**60000**为性能档


### Primary NVMe Idle Timeout
指定 NVMe 设备在过渡到主要非运行电源状态之前必须处于空闲状态的时间

0-60000(ms)

**60000**为性能档


### AHCI Link Power Management - Adaptive
自动从 Partial 过渡到 Slumber

0-300000(ms)

**300000**为性能档


### Secondary NVMe Power State Transition Latency Tolerance
在 NVMe 设备处于主要非运行电源状态一段时间后，转换为 ENLAT+EXLAT 值小于或等于此设置指定值的最低非运行电源状态

0-60000(ms)

**0**为性能档


### NVMe NOPPME
启用或禁用 NVMe 非工作电源状态许可模式

On/Off

**On**为性能档


### Primary NVMe Power State Transition Latency Tolerance
当 NVMe 设备空闲一段时间后，转换为 ENLAT+EXLAT 值小于或等于此设置指定值的最低非运行电源状态

0-60000(ms)

**0**为性能档


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## Internet Explorer

### JavaScript 计时器频率


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 桌面背景设置

### 幻灯片放映
指定希望桌面背景幻灯片放映可用的时间


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 无线适配器设置

### 节能模式
控制无线适配器的节能模式


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />****

## 睡眠

### 旧 RTC 迁移
避免通过旧 RTC 唤醒警报从休眠中唤醒。同时，如果存在内部唤醒警报，请延迟休眠


### 允许离开模式策略
允许对计算机启用离开模式


### 在此时间后睡眠
指定计算机在进入睡眠状态前处于非活动状态的时间


### 无人参与系统睡眠超时
无人参与唤醒后，在系统返回到低电量睡眠状态之前，空闲超时


### 允许混合睡眠
允许 Windows 保存你的工作并进入低电源状态，以便你可以即时恢复工作


### 在此时间后休眠
指定在计算机休眠前处于非活动状态的时间。


### 允许使用系统所需的策略
允许程序阻止计算机自动进入睡眠状态


### 允许待机状态
允许 Windows 在计算机睡眠时使用待机状态


### 允许使用唤醒定时器
指定是否允许定时事件将计算机从睡眠状态唤醒


### 允许在远程打开的情况下进入睡眠状态
允许计算机在远程打开的文件尚未被写入时进入睡眠状态


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## USB设置

### Hub Selective Suspend Timeout
此值将用作所有 USB 集线器的空闲超时

0-100000(ms)

**0**为性能档


### USB 选择性暂停设置
指定是否启用或关闭 USB 选择性暂停功能

已启用/已禁用

**已禁用**为性能档


### Setting IOC on all TDs
是否应该为所有 TD 设置 IOC


### USB 3 Link Power Mangement
指定 USB 3 链路空闲时用于 USB 3 链路的电源管理策略

Off/Minimum power savings/Moderate power savings/Maximum power savings

**Off**为性能档


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 空闲复原

### 执行要求的电源请求的超时时间
指定执行要求的电源请求的超时时间


### IO 合并超时时间
指定 IO 合并超时时间


### 处理器空闲复原定时器精度
指定处理器空闲复原定时器精度


### 已启用/禁用深度睡眠
指定深度睡眠是否启用


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## ???

### ???


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 中断路由控制设置

### 中断路由控制模式
中断路由控制模式


### 目标负载
每个处理器的目标负载


### 已启动时间触发器
将中断移到处理器上之前，处理器必须保持启动状态的时间


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 电源按钮和盖子

### 合上盖子操作
指定合上移动电脑上的盖子时计算机要采取的操作


### 电源按钮操作
指定按电源按钮时要采取的操作


### 启用按钮/盖子强制关机
启用按钮操作和盖子操作的强制关机


### 睡眠按钮操作
指定按睡眠按钮时要采取的操作


### 打开盖子操作
指定打开盖子时要执行的操作


### 「开始」菜单电源按钮
指定按「开始」菜单电源按钮时要采取的操作


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## PCI Express

### 链接状态电源管理
指定链接空闲时用于可用链接的“活动状态电源管理(ASPM)”策略


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 处理器电源管理

<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 图形设置

### GPU 首选项策略
用以确定 GPU 首选项的策略


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 显示

### 以此时间后显示器变暗
指定计算机处于不活动状态多长时间显示器变暗


### 在此时间后关闭显示
指定关闭显示前计算机处于非活动状态的时间


### 高级色彩质量偏好
指定决定高级彩色显示器的视觉质量的策略


### 控制台锁定显示关闭超时
指定控制台锁定显示关闭超时


### 自适应显示
如果重复使用键盘或鼠标打开显示器，则可以延长 Windows 关闭显示器的等待时间


### 允许使用显示器所需的策略
允许程序阻止显示器自动关闭


### 显示器亮度
指定显示器的普通亮度级别


### 显示器亮度变暗
指定显示器变暗时的亮度级别


### 启用自适应亮度
监视环境光传感器，以检测环境光的改变，并调整显示亮度


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 状态感知电源操作

### 人存在传感器自适应离开显示超时
指定在人像状态感官指示用户未显示时显示超时


### 待机保留时间
指定在采取适应性措施之前，电池电量级别应允许的最短有效使用时间


### 待机重置百分比
指定可重置自适应预算的电池电量百分比


### 非传感器输入状态超时
指定非传感器输入状态超时


### 待机预算宽限期
指定当系统已超出其待机预算时，在采取适应性措施之前的宽限期


### 用户状态预测模式
为计算机指定用户状态预测模式


### 待机预算百分比
指定系统在待机状态下每个时间单位允许使用的电池电量百分比


### 人存在传感器自适应离开变暗超时
指定在人存在传感器指示用户不在后的变暗超时


### 待机保留宽限期
指定当系统低于保留电池电量级别时，在采取适应性措施之前的宽限期


### 人存在传感器自适应无人变暗超时
指定在有人状态传感器发出用户未注意的信号后的变暗超时


### 人存在传感器自适应无人显示超时
指定在人存在传感器指示用户离开后的显示超时


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## “多媒体”设置

### 共享媒体时
指定当设备或计算机播放来自你的计算机的媒体时，你的计算机所执行的操作


### 视频播放质量补偿
指定策略以补偿视频播放质量


### 播放视频时
计算机的视频播放管道使用的电源优化模式


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 节能模式设置

### 显示器亮度权重
指定打开节能模式时用于亮度调整的百分比值


### 节能模式策略
指定用于控制节能模式的策略


### 电池电量
指定打开节能模式时的电池电量


<img width="200%" src="https://cdn.jsdelivr.net/gh/Plasma4004/Plasma4004/assets/images/hr.gif" />

## 电池

### 低电池电量通知
指定是否在电量达到临界水平时显示通知


### 关键级别电池操作
指定当电池容量到达关键级别时要采取的操作


### 电池电量水平低
启动低电量操作时的电池剩余容量百分比


### 关键电池电量水平
启动关键电池操作的剩余电池容量百分比


### 低电量通知
指定当电池容量到达低水平时是否显示通知


### 低电量操作
指定当电池容量到达低水平时计算机要采取的操作


### 保留电池电量
启动保留电量模式时的剩余电池电量百分比

