

他の言語： [English](https://github.com/laplamgor/kantai3d/blob/main/README.md) [繁體中文](https://github.com/laplamgor/kantai3d/blob/main/README.zh-Hant.md)

> 関連リポジトリ：
> * 設定方法 A (パソコン Chrome): [Chrome 拡張機能](https://github.com/laplamgor/kantai3d-chrome-extension)
> * 設定方法 B (パソコン [poi](https://github.com/poooi/poi)): [poi プラグイン](https://github.com/laplamgor/kantai3d-poi-plugin)
> * 設定方法 C (パソコン): [KanColle Cache Proxy (KCCP)パッチャー](https://github.com/laplamgor/kantai3d-kccp-patcher)
> * 設定方法 D (Android): [GotoBrowser (2.6以上)](https://github.com/antest1/GotoBrowser) - Kantai3Dは設定ページで入手できます
> * 編集者向け： [カスタマイズ深度マップ ギャラリー](https://github.com/laplamgor/kantai3d-depth-maps)
> * 編集者向け (オープンベータ)： [Webベースの深度マップエディタ](https://github.com/laplamgor/kantai3d-online-editor)


# Kantai3D
Kantai3D は艦隊これくしょんのサードパーティMODです。一部の秘書艦に3Dのような視覚効果とおける乳揺れを追加します。


### 1. 3Dのような視覚効果:
![ezgif-5-acf95d0da0e8](https://user-images.githubusercontent.com/11514317/144702625-fcf94f94-adc7-4741-b098-976cf757c556.gif)
![ezgif-5-651e1f9db9ac](https://user-images.githubusercontent.com/11514317/144702627-36642582-4b92-4af7-8c58-613d7acca56e.gif)

Live2Dではありません。これは、視差遮蔽マッピング（POM）レンダリング手法であり、深度マップを使用して3D光線の閉塞をシミュレートします。

### 2. おける乳揺れ (v2.0+):

![ezgif-7-39734d119569](https://user-images.githubusercontent.com/11514317/134775124-3ceb0bc6-a425-47c9-8219-5fb181767ade.gif)
![ezgif-5-7d7de6bb4a51](https://user-images.githubusercontent.com/11514317/144702132-9954f9ad-f43a-41f3-8db9-6eceda3ca156.gif)

### 3. ゲーム内設定 (v3.0+):

![download](https://user-images.githubusercontent.com/11514317/166011636-9b9a93cc-5786-4983-91a1-963da70ce514.png)




# 3D対応艦娘/CG

深度マップは、次の2つに分類されます：
1. [カスタム手描き深度マップ](https://github.com/users/laplamgor/projects/3/views/1)
   - 現在、カスタム手描き深度マップはCGの一部しかありません。
   - カスタム深度マップの立体効果は、より品質が高く、乳揺れをサポートします。
2. [AIによって生成された深度マップ](https://github.com/isl-org/MiDaS)
   - カスタム手描きの深さマップがないCGはほとんどサポートできます。
   - 立体効果の品質は一般的に粗い。
   - 乳揺れはサポートされていません。

カスタム深度マップの描画には非常に時間がかかり、3D対応艦娘の数は徐々に増加しています。


# 設定方法

現在、Kantai3Dは限られたプラットフォームでのみ利用可能であり、インストールするためのいくつかのオプションがあります。

パソコンの Chrome ユーザーの場合、[Chrome拡張機能](https://github.com/laplamgor/kantai3d-chrome-extension)をご覧ください。

パソコンの [poi](https://github.com/poooi/poi) ユーザーの場合、[プラグイン](https://github.com/laplamgor/kantai3d-chrome-extension)をご覧ください。

パソコンの 他の補助ツール ユーザーの場合、[KanColle Cache Proxy (KCCP)パッチャー](https://github.com/laplamgor/kantai3d-kccp-patcher)を使用できます。

KCCPパッチャーには[KanColle キャッシュプロキシ](https://github.com/Tibowl/KCCacheProxy)が必要です。


Android ユーザーの場合、[GotoBrowser](https://github.com/antest1/GotoBrowser) を使用できます。 GotoBrowser は、Kantai3D が組み込まれたサードパーティの艦これ ブラウザアプリです。

# Contribute your own custom depth Map

In long term, I would like this project to be fan-based. It definitely needs more than one busy poor man to draw all depth maps for 200+ ships and 500+ CGs.

I have created an [online editor](https://github.com/laplamgor/kantai3d-online-editor) to draw depth map.

You can create depth map for your favorite ship CG. (CG base image will not not provided by me due to copyright.)

## Pull Request or Email

If you want your depth map to work with Kantai3D, just do a pull request [on this repo](https://github.com/laplamgor/kantai3d-depth-maps).

Or if you are not familiar with Github, you can also just email me your work!


# 免責事項
Kantai3Dは、ゲーム内APIのリクエストとレスポンスを変更したり、一般ゲームプレイに影響を与えたりすることはありません。
ただし、Kantai3Dは正式に承認されたプログラムではありません。

ご自身の責任でご利用ください。

この MOD だけでは、オリジンゲームからのデータは含まれていません。 使用されるすべてのカスタム深度マップも描きです。

何か質問があれば、laplamgor@gmail.comで私に連絡してください。(日本語が苦手です、英語で返信する場合があります)
