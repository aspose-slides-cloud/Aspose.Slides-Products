---
title: Slides PPSX を Ruby 経由で複数の PPTX に分割する
description: REST API とオープン ソース Ruby SDK を使用して Slides PPSX ファイルを PPTX スライドに分割する
family: slides
platformtag: ruby
feature: split
informat: PPSX
outformat: PPTX
platform: Ruby
otherformats: PPT PPS PPSX PPTM PPSM POTX POTM ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 MD GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Ruby で PPSX を複数の PPTX に分割する" h2="オープン ソースの Cloud Ruby用SDK を使用して、Slides データの読み取り、編集、および他の形式へのエクスポート">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="PPSX ファイルと Ruby のマージ" %}}
1. <a href="https://dashboard.aspose.cloud/">ダッシュボード</a>でアカウントを作成して、無料の API 割り当てと承認の詳細を取得します
1. クライアント ID とクライアント シークレットで ```SlidesApi``` を初期化する
1. 入力 PPSX ファイルの場所と結果の PPTX ファイルを保存する場所に応じて、いずれかの分割メソッドを呼び出します。
    - ```split```、ストレージ上のファイルを分割し、結果をストレージに保存します。 入力 PPSX の各スライドは、指定されたストレージ フォルダー (または既定では入力ファイル フォルダー) に個別の PPTX として保存されます。
    - ```split_online``` を使用してローカル ファイルを分割し、結果を ZIP アーカイブとしてダウンロードします。 入力 PPSX の各スライドは、ZIP アーカイブ内の個別の PPTX としてダウンロードされます。
    - ```split_and_save_online``` を使用して、ローカル ファイルを分割し、結果をストレージに保存します。 入力 PPSX の各スライドは、指定されたストレージ フォルダー (または既定ではルート フォルダー) に個別の PPTX として保存されます。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="スライド API と Ruby SDK" %}}
[GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-ruby) から Slides Cloud Ruby用SDK ソース コードを取得して、SDK を自分でコンパイルするか、別のダウンロード オプションについては[リリース](https://releases.aspose.cloud/)にアクセスしてください。

Swagger ベースの [API リファレンス](https://apireference.aspose.cloud/slides/)も参照して、[SLIDES REST API](https://products.aspose.cloud/slides/curl/) の詳細を確認してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="ruby" format="pptx" inputFormat="ppsx" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}