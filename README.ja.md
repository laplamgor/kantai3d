

他の言語： [English](https://github.com/laplamgor/kantai3d/blob/main/README.md) [繁體中文](https://github.com/laplamgor/kantai3d/blob/main/README.zh-Hant.md)

> 関連リポジトリ：
> * 設定方法 A (パソコン): [Chrome拡張機能](https://github.com/laplamgor/kantai3d-chrome-extension)
> * 設定方法 B (パソコン): [KanColle Cache Proxy (KCCP)パッチャー](https://github.com/laplamgor/kantai3d-kccp-patcher)
> * 設定方法 C (Android): [GotoBrowser (2.6以上)](https://github.com/antest1/GotoBrowser) - Kantai3Dは設定ページで入手できます
> * 編集者向け： [深度マップ ギャラリー](https://github.com/laplamgor/kantai3d-depth-maps)
> * 編集者向け (オープンベータ)： [Webベースの深度マップエディタ](https://github.com/laplamgor/kantai3d-online-editor)


# Kantai3D
Kantai3D は艦隊これくしょんのサードパーティMODです。一部の秘書艦に3Dのような視覚効果とおける乳揺れを追加します。


### 3Dのような視覚効果:

![0463_7319_grmdtyheocuc](https://user-images.githubusercontent.com/11514317/96752931-b8a0c980-1401-11eb-8e42-1b02b336435d.gif) ![ezgif-3-10400017ed1e](https://user-images.githubusercontent.com/11514317/97005334-e0fb0600-1570-11eb-97b3-85896c1a463b.gif)

### おける乳揺れ:

![ezgif-7-39734d119569](https://user-images.githubusercontent.com/11514317/134775124-3ceb0bc6-a425-47c9-8219-5fb181767ade.gif)


Live2Dではありません。これは、視差遮蔽マッピング（POM）レンダリング手法であり、深度マップを使用して3D光線の閉塞をシミュレートします。


# 3D対応艦娘/CG

デプスマップの描画には非常に時間がかかり、3D対応艦娘の数は徐々に増加しています。

3D対応艦娘の名前は[ここ](https://github.com/users/laplamgor/projects/1#column-10244994)にあります。

現在、Kantai3Dは中破CGをサポートしていません。

# 設定方法

現在、Kantai3Dは限られたプラットフォームでのみ利用可能であり、インストールするためのいくつかのオプションがあります。

パソコンの Chrome ユーザーの場合、[Chrome拡張機能](https://github.com/laplamgor/kantai3d-chrome-extension)をご覧ください。パソコンの 補助ツール ユーザーの場合、[KanColle Cache Proxy (KCCP)パッチャー](https://github.com/laplamgor/kantai3d-kccp-patcher)を使用できます。

KCCPパッチャーには[KanColle キャッシュプロキシ](https://github.com/Tibowl/KCCacheProxy)が必要です。


Android ユーザーの場合、[GotoBrowser](https://github.com/antest1/GotoBrowser) を使用できます。 GotoBrowser は、Kantai3D が組み込まれたサードパーティの艦これ ブラウザアプリです。

# Contribute your own depth Map

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

この MOD だけでは、オリジンゲームからのデータは含まれていません。 使用されるすべての深度マップも描きです。

何か質問があれば、laplamgor@gmail.comで私に連絡してください。(日本語が苦手です、英語で返信する場合があります)
