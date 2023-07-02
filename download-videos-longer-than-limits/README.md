# 15 分を超える動画をダウンロードする

ユーザーコンソールを利用した場合も、API を利用した場合も、動画エクスポートには **1 回あたり最大 15 分間の制限** があります。そのため、15 分を超える動画をダウンロードするには、15 分ごとに動画をダウンロードしてから、それらを 1 つのファイルとして結合するなど工夫をする必要があります。

たとえば、毎回決まって行うルーティーン作業をソラカメ対応カメラで撮影していて、その作業が 15 分を超える場合、ユーザーコンソールで録画の確認を行うと、複数回の手動操作が必要です。SORACOM API を使うことで、手動操作よりも効果的に、作業の自動化や省力化が行えます。

ここでは、API を使ったサンプルコードを実行することで、指定された 15 分を超える範囲の動画をダウンロードして、1 つのファイルとして結合することを体験できます。サンプルコードは、[Colaboratory](https://colab.research.google.com/) (以下、Colab) を使って実行します。内容の詳細はガイドページを参照してください。

## コンテンツ
- [ガイドページ](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/api-examples-download-videos-longer-than-limits/)
- [サンプルコード](https://github.com/soracom-labs/sora-cam-api-examples/tree/main/download-videos-longer-than-limits/)
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soracom-labs/sora-cam-api-examples/blob/master/download-videos-longer-than-limits/api-examples-download-videos-longer-than-limits.ipynb)

## 注意

- Colaboratory の利用には Google アカウントが必要です。
- ソラコムは、Colaboratory に関するサポートを行いません。Colaboratory の利用方法については、Colaboratory の運営会社へ [お問い合わせ](https://research.google.com/colaboratory/faq.html) ください。
- サンプルコードは、API の使いかたを紹介することを目的として提供されています。SORACOM サポートではサポートを行いません。
- サンプルコードを実行したことによる利用者自身、もしくは第三者が被った損害に対して、直接的、間接的を問わず、株式会社ソラコムは責任を負いかねます。
- サンブルコード内でライブラリを明示的にインストールしている場合は、インストールしたライブラリのライセンスに準じますので、必ずライセンス確認をしてください。