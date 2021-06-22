
Android 蓝牙示例
===================================

此示例显示如何在两个Android设备之间实现通过蓝牙的双向文本聊天。

Introduction
------------

此示例应同时在两个Android设备上运行，以建立双向聊天设备之间的蓝牙。 在一个设备上选择“Made discoverable”，然后单击在另一个上的蓝牙图标上，找到设备并建立连接。

示例中用的[Bluetooth API][1]:

1. [Setting up][2] Bluetooth
2. [Scanning][3] for other Bluetooth devices
3. [Querying][4] the local Bluetooth adapter for paired Bluetooth devices
4. [Establishing RFCOMM][5] channels/sockets
5. [Connecting][6] to a remote device
6. [Transfering][7] data over Bluetooth

[1]: http://developer.android.com/guide/topics/connectivity/bluetooth.html
[2]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#Permissions
[3]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#FindingDevices
[4]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#QueryingPairedDevices
[5]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#ConnectingDevices
[6]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#ConnectingAsAClient
[7]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#ManagingAConnection

Pre-requisites
--------------

- Android SDK 28
- Android Build Tools v28.0.3
- Android Support Repository

Screenshots
-------------

<img src="screenshots/1-launch.png" height="400" alt="Screenshot"/> <img src="screenshots/2-devices.png" height="400" alt="Screenshot"/> <img src="screenshots/3-chat.png" height="400" alt="Screenshot"/> 

Getting Started
---------------

