其他語言：[English](https://github.com/laplamgor/kantai3d/blob/main/README.md) [日本語](https://github.com/laplamgor/kantai3d/blob/main/README.ja.md)


> 相關代碼庫:
> * 安裝方式一: [Chrome 擴充功能](https://github.com/laplamgor/kantai3d-chrome-extension)
> * 安裝方式二: [poi 插件](https://github.com/laplamgor/kantai3d-poi-plugin)
> * 安裝方式三: [KanColle Cache Proxy Patcher](https://github.com/laplamgor/kantai3d-kccp-patcher)
> * 安裝方式四(安卓): [GotoBrowser](https://github.com/antest1/GotoBrowser)
> * 貢獻深度圖適用: [深度圖庫](https://github.com/laplamgor/kantai3d-depth-maps)
> * 貢獻自定義深度圖適用 (已棄用): ~~[Photoshop 深度圖預覽插件](https://github.com/laplamgor/kantai3d-photoshop-extension)~~
> * 貢獻深度圖適用 (公測中): [網頁版編輯器](https://github.com/laplamgor/kantai3d-online-editor)



# Kantai3D
Kantai3D (前稱：艦隊立體化改修) 是艦隊收藏的第三方製作的遊戲MOD。唯一功能是為部份秘書艦添加仿立體的視覺效果及胸部物理。


### 1. 仿立體效果：

![ezgif-5-acf95d0da0e8](https://user-images.githubusercontent.com/11514317/144702625-fcf94f94-adc7-4741-b098-976cf757c556.gif)
![ezgif-5-651e1f9db9ac](https://user-images.githubusercontent.com/11514317/144702627-36642582-4b92-4af7-8c58-613d7acca56e.gif)

本 MOD 並無使用 Live2D 技術亦與 PSV 遊戲無關。 本 MOD 的立體效果是使用視差遮蔽映射 (POM) 算法加上自製的深度圖渲染而成。順帶一提，3D大作遊戲經常在牆壁、地面上使用視差遮蔽映射特效增強凹凸感。

### 2. 胸部物理  (v2.0+, 定制深度圖限定)：

![ezgif-7-39734d119569](https://user-images.githubusercontent.com/11514317/134775124-3ceb0bc6-a425-47c9-8219-5fb181767ade.gif)
![ezgif-5-7d7de6bb4a51](https://user-images.githubusercontent.com/11514317/144702132-9954f9ad-f43a-41f3-8db9-6eceda3ca156.gif)

### 3. 遊戲內置設定 (v3.0+):

![download](https://user-images.githubusercontent.com/11514317/166011636-9b9a93cc-5786-4983-91a1-963da70ce514.png)


# 支持立體效果的立繪

深度圖分為兩種： 
1. [自定義手繪深度圖](https://github.com/users/laplamgor/projects/3/views/1)
   - 目前只有小部份立繪有自定義手繪深度圖。
   - 自定義深度圖的立體效果品質更高，而且可支持胸部物理。
2. [深度學習產生的深度圖](https://github.com/isl-org/MiDaS)
   - 幾乎可以覆蓋所有未有自定義手繪深度圖的立繪。 
   - 立體效果品質普遍較粗糙。
   - 不支持胸部物理。

繪製自定義深度圖需時，自定義深度圖庫正慢速增長中。

# 安裝方法

目前Kantai3D只支持一部份客戶端使用，您有以下安裝方法可選：

PC Chrome 用戶請使用 [Chrome 擴充功能](https://github.com/laplamgor/kantai3d-chrome-extension)。

PC poi 用戶請於"擴展程式"頁安裝 [專用插件](https://github.com/laplamgor/kantai3d-poi-plugin)。

PC 其他瀏覽器用戶可利用 [KanColle Cache Proxy Patcher](https://github.com/laplamgor/kantai3d-kccp-patcher)。
需配合 [KC Cache Proxy](https://github.com/Tibowl/KCCacheProxy) 一併使用。

安卓用戶可使用第三方瀏覽器[GotoBrowser](https://github.com/antest1/GotoBrowser)。已內置Kantai3D作為試驗性功能。

# 貢獻自定義手繪深度圖

製作深度圖需時，只有一個人做怎麼可能補回全部船。

長遠打算必須開放生態，引進能自願參與製作深度圖的玩家們。

因為PS門檻太高，深度圖原理又不好懂，我連[深度在線圖編輯器](https://github.com/laplamgor/kantai3d-online-editor)都整出來了。

(另外由於版權問題，原立繪素材請自行獲取)

## 經Pull Request 或者電郵提交

如果您想貢獻您的自製深度圖，可以自行去[這個專業](https://github.com/laplamgor/kantai3d-depth-maps)提交PR.

或者直接發成品給到我的電郵地址



# 免責聲明
Kantai3D並非官方正式同意使用的程式。使用Kantai3D可能違反DMM遊戲服務使用條款。

Kantai3D需要修改本地的遊戲客戶端以達成顯示效果，但不會修改任何遊戲內API收發，不會干預原本的遊戲流程或遊戲平衡。

請自行承擔使用風險。

本MOD不含任何原遊戲資源或官方代碼。所使用的自定義深度圖都是完全手工制作。

如有疑問請聯絡 laplamgor@gmail.com
