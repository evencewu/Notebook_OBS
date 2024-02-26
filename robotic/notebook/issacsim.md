### issac SDK
```cardlink
url: https://docs.omniverse.nvidia.com/py/isaacsim/source/extensions/omni.isaac.dynamic_control/docs/index.html
title: "Dynamic Control [omni.isaac.dynamic_control] — isaac_sim 2023.1.1-rc.7 documentation"
host: docs.omniverse.nvidia.com
```
```cardlink
url: https://docs.omniverse.nvidia.com/extensions/latest/index.html
title: "Extensions Overview — Omniverse Extensions latest documentation"
host: docs.omniverse.nvidia.com
```

---
# 目录
[[IssacSim Core API]]
# QA

## 关于issacsim的扭矩控制

	![[Pasted image 20240108193503.png]]

## 2023.1.1版本urdf导入后usd无法使用ros插件的问题
	![[Pasted image 20240207230152.png]]
	Q: 如何解决
	A:  NV论坛：需要使用2022.1.1版本的urdf插件转换

#todo
- [x] 可行性验证

---

## 关于xacro转urdf
``` bash
ros2 run xacro xacro r2d.urdf.xacro > r2d.urdf
```