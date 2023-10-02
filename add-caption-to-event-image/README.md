# イベント画像にキャプションを付ける

ソラカメ対応カメラはイベントを検知して、イベント発生時の画像や動画を [クラウドに保存](/ja-jp/guides/soracom-cloud-camera-services/check-event/) します。このイベント発生時の画像や動画を活用することで、イベントがあった時の状況や内容を把握できます。

たとえば、出入り口や搬入口にカメラを設置して、イベント発生時の画像や動画で、何が記録されているかを確認を取りたい場合があるとします。
その際、手作業で確認する場合は、検知したイベントの数に比例して多くの時間を使ってしまいます。AI を利用して、画像や映像の内容からキャプションが付けられれば、何が記録されているかをキャプションから確認できます。

ここでは、[SORACOM API](/ja-jp/tools/api/) (以下、API) を使ったサンプルコードを実行することで、イベント画像に対して学習済みモデルを使ったキャプション付けを体験できます。サンプルコードは、[Colaboratory](https://colab.research.google.com/)(以下、Colab) を使って実行します。

## コンテンツ
-  [ガイドページ](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/api-examples-add-caption-to-event-image/)
-  [サンプルコード](https://github.com/soracom-labs/sora-cam-api-examples/tree/main/add-caption-to-event-image/)
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soracom-labs/sora-cam-api-examples/blob/main/add-caption-to-event-image/api-examples-add-caption-to-event-image.ipynb)

## 注意

- Colaboratory の利用には Google アカウントが必要です。
- ソラコムは、Colaboratory に関するサポートを行いません。Colaboratory の利用方法については、Colaboratory の運営会社へ [お問い合わせ](https://research.google.com/colaboratory/faq.html) ください。
- サンプルコードは、API の使いかたを紹介することを目的として提供されています。SORACOM サポートではサポートを行いません。
- サンプルコードを実行したことによる利用者自身、もしくは第三者が被った損害に対して、直接的、間接的を問わず、株式会社ソラコムは責任を負いかねます。
- サンブルコード内でライブラリを明示的にインストールしている場合は、インストールしたライブラリのライセンスに準じますので、必ずライセンス確認をしてください。