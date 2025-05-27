其他語言：[English](https://github.com/laplamgor/kantai3d/blob/main/README.md) [日本語](https://github.com/laplamgor/kantai3d/blob/main/README.ja.md)

> 相關代碼庫：
> * 安裝方式一 (PC Chrome)：[Chrome 擴充功能](https://github.com/laplamgor/kantai3d-chrome-extension)
> * 安裝方式二 (PC [poi](https://github.com/poooi/poi))：[Poi 瀏覽器插件](https://github.com/laplamgor/kantai3d-poi-plugin)
> * ~~安裝方式三 (PC Proxy)：[KanColle Cache Proxy Patcher](https://github.com/laplamgor/kantai3d-kccp-patcher)~~（已棄用）
> * 安裝方式四 (Android)：[GotoBrowser (2.6 或更新版本)](https://github.com/antest1/GotoBrowser) - Kantai3D 於其設定頁面中提供
> * 貢獻者專用：[自定義深度圖庫](https://github.com/laplamgor/kantai3d-depth-maps)
> * 貢獻者專用 (公測中)：[網頁版深度圖編輯器](https://github.com/laplamgor/kantai3d-online-editor)
> * [深度圖生成器](https://github.com/laplamgor/kantai3d-depth-gen)（全新發布！）

# Kantai3D
Kantai3D 是艦隊收藏 (Kancolle - Kantai Collection) 的第三方模組 (MOD)。它為秘書艦添加了仿立體視覺效果及胸部物理動態效果。

### 1. 仿立體效果：
![ezgif-5-acf95d0da0e8](https://user-images.githubusercontent.com/11514317/144702625-fcf94f94-adc7-4741-b098-976cf757c556.gif)  
![ezgif-5-651e1f9db9ac](https://user-images.githubusercontent.com/11514317/144702627-36642582-4b92-4af7-8c58-613d7acca56e.gif)

本模組並非使用 Live2D 技術。它採用視差遮蔽映射 (Parallax Occlusion Mapping, POM) 渲染技術，結合深度圖模擬 3D 光線遮擋效果。這種技術常見於 3D 大作遊戲，用於增強牆壁與地面的凹凸視覺效果。

### 2. 胸部物理 (自 v2.0 起)：
![ezgif-7-39734d119569](https://user-images.githubusercontent.com/11514317/134775124-3ceb0bc6-a425-47c9-8219-5fb181767ade.gif)  
![ezgif-5-7d7de6bb4a51](https://user-images.githubusercontent.com/11514317/144702132-9954f9ad-f43a-41f3-8db9-6eceda3ca156.gif)

### 3. 遊戲內切換介面 (自 v3.0 起)：
![download](https://user-images.githubusercontent.com/11514317/166011636-9b9a93cc-5786-4983-91a1-963da70ce514.png)

# 支持的立繪

深度圖分為兩種類型：
1. [自定義手繪深度圖](https://github.com/users/laplamgor/projects/3/views/1)
   - 目前僅少數艦船擁有自定義深度圖。
   - 自定義深度圖品質更高，且可支持胸部物理效果。
2. [AI 生成深度圖 (Depth Pro)](https://github.com/laplamgor/kantai3d-depth-gen)
   - 涵蓋幾乎所有未有自定義深度圖的艦船立繪。
   - 立體效果品質略低於自定義深度圖。
   - 同樣支持胸部物理效果。

繪製自定義深度圖非常耗時，目前支持的立繪數量正在緩慢增加。請考慮為您喜愛的艦船貢獻深度圖！

# 安裝方法

目前 Kantai3D 僅支持部分平台，以下為各平台的安裝選項：

PC Chrome 用戶請使用 [Chrome 擴充功能](https://github.com/laplamgor/kantai3d-chrome-extension)。

PC [poi](https://github.com/poooi/poi) 用戶請在瀏覽器插件管理頁面安裝 [專用插件](https://github.com/laplamgor/kantai3d-poi-plugin)。

~~其他 PC 用戶可通過 [KanColle Cache Proxy Patcher](https://github.com/laplamgor/kantai3d-kccp-patcher) 安裝。~~  
~~此方式需配合 [KC Cache Proxy](https://github.com/Tibowl/KCCacheProxy) 使用。~~（已棄用）

Android 用戶可使用 [GotoBrowser](https://github.com/antest1/GotoBrowser)，這是一款內置 Kantai3D（作為試驗性功能）的第三方艦隊收藏瀏覽器應用。

# 貢獻自定義深度圖

最初，我希望這個項目能成為粉絲共同參與的計劃，期待玩家貢獻自製深度圖。

目前為止，多年來僅有少數貢獻，而新型 AI 模型已能生成更多可用的深度圖。

雖然人工貢獻已非必要，但您仍可使用我的工具為樂趣或非遊戲立繪製作深度圖。

我已開發 [網頁版深度圖編輯器](https://github.com/laplamgor/kantai3d-online-editor)，供您為喜愛的艦船立繪創建自定義深度圖。（因版權問題，原立繪素材請自行獲取）

您也可以通過電郵與我聯繫以獲取更多詳情。

## 提交方式：Pull Request 或電郵

若您希望您的深度圖與 Kantai3D 兼容，請在 [此代碼庫](https://github.com/laplamgor/kantai3d-depth-maps) 提交 Pull Request。

若不熟悉 GitHub，您也可以直接將作品電郵給我。

# 免責聲明
Kantai3D 並非 DMM 官方認可的程式，使用可能違反其服務條款。

Kantai3D 通過修改本地遊戲客戶端（main.js）實現視覺效果，但不會修改任何遊戲內 API 請求與響應，因此不會影響正常遊戲流程或平衡。

請自行承擔使用風險。

本模組不包含任何原遊戲數據。所有自定義深度圖均為 100% 手工繪製。AI 生成的深度圖因潛在版權問題未包含在此開源項目中。

如有任何問題或疑問，請聯繫：laplamgor@gmail.com
