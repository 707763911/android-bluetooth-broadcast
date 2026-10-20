# Android Bluetooth Broadcast

Android 蓝牙广播、设备发现与状态管理的通用工程实现。仓库内不包含企业真实广播格式、客户数据或密钥。

## 功能
- 经典蓝牙发现流程【作为后台服务，能做到稳定被发现】
- BLE Advertising 实现入口
- 广播数据构造器可替换
- Android 12+ 蓝牙/附近设备权限适配
- 设备列表与连接状态展示
- 统一日志与错误回调

## 技术栈
Kotlin / Java、Android SDK、BluetoothAdapter、BluetoothLeAdvertiser

## 快速开始
1. 使用 Android Studio 打开项目
2. 授予蓝牙/附近设备权限
3. 运行后开启广播或扫描

## 安全与合规
- 广播数据为脱敏合成数据
- 不包含企业私有协议字段
- 不采集真实用户设备信息

## License
MIT
