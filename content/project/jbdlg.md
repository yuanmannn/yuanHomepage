---
date: '2024-08-25T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: ''
draft: false # set to "true" if you want to hide the content 
description: '纪录片《布达拉宫·时空解码》'
video: "videos/bdlg.mp4"

params:
    image:
        src: "images/works/bdlg.png"
        scale: 0.5

projectTitle: "纪录片《布达拉宫·时空解码》"
duration: "2024.08-2025.09"
    

---


### 项目概述

纪录片《布达拉宫·时空解码》创新运用XR虚拟拍摄技术，以真实游览路线为叙事脉络，带领观众沉浸式探访未开放殿宇，通过数字技术动态还原建筑1300年的演变历程，实现历史文献与视觉科技的深度融合。<br>
纪录片视频地址：[《布达拉宫·时空解码》](https://www.miguvideo.com/p/detail/959184199?lastLocation=b1c29dcd91f94a0289bf6295140f43b2%23bfde657872134824ad46f6e67ce43bd5%23c1950db6b5ea42bca35a4d2d48494850)

### 技术实现

##### UE5·虚拟制片
- 使用Nanite虚拟化几何体处理过亿面数的扫描建筑模型，结合Lumen全局光照模拟日光环境
- 运用青瞳视觉光学动捕设备采集喇嘛诵经、跪拜等民俗动作数据，通过 Control Rig 重定向至UE5角色骨骼，修复拓扑差异导致的关节形变问题
- 设计动画蒙太奇逻辑，基于UE5动画蓝图实现环境事件触发（如钟声→跪拜动画），支持动作与场景的实时交互
- 结合EmberGen软件和Niagara系统模拟香炉烟雾特效，通过GPU Spawn事件控制粒子密度
- 实现多机位实时切换蓝图功能



### 项目成果
- 开创XR技术全程应用新范式，实现建筑演进史动态可视化还原
- 构建沉浸式文化体验，成功触达年轻受众群体
- 打造"科技+文化"融合标杆案例，推动行业创新发展
- 深化民族团结主题阐释，展现汉藏文化交融印记


---

*项目周期: 2024年8月 - 2025年9月*  