# Collection of code examples utilizing Soracom Cloud Camera Services API.

[Soracom Cloud Camera Services](https://soracom.jp/sora_cam/) (ソラコムクラウドカメラサービス。略称: [ソラカメ](https://sora-cam.com/)) は、ソラカメ対応カメラでクラウドに録画した映像を [SORACOM API](https://users.soracom.io/ja-jp/tools/api/) (以下、API) を使って操作できます。

Google が提供している [Colaboratory](https://colab.research.google.com/) (略称: Colab) を使って、実際に Python で API を使ったサンプルコードを実行できます。

サンプルコードは、Colab ノートブック (Jupyter Notebook) 形式で提供され、合わせて用意されている [ガイドページ](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/about-api-examples/) に記載された内容に沿って操作していくことで API の使いかたを体験できます。

## 体験について

[Soracom Cloud Camera Services スタートガイド](https://users.soracom.io/ja-jp/docs/soracom-cloud-camera-services/) に [API の使いかた](https://users.soracom.io/ja-jp/docs/soracom-cloud-camera-services/about-api-examples/) というガイドページがあります。このページで、サンプルコードの利用準備や実行条件の確認を行なってください。

体験できるサンプルコードごとにガイドページが用意されています。ガイドページに記載されている内容に沿って体験してください。

## コンテンツ

> [!IMPORTANT]
> サンプルコードの使用開始前に、ガイドページと注意点を必ず確認してください。

 - 15 分を超える動画をダウンロードする
 	-  [ガイドページ](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/api-examples-download-videos-longer-than-limits/)
	-  [サンプルコード](https://github.com/soracom-labs/sora-cam-api-examples/tree/main/download-videos-longer-than-limits/)
	- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soracom-labs/sora-cam-api-examples/blob/main/download-videos-longer-than-limits/api-examples-download-videos-longer-than-limits.ipynb)
- タイムラプス動画を作成する
 	-  [ガイドページ](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/api-examples-creating-time-lapse-video/)
	-  [サンプルコード](https://github.com/soracom-labs/sora-cam-api-examples/tree/main/creating-time-lapse-video/)
	- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soracom-labs/sora-cam-api-examples/blob/main/creating-time-lapse-video/api-examples-creating-time-lapse-video.ipynb)
- イベント画像に映っている物体を検出する
	-  [ガイドページ](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/api-examples-object-detection-with-event-image/)
	-  [サンプルコード](https://github.com/soracom-labs/sora-cam-api-examples/tree/main/object-detection-with-event-image/)
	- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soracom-labs/sora-cam-api-examples/blob/main/object-detection-with-event-image/api-examples-object-detection-with-event-image.ipynb)
- イベント画像にキャプションを付ける
	-  [ガイドページ](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/api-examples-add-caption-to-event-image/)
	-  [サンプルコード](https://github.com/soracom-labs/sora-cam-api-examples/tree/main/add-caption-to-event-image/)
	- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soracom-labs/sora-cam-api-examples/blob/main/add-caption-to-event-image/api-examples-add-caption-to-event-image.ipynb)
- イベント画像を OpenAI で解析する
	- [ガイドページ](https://users.soracom.io/ja-jp/docs/soracom-cloud-camera-services/api-examples-analyze-event-image-with-openai/)
	- [サンプルコード](https://github.com/soracom-labs/sora-cam-api-examples/tree/main/analyze-event-image-with-openai/)
	- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soracom-labs/sora-cam-api-examples/blob/main/analyze-event-image-with-openai/api-examples-analyze-event-image-with-openai.ipynb)
 
## 注意

- Colaboratory の利用には Google アカウントが必要です。
- ソラコムは、Colaboratory に関するサポートを行いません。
- Colaboratory については、運営会社へ直接 [お問い合わせ](https://research.google.com/colaboratory/faq.html) ください。
-  OpenAI API の利用には OpenAI アカウントで発行できる API キーが必要です。
-  OpenAI API の利用には別途料金がかかります。
-  ソラコムは OpenAI API に関するサポートを行いません。
-  OpenAI API については、運営会社へ直接 [お問い合わせ](https://help.openai.com/en/) ください。
- サンプルコードは、API の使いかたを紹介することを目的として提供されています。
- ソラコムは、サンプルコード に関するサポートを行いません。
- サンプルコードを実行したことによる利用者自身、もしくは第三者が被った損害に対して、直接的、間接的を問わず、株式会社ソラコムは責任を負いかねます。
- サンブルコード内で利用するライブラリを明示的にインストールしている場合があります。
- ライセンスは、インストールしたライブラリのライセンスに準ずる場合があります。
