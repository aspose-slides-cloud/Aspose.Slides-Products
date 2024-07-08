---
title: Slides PPS を Node.js 経由で複数の OTP に分割する
description: REST API とオープン ソース Node.js SDK を使用して Slides PPS ファイルを OTP スライドに分割する
family: slides
platformtag: nodejs
feature: split
informat: PPS
outformat: OTP
platform: Node.js
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM ODP PDF XPS JPEG PNG BMP TIFF SVG HTML5 MD GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Node.js で PPS を複数の OTP に分割する" h2="オープン ソースの Cloud Node.js用SDK を使用して、Slides データの読み取り、編集、および他の形式へのエクスポート">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="PPS ファイルと Node.js のマージ" %}}
1. <a href="https://dashboard.aspose.cloud/">ダッシュボード</a>でアカウントを作成して、無料の API 割り当てと承認の詳細を取得します
1. クライアント ID とクライアント シークレットで ```SlidesApi``` を初期化する
1. 入力 PPS ファイルの場所と結果の OTP ファイルを保存する場所に応じて、いずれかの分割メソッドを呼び出します。
    - ```split```、ストレージ上のファイルを分割し、結果をストレージに保存します。 入力 PPS の各スライドは、指定されたストレージ フォルダー (または既定では入力ファイル フォルダー) に個別の OTP として保存されます。
    - ```splitOnline``` を使用してローカル ファイルを分割し、結果を ZIP アーカイブとしてダウンロードします。 入力 PPS の各スライドは、ZIP アーカイブ内の個別の OTP としてダウンロードされます。
    - ```splitAndSaveOnline``` を使用して、ローカル ファイルを分割し、結果をストレージに保存します。 入力 PPS の各スライドは、指定されたストレージ フォルダー (または既定ではルート フォルダー) に個別の OTP として保存されます。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="スライド API と Node.js SDK" %}}
[GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-nodejs) から Slides Cloud Node.js用SDK ソース コードを取得して、SDK を自分でコンパイルするか、別のダウンロード オプションについては[リリース](https://releases.aspose.cloud/)にアクセスしてください。

Swagger ベースの [API リファレンス](https://apireference.aspose.cloud/slides/)も参照して、[SLIDES REST API](https://products.aspose.cloud/slides/curl/) の詳細を確認してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="nodejs" format="otp" inputFormat="pps" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}