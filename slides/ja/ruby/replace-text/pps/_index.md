---
title: Ruby 経由で PPS ファイル内のテキストを置換する
description: Slides PPS ファイル内のテキストを REST API とオープンソース Ruby SDK で置き換えます
family: slides
platformtag: ruby
feature: replace-text
informat: PPS
platform: Ruby
otherformats: PPT PPTX PPSX PPTM PPSM POTX POTM ODP OTP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="PPS ファイル内のテキストを Ruby で置き換える" h2="オープンソースの Cloud Ruby用SDK を使用して、Slides データ内のテキストの出現箇所を検索して置換します">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Ruby を使用した PPS ファイル内のテキストの置換" %}}
1. <a href="https://dashboard.aspose.cloud/">ダッシュボード</a>でアカウントを作成して、無料の API 割り当てと承認の詳細を取得します
1. クライアント ID とクライアント シークレットで ```SlidesApi``` を初期化する
1. PPS ファイルの場所、および文書全体または 1 つのスライド内のテキストを置換する必要があるかどうかに応じて、テキスト置換メソッドのいずれかを呼び出します。
    - ```replace_presentation_text``` は、ストレージ内のプレゼンテーション ファイルのすべてのスライド上で、指定されたテキストのすべての出現を別のテキストに置き換えます。
    - ```replace_slide_text``` は、ストレージ内のプレゼンテーション ファイルの 1 つのスライド上にある特定のテキストをすべて別のテキストに置き換えます。
    - ```replace_presentation_text_online``` は、リクエスト本文で渡されたプレゼンテーション ファイルのすべてのスライド内で、指定されたテキストをすべて別のテキストに置き換えます。
    - ```replace_slide_text_online``` は、リクエスト本文で渡されたプレゼンテーション ファイルの 1 つのスライド内で指定されたテキストをすべて別のテキストに置き換えます。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="スライド API と Ruby SDK" %}}
[GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-ruby) から Slides Cloud Ruby用SDK ソース コードを取得して、SDK を自分でコンパイルするか、別のダウンロード オプションについては[リリース](https://releases.aspose.cloud/)にアクセスしてください。

Swagger ベースの [API リファレンス](https://apireference.aspose.cloud/slides/)も参照して、[SLIDES REST API](https://products.aspose.cloud/slides/curl/) の詳細を確認してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="replaceText" language="ruby" inputFormat="pps" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}