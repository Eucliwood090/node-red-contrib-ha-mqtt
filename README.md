# ha-mqtt
在HomeAssistant生成MQTT实体

参考文档：https://www.home-assistant.io/docs/mqtt/discovery/

## 支持组件
- [x] alarm_control_panel - 警报面板
- [x] binary_sensor - 二元传感器
- [x] camera - 摄像头
- [x] climate - 空调
- [x] cover - 窗帘
- [x] device_tracker - 设备检测
- [x] device_automation - 设备自动化
- [x] fan - 风扇
- [x] humidifier - 加湿器
- [x] light - 灯
- [x] lock - 锁
- [x] number - 数字
- [x] scene - 场景
- [x] select - 选择器
- [x] sensor - 传感器
- [x] switch - 开关
- [x] tag - 标签
- [x] vacuum - 扫地机器人

自动发现
```yaml
topic: homeassistant/status
payload: online
```

## 如果这个项目对你有帮助，请我喝杯<del style="font-size: 14px;">咖啡</del>奶茶吧😘
|支付宝|微信|
|---|---|
<img src="https://github.com/shaonianzhentan/ha-docs/raw/master/docs/img/alipay.png" align="left" height="160" width="160" alt="支付宝" title="支付宝">  |  <img src="https://github.com/shaonianzhentan/ha-docs/raw/master/docs/img/wechat.png" align="left" height="160" width="160" alt="微信支付" title="微信">