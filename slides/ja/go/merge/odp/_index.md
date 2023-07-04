---
title: Go経由で複数のODPファイルをマージ
description: REST API とオープン ソース Go SDK を使用して複数の Slides ODP ファイルをマージする
family: slides
platformtag: go
feature: merge
informat: ODP
platform: Go
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM OTP PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="複数の ODP ファイルを Go でマージする" h2="オープン ソースの Cloud Go用SDK を使用して、Slides データの読み取り、編集、および他の形式へのエクスポート">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Go を使用した ODP から MPEG4 への変換" %}}
1. <a href="https://dashboard.aspose.cloud/">ダッシュボード</a>でアカウントを作成して、無料の API 割り当てと承認の詳細を取得します
1. クライアント ID とクライアント シークレットで ```SlidesApi``` を初期化する
1. 入力 ODP ファイルの場所、マージされたファイルを保存する場所、およびファイルの一部をマージする必要があるかどうかに応じて、いずれかのマージ メソッドを呼び出します。
    - ```Merge``` を使用して、ストレージ上のファイルに 1 つまたは複数のストレージ ファイルを追加します。
    - ```OrderedMerge``` を使用して、1 つまたは複数のストレージ ファイルまたはその一部をストレージ上のファイルに追加します。 撮影するスライドのインデックスを指定できます。
    - ```MergeOnline``` は、複数のローカル ファイル、ストレージ ファイル、および/または URL で利用可能なファイルをマージします。 撮影するスライドのインデックスを指定できます。 結果はレスポンスボディにダウンロードされます。
    - ```MergeAndSaveOnline``` は、複数のローカル ファイル、ストレージ ファイル、および/または URL で利用可能なファイルをマージします。 撮影するスライドのインデックスを指定できます。 結果はストレージに保存されます。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="スライド API と Go SDK" %}}
[GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-go) から Slides Cloud Go用SDK ソース コードを取得して、SDK を自分でコンパイルするか、別のダウンロード オプションについては[リリース](https://releases.aspose.cloud/)にアクセスしてください。

Swagger ベースの [API リファレンス](https://apireference.aspose.cloud/slides/)も参照して、[SLIDES REST API](https://products.aspose.cloud/slides/curl/) の詳細を確認してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="merge" language="go" inputFormat="odp" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}