# タイムラプス動画を作成する

カメラを設置した場所の状況や経過を確認する場合、クラウドに録画された映像を 再生 したり、画像を一覧表示 したりして確認すると思いますが、カメラの数や確認頻度が多いと大変な作業です。

たとえば、定点観察のような変化が少ない場合には、変化の差分に気づきにくいことがあったり、1 時間ごとに 1 回確認する場合にはすべての範囲を再生する必要がないこともあります。 このような場合に一定間隔で取得した静止画からタイムラプス動画を作成することで、通常では視覚的に捉えにくい変化や長時間の視聴をせずに短時間での確認ができます。

ここでは、[SORACOM API](https://users.soracom.io/ja-jp/tools/api/) (以下、API)  を使ったサンプルコードを実行することで、録画データから一定期間で取得した静止画を元に、タイムラプス動画の作成を体験できます。サンプルコードは、[Colaboratory](https://colab.research.google.com/) (以下、Colab) を使って実行します。内容の詳細はガイドページを参照してください。

## コンテンツ
 -  [ガイドページ](https://users.soracom.io/ja-jp/guides/soracom-cloud-camera-services/api-examples-creating-time-lapse-video/)
-  [サンプルコード](https://github.com/soracom-labs/sora-cam-api-examples/tree/main/creating-time-lapse-video/)
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soracom-labs/sora-cam-api-examples/blob/main/creating-time-lapse-video/api-examples-creating-time-lapse-video.ipynb)

## 注意

- Colaboratory の利用には Google アカウントが必要です。
- ソラコムは、Colaboratory に関するサポートを行いません。Colaboratory の利用方法については、Colaboratory の運営会社へ [お問い合わせ](https://research.google.com/colaboratory/faq.html) ください。
- サンプルコードは、API の使いかたを紹介することを目的として提供されています。SORACOM サポートではサポートを行いません。
- サンプルコードを実行したことによる利用者自身、もしくは第三者が被った損害に対して、直接的、間接的を問わず、株式会社ソラコムは責任を負いかねます。
- サンブルコード内でライブラリを明示的にインストールしている場合は、インストールしたライブラリのライセンスに準じますので、必ずライセンス確認をしてください。