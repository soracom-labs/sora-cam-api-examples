# イベント画像を OpenAI で解析する

ソラカメ対応カメラはイベントを検知して、イベント発生時の画像や動画を [クラウドに保存](https://users.soracom.io/ja-jp/docs/soracom-cloud-camera-services/check-event/) します。このイベント発生時の画像や動画を活用することで、イベントがあった時の状況や内容を把握できます。

たとえば、出入り口や搬入口にカメラを設置して、イベント発生時の画像や動画で、何が記録されているかを確認を取りたい場合があるとします。
その際、手作業で確認する場合は、検知したイベントの数に比例して多くの時間を使ってしまいます。AI を利用して、画像や映像の解析ができれば、何が記録されているかを解析結果の文字列から確認できます。

ここでは、[SORACOM API](https://users.soracom.io/ja-jp/tools/api/) (以下、API) を使ったサンプルコードを実行することで、イベント画像に対して [OpenAI API](https://platform.openai.com/docs/guides/vision) を使って画像解析を体験できます。OpenAI のサービスである [ChatGPT](https://chat.openai.com/) と同様に、イベント画像に対して自然言語で画像解析を行えます。サンプルコードは、[Colaboratory](https://colab.research.google.com/)(以下、Colab) を使って実行します。

## コンテンツ
-  [ガイドページ](https://users.soracom.io/ja-jp/docs/soracom-cloud-camera-services/api-examples-analyze-event-image-with-openai/)
-  [サンプルコード](https://github.com/soracom-labs/sora-cam-api-examples/tree/main/analyze-event-image-with-openai/)
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soracom-labs/sora-cam-api-examples/blob/main/analyze-event-image-with-openai/api-examples-analyze-event-image-with-openai.ipynb)

## [!CAUTION] 注意

- Colaboratory の利用には Google アカウントが必要です。
- ソラコムは、Colaboratory に関するサポートを行いません。
-  Colaboratory については、運営会社へ直接 [お問い合わせ](https://research.google.com/colaboratory/faq.html) ください。
-  OpenAI API の利用には OpenAI アカウントで発行できる API キーが必要です。
-  OpenAI API の利用には別途料金がかかります。
-  ソラコムは OpenAI API に関するサポートを行いません。
-  OpenAI API については、運営会社へ直接 [お問い合わせ](https://help.openai.com/en/) ください。
- サンプルコードは、API の使いかたを紹介することを目的として提供されています。SORACOM サポートではサポートを行いません。
- サンプルコードを実行したことによる利用者自身、もしくは第三者が被った損害に対して、直接的、間接的を問わず、株式会社ソラコムは責任を負いかねます。
- サンブルコード内でライブラリを明示的にインストールしている場合は、インストールしたライブラリのライセンスに準じますので、必ずライセンス確認をしてください。

