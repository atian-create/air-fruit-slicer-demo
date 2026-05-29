# 远程切水果 Demo

一个整只手体感切水果原型，现在偏向 5 分钟久坐唤醒运动。

## 线上体验

- Website: https://atian-create.github.io/air-fruit-slicer-demo/
- GitHub: https://github.com/atian-create/air-fruit-slicer-demo

## 打开

```bash
cd /Users/tianyi/Documents/阿甜本地知识库/业务整理和扩展/air-fruit-slicer-demo
python3 -m http.server 5178
```

然后打开：

```text
http://localhost:5178/
```

## 玩法

- 摄像头识别整只手中心，不追踪单根手指。
- 默认是一轮 5 分钟倒计时运动。
- 分为热身、主运动、冲刺、放松四段。
- 屏幕会指定目标水果和目标区域，例如左侧、右上、左下。
- 屏幕会指定目标水果，先切对目标才加分。
- 连续命中 3 个目标后自动切换下一种水果。
- 误切其他水果会断连击并扣少量分。
- 水果数量更少、尺寸更大，更适合隔空挥手。
- 动作越快，刀光越亮越宽。
- 结束后显示挥手次数、活跃时间、左右平衡、最高连击等统计。
- 鼠标/触摸也可拖动切水果。

## 后续可加

- 炸弹：切到扣分。
- 双手大招：两只手同时横扫清屏。
- 慢动作：连续切 5 个后触发。
- 真实水果图片/3D 水果。
- 关卡和 60 秒挑战模式。

## License

MIT
