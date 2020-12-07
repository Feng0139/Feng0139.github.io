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
| :----- | :-----: | :-----: |
| eyeBlinkLeft      | 描述左眼上眼睑闭合的系数 | <img src="./img/2020-12-07/eyeBlinkLeft.png" width = 300px> |
| eyeLookDownLeft   | 描述左眼皮运动与向下凝视一致的系数 | <img src="./img/2020-12-07/eyeLookDownLeft.png" width = 300px> |
| eyeLookInLeft     | 描述左眼皮运动与右眼注视一致的系数 | <img src="./img/2020-12-07/eyeLookInLeft.png" width = 300px> |
| eyeLookOutLeft    | 描述左眼皮运动与左眼注视一致的系数 | <img src="./img/2020-12-07/eyeLookOutLeft.png" width = 300px> |
| eyeLookUpLeft     | 描述左眼皮运动与向上注视一致的系数 | <img src="./img/2020-12-07/eyeLookUpLeft.png" width = 300px> |
| eyeSquintLeft     | 描述左眼周围脸部收缩的系数 | <img src="./img/2020-12-07/eyeSquintLeft.png" width = 300px> |
| eyeWideLeft       | 描述左眼周围眼睑变宽的系数 | <img src="./img/2020-12-07/eyeWideLeft.png" width = 300px> |

## 右眼
| 系数 | 说明 | 示例图 |
| :----- | :-----: | :-----: |
| eyeBlinkRight     | 描述右眼上眼睑闭合的系数          | <img src="./img/2020-12-07/eyeBlinkRight.png" width = 300px> |
| eyeLookDownRight  | 描述右眼皮运动与向下凝视一致的系数 | <img src="./img/2020-12-07/eyeLookDownRight.png" width = 300px> |
| eyeLookInRight    | 描述右眼皮运动与左眼注视一致的系数 | <img src="./img/2020-12-07/eyeLookInRight.png" width = 300px> |
| eyeLookOutRight   | 描述右眼皮与向右注视一致的系数     | <img src="./img/2020-12-07/eyeLookOutRight.png" width = 300px> |
| eyeLookUpRight    | 描述右眼皮运动与向上注视一致的系数 | <img src="./img/2020-12-07/eyeLookUpRight.png" width = 300px> |
| eyeSquintRight    | 描述右眼周围脸部收缩的系数         | <img src="./img/2020-12-07/eyeSquintRight.png" width = 300px> |
| eyeWideRight      | 描述右眼周围眼睑变宽的系数        | <img src="./img/2020-12-07/eyeWideRight.png" width = 300px> |

## 嘴唇与上下颚
| 系数 | 说明 | 示例图 |
| :----- | :-----: | :-----: |
| jawForward            | 描述下颌向前运动的系数 | <img src="./img/2020-12-07/jawForward.png" width = 300px> |
| jawLeft               | 描述下颚向左移动的系数 | <img src="./img/2020-12-07/jawLeft.png" width = 300px> |
| jawRight              | 描述下颌向右运动的系数 | <img src="./img/2020-12-07/jawRight.png" width = 300px> |
| jawOpen               | 描述下颚张开的系数 | <img src="./img/2020-12-07/jawOpen.png" width = 300px> |
| mouthClose            | 该系数表示嘴唇的闭合与下颌的位置（系数）无关，因此，除非将其他系数也设置为真实值，否则该系数的某些值可能会产生不真实的面部表情 | <img src="./img/2020-12-07/mouthClose.png" width = 300px> |
| mouthFunnel           | 描述双唇收缩成开放形状的系数 | <img src="./img/2020-12-07/mouthFunnel.png" width = 300px> |
| mouthPucker           | 描述两个闭合嘴唇的收缩和压缩的系数 | <img src="./img/2020-12-07/mouthPucker.png" width = 300px> |
| mouthLeft             | 描述双唇一起向左移动的系数 | <img src="./img/2020-12-07/mouthLeft.png" width = 300px> |
| mouthRight            | 描述双唇一起向右运动的系数 | <img src="./img/2020-12-07/mouthRight.png" width = 300px> |
| mouthSmileLeft        | 描述嘴左角向上运动的系数 | <img src="./img/2020-12-07/mouthSmileLeft.png" width = 300px> |
| mouthSmileRight       | 描述嘴右角向上运动的系数 | <img src="./img/2020-12-07/mouthSmileRight.png" width = 300px> |
| mouthFrownLeft        | 描述嘴左角向下运动的系数 | <img src="./img/2020-12-07/mouthFrownLeft.png" width = 300px> |
| mouthFrownRight       | 描述嘴右角向下运动的系数 | <img src="./img/2020-12-07/mouthFrownRight.png" width = 300px> |
| mouthDimpleLeft       | 描述嘴左角向后移动的系数 | <img src="./img/2020-12-07/mouthDimpleLeft.png" width = 300px> |
| mouthDimpleRight      | 描述嘴右角向后移动的系数 | <img src="./img/2020-12-07/mouthDimpleRight.png" width = 300px> |
| mouthStretchLeft      | 描述嘴左角向左移动的系数 | <img src="./img/2020-12-07/mouthStretchLeft.png" width = 300px> |
| mouthStretchRight     | 描述嘴左角向右移动的系数 | <img src="./img/2020-12-07/mouthStretchRight.png" width = 300px> |
| mouthRollLower        | 描述下唇向口腔内部运动的系数 | <img src="./img/2020-12-07/mouthRollLower.png" width = 300px> |
| mouthRollUpper        | 描述上唇向口内运动的系数 | <img src="./img/2020-12-07/mouthRollUpper.png" width = 300px> |
| mouthShrugLower       | 描述下唇向外运动的系数 | <img src="./img/2020-12-07/mouthShrugLower.png" width = 300px> |
| mouthShrugUpper       | 描述上唇向外移动的系数 | <img src="./img/2020-12-07/mouthShrugUpper.png" width = 300px> |
| mouthPressLeft        | 描述左侧下唇向上压缩的系数 | <img src="./img/2020-12-07/mouthPressLeft.png" width = 300px> |
| mouthPressRight       | 描述右侧下唇向上压缩的系数 | <img src="./img/2020-12-07/mouthPressRight.png" width = 300px> |
| mouthLowerDownLeft    | 描述左侧下唇向下运动的系数 | <img src="./img/2020-12-07/mouthLowerDownLeft.png" width = 300px> |
| mouthLowerDownRight   | 描述右侧下唇向下运动的系数 | <img src="./img/2020-12-07/mouthLowerDownRight.png" width = 300px> |
| mouthUpperUpLeft      | 描述左侧上唇向上运动的系数 | <img src="./img/2020-12-07/mouthUpperUpLeft.png" width = 300px> |
| mouthUpperUpRight     | 描述右侧上唇向上运动的系数 | <img src="./img/2020-12-07/mouthUpperUpRight.png" width = 300px> |

## 眉毛、脸颊、鼻子
| 系数 | 说明 | 示例图 |
| :----- | :-----: | :-----: |
| browDownLeft | 描述左眉外部向下运动的系数 | <img src="./img/2020-12-07/browDownLeft.png" width = 300px> |
| browDownRight | 描述右眉外部向下运动的系数 | <img src="./img/2020-12-07/browDownRight.png" width = 300px> |
| browInnerUp | 描述两个眉毛内部向上运动的系数 | <img src="./img/2020-12-07/browInnerUp.png" width = 300px> |
| browOuterUpLeft | 描述左眉外部向上运动的系数 | <img src="./img/2020-12-07/browOuterUpLeft.png" width = 300px> |
| browOuterUpRight | 描述右眉外部向上运动的系数 | <img src="./img/2020-12-07/browOuterUpRight.png" width = 300px> |
| cheekPuff | 描述两个脸颊向外运动的系数 | <img src="./img/2020-12-07/cheekPuff.png" width = 300px> |
| cheekSquintLeft | 描述脸颊在左眼周围和下方向上运动的系数 | <img src="./img/2020-12-07/cheekSquintLeft.png" width = 300px> |
| cheekSquintRight | 描述脸颊在右眼周围和下方向上运动的系数 | <img src="./img/2020-12-07/cheekSquintRight.png" width = 300px> |
| noseSneerLeft | 该系数描述了鼻孔周围鼻子左侧的隆起 | <img src="./img/2020-12-07/noseSneerLeft.png" width = 300px> |
| noseSneerRight | 该系数描述了鼻孔周围鼻子右侧的隆起 | <img src="./img/2020-12-07/noseSneerRight.png" width = 300px> |

## 舌
| 系数 | 说明 | 示例图 |
| :----- | :----- | :----- |
| tongueOut | 描述舌头伸展的系数 | NULL |