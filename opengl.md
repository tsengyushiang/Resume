# OpenGL

## RGBD Camera viewer

### [source code](https://github.com/tsengyushiang/Azurekinect-OpenGL-Viewer)


使用OpenGL搭配imgui 2D介面, 同時繪製多台 RGBD Camera的影像、點雲, 並利用 cuda 加速效能...

- RGBD Camera API 使用 : 支援 Azure Kinect, Realsense.
- 多台相機對齊 : 手動拖曳, OpenCV Aruco Marker 取得3D feature points.

| 介面 |多台相機點雲|
| ----------------- | -------------- |
| ![1](./images/azruekinect-viewer-interface.png)|![2](./images/azruekinect-viewer-pointcloud.gif) |

## 機器人

### [source code](https://github.com/tsengyushiang/CG-P1)

使用OpenGL 內建基礎形狀繪製機器人，產生各個身體部位依序繪製，並使用階層式的矩陣完成動畫，再套用uv繪製貼圖
  
### 動畫

||||||||
| ----------------- | -------------- | --------- | --------- | --------- | --------- | --------- |
| ![1](./images/CG01_anime1.png)|![2](./images/CG01_anime2.png) |![3](./images/CG01_anime3.png) |![4](./images/CG01_anime4.png) |![5](./images/CG01_anime5.png) |![6](./images/CG01_anime6.png) |

### 貼圖

||||
| ----------------- | -------------- | --------- |
| ![1](./images/CG01_texture01.png)|![2](./images/CG01_texture02.png) |![3](./images/CG01_texture03.png) |

## OpenMesh貼圖

### [source code](https://github.com/tsengyushiang/CG-P2)

使用OpenMesh 將載入的obj檔套用其資料結構獲得 vertex, edge, face資訊，並透過反算相機矩陣選面，將選取範圍中的面參數化產生uv，最後貼上對應的貼圖。
   
| 參數化結果 | 貼上貼圖 | 成品 |
| ----------------- | -------------- | --------- |
| ![1](./images/CG02_param01.png)| ![2](./images/CG02_param02.png) |![3](./images/CG02_param03.png) |

## Shader特效

### [source code](https://github.com/tsengyushiang/CG-P3)

讀取obj檔的資訊和模型矩陣傳入vertexShader做機器人動畫表演，搭配fragmentShader與framebuffer做畫面和貼圖的post processing，完成特效。


| Toon  |Swirl distortion|CRT|Chromatic Aberration|
| ----------------- | -------------- | --------- | --------- |
| ![1](./images/CG03_shader01.png)|![2](./images/CG03_shader02.png) |![3](./images/CG03_shader03.jpg) |![4](./images/CG03_shader04.png) |

| 特效貼圖 |||
| ----------------- | -------------- | --------- |
| ![5](./images/CG03_shader05.png) |![6](./images/CG03_shader06.png) |![6](./images/CG03_shader07.png) |
