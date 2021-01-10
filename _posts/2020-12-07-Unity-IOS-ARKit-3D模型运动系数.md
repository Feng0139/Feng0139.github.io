---
layout:     post   				    # 使用的布局（不需要改）
title:      Unity-IOS-ARKit-3D模型运动系数	  		# 标题
subtitle:                   		#副标题
date:       2020-12-07 				# 时间
author:     Feng 					# 作者
header-img: img/post-bg-desk.jpg 	#这篇文章标题背景图片
catalog: true 						# 是否归档
tags:								#标签
    - Unity
    - ios
    - ARKit
---

# BlendShapeLocation
## 左眼

| 系数 | 说明 | 示例图 |
| -----: | :-----: | :-----: |
| eyeBlinkLeft      | 描述左眼上眼睑闭合的系数 | ![](./img/2020-12-07/eyeBlinkLeft.png) |
| eyeLookDownLeft   | 描述左眼皮运动与向下凝视一致的系数 | ![](./img/2020-12-07/eyeLookDownLeft.png) |
| eyeLookInLeft     | 描述左眼皮运动与右眼注视一致的系数 | ![](./img/2020-12-07/eyeLookInLeft.png) |
| eyeLookOutLeft    | 描述左眼皮运动与左眼注视一致的系数 | ![](./img/2020-12-07/eyeLookOutLeft.png) |
| eyeLookUpLeft     | 描述左眼皮运动与向上注视一致的系数 | ![](./img/2020-12-07/eyeLookUpLeft.png) |
| eyeSquintLeft     | 描述左眼周围脸部收缩的系数 | ![](./img/2020-12-07/eyeSquintLeft.png) |
| eyeWideLeft       | 描述左眼周围眼睑变宽的系数 | ![](./img/2020-12-07/eyeWideLeft.png) |

## 右眼

| 系数 | 说明 | 示例图 |
| -----: | :-----: | :-----: |
| eyeBlinkRight     | 描述右眼上眼睑闭合的系数          | ![](./img/2020-12-07/eyeBlinkRight.png) |
| eyeLookDownRight  | 描述右眼皮运动与向下凝视一致的系数 | ![](./img/2020-12-07/eyeLookDownRight.png) |
| eyeLookInRight    | 描述右眼皮运动与左眼注视一致的系数 | ![](./img/2020-12-07/eyeLookInRight.png) |
| eyeLookOutRight   | 描述右眼皮与向右注视一致的系数     | ![](./img/2020-12-07/eyeLookOutRight.png) |
| eyeLookUpRight    | 描述右眼皮运动与向上注视一致的系数 | ![](./img/2020-12-07/eyeLookUpRight.png) |
| eyeSquintRight    | 描述右眼周围脸部收缩的系数        | ![](./img/2020-12-07/eyeSquintRight.png) |
| eyeWideRight      | 描述右眼周围眼睑变宽的系数        | ![](./img/2020-12-07/eyeWideRight.png) |

## 嘴唇与上下颚

| 系数 | 说明 | 示例图 |
| -----: | :-----: | :-----: |
| jawForward            | 描述下颌向前运动的系数 | ![](./img/2020-12-07/jawForward.png) |
| jawLeft               | 描述下颚向左移动的系数 | ![](./img/2020-12-07/jawLeft.png) |
| jawRight              | 描述下颌向右运动的系数 | ![](./img/2020-12-07/jawRight.png) |
| jawOpen               | 描述下颚张开的系数 | ![](./img/2020-12-07/jawOpen.png) |
| mouthClose            | 该系数表示嘴唇的闭合与下颌的位置（系数）无关，因此，除非将其他系数也设置为真实值，否则该系数的某些值可能会产生不真实的面部表情 | ![](./img/2020-12-07/mouthClose.png) |
| mouthFunnel           | 描述双唇收缩成开放形状的系数 | ![](./img/2020-12-07/mouthFunnel.png) |
| mouthPucker           | 描述两个闭合嘴唇的收缩和压缩的系数 | ![](./img/2020-12-07/mouthPucker.png) |
| mouthLeft             | 描述双唇一起向左移动的系数 | ![](./img/2020-12-07/mouthLeft.png) |
| mouthRight            | 描述双唇一起向右运动的系数 | ![](./img/2020-12-07/mouthRight.png) |
| mouthSmileLeft        | 描述嘴左角向上运动的系数 | ![](./img/2020-12-07/mouthSmileLeft.png) |
| mouthSmileRight       | 描述嘴右角向上运动的系数 | ![](./img/2020-12-07/mouthSmileRight.png) |
| mouthFrownLeft        | 描述嘴左角向下运动的系数 | ![](./img/2020-12-07/mouthFrownLeft.png) |
| mouthFrownRight       | 描述嘴右角向下运动的系数 | ![](./img/2020-12-07/mouthFrownRight.png) |
| mouthDimpleLeft       | 描述嘴左角向后移动的系数 | ![](./img/2020-12-07/mouthDimpleLeft.png) |
| mouthDimpleRight      | 描述嘴右角向后移动的系数 | ![](./img/2020-12-07/mouthDimpleRight.png) |
| mouthStretchLeft      | 描述嘴左角向左移动的系数 | ![](./img/2020-12-07/mouthStretchLeft.png) |
| mouthStretchRight     | 描述嘴左角向右移动的系数 | ![](./img/2020-12-07/mouthStretchRight.png) |
| mouthRollLower        | 描述下唇向口腔内部运动的系数 | ![](./img/2020-12-07/mouthRollLower.png) |
| mouthRollUpper        | 描述上唇向口内运动的系数 | ![](./img/2020-12-07/mouthRollUpper.png) |
| mouthShrugLower       | 描述下唇向外运动的系数 | ![](./img/2020-12-07/mouthShrugLower.png) |
| mouthShrugUpper       | 描述上唇向外移动的系数 | ![](./img/2020-12-07/mouthShrugUpper.png) |
| mouthPressLeft        | 描述左侧下唇向上压缩的系数 | ![](./img/2020-12-07/mouthPressLeft.png) |
| mouthPressRight       | 描述右侧下唇向上压缩的系数 | ![](./img/2020-12-07/mouthPressRight.png) |
| mouthLowerDownLeft    | 描述左侧下唇向下运动的系数 | ![](./img/2020-12-07/mouthLowerDownLeft.png) |
| mouthLowerDownRight   | 描述右侧下唇向下运动的系数 | ![](./img/2020-12-07/mouthLowerDownRight.png) |
| mouthUpperUpLeft      | 描述左侧上唇向上运动的系数 | ![](./img/2020-12-07/mouthUpperUpLeft.png) |
| mouthUpperUpRight     | 描述右侧上唇向上运动的系数 | ![](./img/2020-12-07/mouthUpperUpRight.png) |

## 眉毛、脸颊、鼻子

| 系数 | 说明 | 示例图 |
| -----: | :-----: | :-----: |
| browDownLeft      | 描述左眉外部向下运动的系数 | ![](./img/2020-12-07/browDownLeft.png) |
| browDownRight     | 描述右眉外部向下运动的系数 | ![](./img/2020-12-07/browDownRight.png) |
| browInnerUp       | 描述两个眉毛内部向上运动的系数 | ![](./img/2020-12-07/browInnerUp.png) |
| browOuterUpLeft   | 描述左眉外部向上运动的系数 | ![](./img/2020-12-07/browOuterUpLeft.png) |
| browOuterUpRight  | 描述右眉外部向上运动的系数 | ![](./img/2020-12-07/browOuterUpRight.png) |
| cheekPuff         | 描述两个脸颊向外运动的系数 | ![](./img/2020-12-07/cheekPuff.png) |
| cheekSquintLeft   | 描述脸颊在左眼周围和下方向上运动的系数 | ![](./img/2020-12-07/cheekSquintLeft.png) |
| cheekSquintRight  | 描述脸颊在右眼周围和下方向上运动的系数 | ![](./img/2020-12-07/cheekSquintRight.png) |
| noseSneerLeft     | 该系数描述了鼻孔周围鼻子左侧的隆起 | ![](./img/2020-12-07/noseSneerLeft.png) |
| noseSneerRight    | 该系数描述了鼻孔周围鼻子右侧的隆起 | ![](./img/2020-12-07/noseSneerRight.png) |

## 舌

| 系数 | 说明 | 示例图 |
| -----: | :-----: | :-----: |
| tongueOut | 描述舌头伸展的系数 | NULL |