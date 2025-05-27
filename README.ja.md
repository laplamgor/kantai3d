他の言語：[English](https://github.com/laplamgor/kantai3d/blob/main/README.md) [繁體中文](https://github.com/laplamgor/kantai3d/blob/main/README.zh-Hant.md)

> 関連リポジトリ：
> * インストール方法 A (PC Chrome)：[Chrome 拡張機能](https://github.com/laplamgor/kantai3d-chrome-extension)
> * インストール方法 B (PC [poi](https://github.com/poooi/poi))：[Poi プラグイン](https://github.com/laplamgor/kantai3d-poi-plugin)
> * ~~インストール方法 C (PC Proxy)：[KanColle Cache Proxy Patcher](https://github.com/laplamgor/kantai3d-kccp-patcher)~~（廃止）
> * インストール方法 D (Android)：[GotoBrowser (2.6 以上)](https://github.com/antest1/GotoBrowser) - Kantai3D は設定ページで利用可能
> * 貢献者向け：[カスタム深度マップライブラリ](https://github.com/laplamgor/kantai3d-depth-maps)
> * 貢献者向け (ベータ版)：[Web ベース深度マップエディタ](https://github.com/laplamgor/kantai3d-online-editor)
> * [深度マップ生成器](https://github.com/laplamgor/kantai3d-depth-gen)（新登場！）

# Kantai3D
Kantai3D は、艦隊これくしょん（Kancolle - Kantai Collection）のサードパーティ製 MOD です。秘書艦に 3D のような視覚効果とおける乳揺れ物理効果を追加します。

### 1. 3D のような視覚効果：
![ezgif-5-acf95d0da0e8](https://user-images.githubusercontent.com/11514317/144702625-fcf94f94-adc7-4741-b098-976cf757c556.gif)  
![ezgif-5-651e1f9db9ac](https://user-images.githubusercontent.com/11514317/144702627-36642582-4b92-4af7-8c58-613d7acca56e.gif)

これは Live2D ではありません。視差遮蔽マッピング（Parallax Occlusion Mapping, POM）レンダリング手法を使用し、深度マップを活用して 3D 光線の遮蔽をシミュレートします。3D AAA ゲームでは、壁や床にこの技術を用いて凹凸の視覚効果を追加することが一般的です。

### 2. おける乳揺れ (v2.0 以降)：
![ezgif-7-39734d119569](https://user-images.githubusercontent.com/11514317/134775124-3ceb0bc6-a425-47c9-8219-5fb181767ade.gif)  
![ezgif-5-7d7de6bb4a51](https://user-images.githubusercontent.com/11514317/144702132-9954f9ad-f43a-41f3-8db9-6eceda3ca156.gif)

### 3. ゲーム内 UI トグル (v3.0 以降)：
![download](https://user-images.githubusercontent.com/11514317/166011636-9b9a93cc-5786-4983-91a1-963da70ce514.png)

# 対応 CG

深度マップは以下の 2 種類に分けられます：
1. [カスタム手描き深度マップ](https://github.com/users/laplamgor/projects/3/views/1)
   - 現在、一部の艦船のみがカスタム深度マップに対応。
   - カスタム深度マップは高品質で、おける乳揺れ効果をサポートします。
2. [AI 生成深度マップ (Depth Pro)](https://github.com/laplamgor/kantai3d-depth-gen)
   - カスタム深度マップがないほぼすべての艦船 CG をカバー。
   - 3D 効果の品質はカスタム深度マップに比べてやや劣ります。
   - おける乳揺れ効果もサポート。

カスタム深度マップの作成は非常に時間がかかるため、対応 CG の数は徐々に増加しています。お気に入りの艦船のために深度マップを貢献することを検討してください。

# インストール方法

現在、Kantai3D は限られたプラットフォームでのみ利用可能で、以下のインストール方法があります：

PC Chrome ユーザーは [Chrome 拡張機能](https://github.com/laplamgor/kantai3d-chrome-extension) をご確認ください。

PC [poi](https://github.com/poooi/poi) ユーザーは、ブラウザのプラグインマネージャーで [プラグイン](https://github.com/laplamgor/kantai3d-poi-plugin) をインストールしてください。

~~他の PC ユーザーは [KanColle Cache Proxy Patcher](https://github.com/laplamgor/kantai3d-kccp-patcher) を使用してインストールできます。~~  
~~KCCP パッチャーは [KC Cache Proxy](https://github.com/Tibowl/KCCacheProxy) が必要です。~~（廃止）

Android ユーザーは [GotoBrowser](https://github.com/antest1/GotoBrowser) を使用できます。これは Kantai3D を実験的機能として内蔵したサードパーティ製艦これブラウザアプリです。

# カスタム深度マップの貢献

当初、このプロジェクトはファンによる共同作業を目標としており、ユーザーが深度マップを貢献してくれることを期待していました。

これまで数年間で寄せられた貢献はわずかでしたが、最新の AI モデルにより、より多くの使用可能な深度マップが生成されるようになりました。

人的な貢献は必須ではなくなりましたが、楽しみやゲーム以外の CG のために私のツールを使用することもできます。

カスタム深度マップを作成するための [Web ベース深度マップエディタ](https://github.com/laplamgor/kantai3d-online-editor) を用意しました。

お気に入りの艦船 CG の深度マップを作成できます。（著作権の関係上、元の CG 画像は提供しません。）

詳細については、メールでご連絡ください。

## Pull Request またはメールでの提出

Kantai3D で動作する深度マップを貢献したい場合は、[このリポジトリ](https://github.com/laplamgor/kantai3d-depth-maps) で Pull Request をしてください。

GitHub に慣れていない場合は、作品をメールで直接送っていただいても構いません。

# 免責事項
Kantai3D は公式に承認されたプログラムではありません。DMM の利用規約に違反する可能性があります。

Kantai3D はローカルのゲームクライアント（main.js）を変更して視覚効果を実現しますが、ゲーム内 API のリクエストやレスポンスを変更せず、通常のゲームプレイやバランスに影響を与えません。

ご自身の責任でご利用ください。

この MOD 単体では、元のゲームデータは一切含まれていません。使用されるすべてのカスタム深度マップは 100% 手描きです。ただし、AI 生成の深度マップは著作権の問題により、このオープンソースプロジェクトの範囲には含まれていません。

ご質問やご不明点がある場合は、laplamgor@gmail.com までご連絡ください。（日本語が苦手なため、英語で返信する場合があります）

