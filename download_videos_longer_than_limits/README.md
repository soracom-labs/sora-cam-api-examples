# API を使って制限5分以上の動画をダウンロードする

[Soracom Cloud Camera Services](https://soracom.jp/sora_cam/) (ソラコムクラウドカメラサービス。略称: ソラカメ) は、クラウドに常時録画した映像を API を使って操作できます。

Google が提供している [Colaboratory](https://colab.research.google.com/)(略称: Colab) を使って、実際に Python で API を実行するサンプルコードを実行できます。

サンプルコードは、Colab ノートブック (Jupyter Notebook) 形式で提供され、合わせて用意されている [ガイドページ](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/about-api-examples/) に記載された内容に沿って操作していくことでAPI の使いかたを体験できます。

## 体験について

[Soracom Cloud Camera Services スタートガイド](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/) に [API の使いかた](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/about-api-examples/) というガイドページがあります。

体験できる内容ごとにガイドページがあるので、ガイドページに記載されている内容に沿って体験してください。

## 体験できる内容

ユーザーコンソールで操作した場合、1 回の動画エクスポートは 5 分間の制限 があります。5 分を超える範囲をエクスポートするには、自分自身で 5 分間の単位に区切って、複数回エクスポートを行う必要があります。

ここでは、API を使うことで 5 分を超える範囲を指定された場合でも、自動的に 5 分間の単位に区切って動画をエクスポートとしてダウンロードできます。また、複数個ある 5 分間の動画ファイルを 1 つのファイルとしてダウンロードできます。以下のステップに沿って体験できます。

### API を使って制限5分以上の動画をダウンロードする
- [ガイドページ](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/api-examples-download-videos-longer-than-limits/)
- [サンプルコード](https://github.com/soracom-labs/sora-cam-api-examples/tree/main/download_videos_longer_than_limits/)
-  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soracom-labs/sora-cam-api-examples/blob/master/download_videos_longer_than_limits/api_examples_download_videos_longer_than_limits.ipynb)

## 注意

- Colaboratory の利用には Google アカウントが必要です。
- ご不明な点は Colaboratory の運営会社へ お問い合わせ ください。
- サンプルコード内で利用しているライブラリは、サンプルコード内に表示のライセンスに準じます。
- サンプルコードは、API の使いかたを紹介することを目的として作成されています。目的以外で利用する場合、利用者自身、もしくは第三者が被った損害に対して、直接的、間接的を問わず、株式会社ソラコムは責任を負いかねます。