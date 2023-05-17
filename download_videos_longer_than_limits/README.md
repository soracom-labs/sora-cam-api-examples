# API を使って制限5分以上の動画をダウンロードする

ユーザーコンソールを利用した場合も、SORACOM API を利用した場合も、動画エクスポートには **1 回あたり最大 5 分間の制限** があります。そのため、5 分を超える動画をダウンロードするには、5 分ごとに動画をダウンロードしてから、それらを 1 つのファイルとして結合します。

たとえば、毎回決まって行うルーティーン作業をソラカメ対応カメラで撮影していて、その作業が 5 分以上になる場合、録画を後から確認する際、ユーザーコンソールだと複数回の手動操作が必要です。ここで説明する SORACOM API を使うことで、効果的に作業の自動化や省力化が行えます。

ここでは、API を使ったサンプルコードを実行することで、上記の動作を体験できます。サンプルコードは、[Colaboratory](https://colab.research.google.com/)(以下、Colab) を使って実行します。詳細はガイドページを参照してください。


## API を使って制限5分以上の動画をダウンロードする
- [ガイドページ](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/api-examples-download-videos-longer-than-limits/)
- [サンプルコード](https://github.com/soracom-labs/sora-cam-api-examples/tree/main/download_videos_longer_than_limits/)
-  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soracom-labs/sora-cam-api-examples/blob/master/download_videos_longer_than_limits/api_examples_download_videos_longer_than_limits.ipynb)

## 注意

- Colaboratory の利用には Google アカウントが必要です。
- ソラコムは、Colaboratory に関するサポートを行いません。Colaboratory の利用方法については、Colaboratory の運営会社へ [お問い合わせ](https://research.google.com/colaboratory/faq.html) ください。
- サンプルコード内で利用しているライブラリは、サンプルコード内に表示のライセンスに準じます。
- サンプルコードは、API の使いかたを紹介することを目的として提供されています。SORACOM サポートではサポートを行いません。また、サンプルコードを実行したことによる利用者自身、もしくは第三者が被った損害に対して、直接的、間接的を問わず、株式会社ソラコムは責任を負いかねます。