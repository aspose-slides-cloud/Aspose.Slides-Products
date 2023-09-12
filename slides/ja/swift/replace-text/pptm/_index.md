---
title: Swift 経由で PPTM ファイル内のテキストを置換する
description: Slides PPTM ファイル内のテキストを REST API とオープンソース Swift SDK で置き換えます
family: slides
platformtag: swift
feature: replace-text
informat: PPTM
platform: Swift
otherformats: PPT PPTX PPS PPSX PPSM POTX POTM ODP OTP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="PPTM ファイル内のテキストを Swift で置き換える" h2="オープンソースの Cloud Swift用SDK を使用して、Slides データ内のテキストの出現箇所を検索して置換します">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Swift を使用した PPTM ファイル内のテキストの置換" %}}
1. <a href="https://dashboard.aspose.cloud/">ダッシュボード</a>でアカウントを作成して、無料の API 割り当てと承認の詳細を取得します
1. クライアント ID とクライアント シークレットで ```SlidesApi``` を初期化する
1. PPTM ファイルの場所、および文書全体または 1 つのスライド内のテキストを置換する必要があるかどうかに応じて、テキスト置換メソッドのいずれかを呼び出します。
    - ```replacePresentationText``` は、ストレージ内のプレゼンテーション ファイルのすべてのスライド上で、指定されたテキストのすべての出現を別のテキストに置き換えます。
    - ```replaceSlideText``` は、ストレージ内のプレゼンテーション ファイルの 1 つのスライド上にある特定のテキストをすべて別のテキストに置き換えます。
    - ```replacePresentationTextOnline``` は、リクエスト本文で渡されたプレゼンテーション ファイルのすべてのスライド内で、指定されたテキストをすべて別のテキストに置き換えます。
    - ```replaceSlideTextOnline``` は、リクエスト本文で渡されたプレゼンテーション ファイルの 1 つのスライド内で指定されたテキストをすべて別のテキストに置き換えます。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="スライド API と Swift SDK" %}}
[GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-swift) から Slides Cloud Swift用SDK ソース コードを取得して、SDK を自分でコンパイルするか、別のダウンロード オプションについては[リリース](https://releases.aspose.cloud/)にアクセスしてください。

Swagger ベースの [API リファレンス](https://apireference.aspose.cloud/slides/)も参照して、[SLIDES REST API](https://products.aspose.cloud/slides/curl/) の詳細を確認してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="replaceText" language="swift" inputFormat="pptm" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}