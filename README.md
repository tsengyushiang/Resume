# Tseng Yu Shiang 作品集
## WebGL(Threejs)

**線上3D實境賞屋系統**

<details>
<summary>
    利用Threejs 繪製出線上3D賞屋動畫, 並利用ReactJs製作簡易UI。
</summary>
</details>

| 動畫 ||
| ----------------- | -------------- |
| ![1](./images/anim-fp2fp.gif)| ![2](./images/anim-fp2orth.gif) |
| ![3](./images/anim-top2fp.gif)| ![4](./images/anim-top2orth.gif) |
| ![5](./images/anim-orth2fp.gif)| ![6](./images/anim-orth2perspective.gif) |

**飯店場地配置系統**

<details>
<summary>
    將環景圖及場地平面圖通過描框、調整牆壁位置、調整貼圖角度、輸入實際場地大小、放置物品等階段，製造出可於場地內以第一人稱自由走動的網頁
</summary>
</details>

|空間製作流程||
| ------------ | ------------- |
| ![1](./images/hotel360_sa.jpg)||
|調整桌椅位置 & 自由走動的viewer||
| ![3](./images/hotel360_editor.png) ![4](./images/hotel360_viewer.png)||
|輸出的貼圖及模型 方便人工修正||
| ![1](./images/hotel360_obj.png)||

## Cocos Creator

**卡牌遊戲前端**

<details>
<summary>
    使用Cocos Creator 製作卡牌遊戲-鬥地主前端，包含動畫、音效、介面、封包接送等等，前期自行以Nodejs撰寫測試用的後台，最終根據他們所提供的規格書串接對方後台，並使用unity uniwebview 插件接上遊戲大廳。
</summary>
</details>    

|鬥地主 ||
| ------------- | ------------- |
| ![1](./images/card_game3.jpg)  | ![2](./images/card_game2.jpg) |
| ![3](./images/card_game4.jpg) | ![4](./images/card_game1.jpg) |


**老虎機前端**

<details>
<summary>
    使用Cocos Creator 製作老虎機前端，包含動畫、音效、畫面、封包接送等等，根據合作公司的文件使用現有TypeScript程式框架, 最終階段透過mantis進行QA測試。
</summary>
</details>

|S127-HauntedMansion ||
| ------------- | ------------- |
| ![1](./images/127-HauntedMansion03.jpg)  | ![2](./images/127-HauntedMansion02.jpg) |
| ![3](./images/127-HauntedMansion01.jpg) | ![4](./images/127-HauntedMansion04.jpg) |

| S129 Orientaldragon ||||
| ----------------- | -------------- | --------- |--------- |
| ![1](./images/S129_Orientaldragon_Demo_Moment.jpg)| ![2](./images/S129_Orientaldragon_Demo_Moment2.jpg) |![3](./images/S129_Orientaldragon_Demo_Moment3.jpg) |![3](./images/S129_Orientaldragon_Demo_Moment4.jpg) |

## Unity2D/3D

**遊戲程式設計作業**
- 迷宮遊戲

    <details>
    <summary>
        使用unity3D遊戲引擎開發的一款遊戲，讓玩家透過簡單的提示字在迷宮找到出口，實做部分使用unity3D中的物理性質、UI、攝影機、粒子系統......等功能...
    </summary>
    
    <ul>
    <li>動畫 : 角色走路動畫、樹倒下的動畫、敵人走路攻擊動畫。</li>
    <li>UI : 關閉遊戲，重新遊戲、倒數計時畫面。</li>
    <li>光源 : 火把光源、死亡時的聚光燈。</li>
    <li>粒子系統 : 火把、光圈。</li>
    <li>場景 : 峽谷地形、星空skybox。</li>
    <li>攝影機 :  遊玩視角、小地圖視角。</li>
    <li>音效 : 背景音樂、攻擊聲、撿起道具聲、火把燃燒聲。</li>
    </ul>
    </details>

    | 峽谷地形 | 粒子效果 | 死亡畫面 | 遊玩畫面 |
    | ----------------- | -------------- | --------- | --------- |
    | ![1](./images/GP01_01.png)| ![2](./images/GP01_03.png) |![3](./images/GP01_05.png) | ![3](./images/GP01_06.png) |


- 多人連線2D遊戲

    <details>
    <summary>
        使用unity遊戲引擎開發的一款遊戲，通過發射子彈染色擊中的區域來佔領地盤，實做部分使用2D物理、圖片動畫、UI、連線......等功能...
    </summary>
    <ul>
    <li>物理 : 子彈打到物體後效果、單向門、子彈加速器。</li>
    <li>動畫: 用連續圖作敵人跳動動畫。</li>
    <li>連線 : 用Unet製作連線，同步玩家、時間、戰況。</li>
    <li>AssetBundle: 動態載入資源，方便更換圖片。</li>
    <li>Shader: 子彈特效，染色效果。</li>
    <li>UI: 連線介面。</li>
    </ul>
    </details>

    | 動畫 | 子彈特效 | 遊玩畫面 |
    | ----------------- | -------------- | --------- |
    | ![1](./images/GP02_01.png)| ![2](./images/GP02_02.png) |![3](./images/GP02_03.png) |

- Andriod 2D遊戲

    <details>
    <summary>
        使用unity遊戲引擎開發的一款遊戲，通過陀螺儀上下躲避躲避來車，及觸碰螢幕發射子彈來破壞車輛，實做部分使用陀螺儀、多點觸控......等功能..
    </summary>
    <ul>
    <li>陀螺儀: 控制角色上下移動。</li>
    <li>多點觸控: 發射子彈。</li>
    <li>存讀檔: 儲存得分。</li>
    </ul>
    </details>


    | 選單畫面 | 遊玩畫面 |
    | ------------- | ------------- |
    | ![教學影片](./images/GP03_01.png)  | ![選單畫面](./images/GP03_02.png) |

**遊戲企劃與設計原理作業-Boooom**
    
<details>
<summary>
    Boooom是用unity3D遊戲引擎開發的一款多人搶地盤遊戲，過程包含文件撰寫、開發程式、測試除錯到最後DEMO，實作部分包含主遊戲外，還有控制角色用的web-App...
</summary>

<ul>
<li>主遊戲 :主要核心玩法是透過丟水球佔領地盤，實作上使用shader更改vertex color再套用簡單的模糊遮罩，達到染色地板的效果。</li>
<li>控制器 : 開發使用unity3D遊戲引擎輸出webGL網頁，透過websocket傳輸簡單的上下左右、ready等資訊。</li>
<li><a href="https://www.youtube.com/watch?v=q7bf38KAHDw">遊戲介紹影片</a></li>
</ul>
</details>

|介紹影片 |選單畫面|
| ------------- | ------------- |
| ![1](./images/Boooom01.png)  | ![2](./images/Boooom03.png) |
|遊玩畫面 | 等待畫面|
| ![3](./images/Boooom04.png) | ![4](./images/Boooom05.png) |

**設計系合作專題-Looptopia**

<details>
<summary>
    與設計系同學合作，一款重現動物園動物「刻板行為」的網頁遊戲，讓更多人認識「刻板行為」，而「刻板行為」是指圈養動物因為壓力、孤立或無聊，而重複進行某個動作，例如籠子內不停的走來走去，重複的轉圈圈，或持續的咬某一個東西...
</summary>

<br>進入遊戲後，成為一隻不知名的生物，被困在柵欄中，身旁只有一截樹墩、一碗飼料。你沒有事情做，只能無聊地操作手把，上、下、左、右，你不斷繞圈、橫衝直撞，碰到柵欄才停下來，偶爾按幾下「點頭」按鈕。終於，在你耗盡耐心前，天色漸漸暗了，遊戲裡的一天結束了，遊戲會結束，玩家可以離開，但遊戲裡的生物卻必須留在無止盡的循環中——就像動物園的動物一樣。
    
<br>遊戲實做的部分使用Cocos Creator 構建前端介面及表演動畫，之後將路線資訊傳到由Google App Script 所建立的簡單後台，並透過 API 儲存於 Google sheet中。
</details>

|開始選單 |被困住的2分鐘時間|
| ------------- | ------------- |
| ![1](./images/Looptopia01.jpg)  | ![2](./images/Looptopia02.jpg) |
|重播2分鐘中所走的路徑 |所有歷史紀錄(走動動畫)|
| ![3](./images/Looptopia03.jpg) | ![4](./images/Looptopia04.jpg) |

## OpenGL

**RGBD Camera viewer**

<details>
<summary>
    使用OpenGL搭配imgui 2D介面, 同時繪製多台 RGBD Camera的影像、點雲, 並利用 cuda 加速效能...
</summary>
    <ul>
    <li>RGBD Camera API 使用 : Azure Kinect, Realsense</li>
    <li>多台相機對齊 : 手動拖曳, OpenCV Aruco Marker 取得3D feature points </li>
    </ul>
</details>

| 介面 |多台相機點雲|
| ----------------- | -------------- |
| ![1](./images/azruekinect-viewer-interface.png)|![2](./images/azruekinect-viewer-pointcloud.gif) |

**基礎電腦圖學作業**
- 機器人

    <details>
    <summary>
        使用OpenGL 內建基礎形狀繪製機器人，產生各個身體部位依序繪製，並使用階層式的矩陣完成動畫，再套用uv繪製貼圖
    </summary>        
    </details>

    | 動畫 |||||||
    | ----------------- | -------------- | --------- | --------- | --------- | --------- | --------- |
    | ![1](./images/CG01_anime1.png)|![2](./images/CG01_anime2.png) |![3](./images/CG01_anime3.png) |![4](./images/CG01_anime4.png) |![5](./images/CG01_anime5.png) |![6](./images/CG01_anime6.png) |

    | 貼圖 |||
    | ----------------- | -------------- | --------- |
    | ![1](./images/CG01_texture01.png)|![2](./images/CG01_texture02.png) |![3](./images/CG01_texture03.png) |

- Mesh貼圖

    <details>
    <summary>
        使用OpenMesh 將載入的obj檔套用其資料結構方便運算，並透過反算相機矩陣選面，將選取範圍中的面參數化產生uv，最後貼上對應的貼圖。
    </summary>        
    </details>

    | 參數化結果 | 貼上貼圖 | 成品 |
    | ----------------- | -------------- | --------- |
    | ![1](./images/CG02_param01.png)| ![2](./images/CG02_param02.png) |![3](./images/CG02_param03.png) |

- Shader特效

    <details>
    <summary>
        讀取obj檔的資訊和模型矩陣傳入vertexShader做機器人動畫表演，搭配fragmentShader與framebuffer做畫面和貼圖的post processing，完成特效。
    </summary>        
    </details>


    | Toon  |Swirl distortion|CRT|Chromatic Aberration|
    | ----------------- | -------------- | --------- | --------- |
    | ![1](./images/CG03_shader01.png)|![2](./images/CG03_shader02.png) |![3](./images/CG03_shader03.jpg) |![4](./images/CG03_shader04.png) |
    
    | 特效貼圖 |||
    | ----------------- | -------------- | --------- |
    | ![5](./images/CG03_shader05.png) |![6](./images/CG03_shader06.png) |![6](./images/CG03_shader07.png) |


## Unreal, IOS, Nodejs

**Unreal 第一人稱射擊遊戲**
<details>
<summary>
    使用Unreal遊戲引擎開發的第一人稱射擊遊戲，通過發射子彈來擊退敵人，實做部分使用粒子系統、UI、物理、AI......等功能...
</summary>
<ul>
<li>粒子系統: 敵人生成特效、雷射槍。</li>
<li>物理: 子彈擊飛敵人。</li>
<li>UI : 開始、結束、暫停按鈕。</li>
<li>AI : 敵人自動追擊玩家。</li>
</ul>
</details>

| 選單畫面 | 遊玩畫面 |
| ------------- | ------------- |
| ![教學影片](./images/GP04_02.png)  | ![選單畫面](./images/GP04_01.png) |

**IOS 2D橫向卷軸**

<details>
<summary>
    使用IOS Game框架中的 Sprite Kit遊戲開發的殺殭屍遊戲，通過發射子彈來避免殭屍前進，實做使用連續圖製作殭屍及人物動畫，背景街道則用兩組重複圖連續移動達到無限循環的效果。
</summary>
</details>

| 遊玩畫面 | 結算畫面 |
| ------------- | ------------- |
| ![教學影片](./images/IOS01.png)  | ![選單畫面](./images/IOS02.png) |

**留言平台(Cocos Creator, Nodejs, MySQL)**

<details>
<summary>
    一個以五人小組根據MVC架構做的留言平台，過程包含文件撰寫、開發程式、測試除錯到最後DEMO...
</summary>
功能 :
<ul>        
<li>使用者帳號密碼</li>
<li>新增、申請看板</li>
<li>發文、案讚、顯示熱門文章</li>
<li>新增、刪除好友、家族</li>
<li>管理員介面 :  刪除/凍結使用者、新增刪除看板</li>
</ul>
<br>實做工具:
<ul> 
<li>前端 :  Cocos Creator</li>
<li>後端 :  Nodejs express,socket.io</li>
<li>資料庫 : MySQL</li>
</ul>
</details>

| 登入頁面 | 管理者頁面 | 文章頁面 | 家族頁面 |
| ----------------- | -------------- | --------- | --------- |
| ![1](./images/T-page01.png)| ![2](./images/T-page02.png) |![3](./images/T-page03.png) | ![3](./images/T-page04.png) |