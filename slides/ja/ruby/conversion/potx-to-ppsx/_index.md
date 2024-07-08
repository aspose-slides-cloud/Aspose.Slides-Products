---
title: Slides POTX から Ruby 経由で PPSX に変換
description: REST API とオープン ソース Ruby SDK を使用して Slides POTX ファイルを作成、編集、PPSX に変換します
family: slides
platformtag: ruby
feature: conversion
informat: POTX
outformat: PPSX
platform: Ruby
otherformats: PPT PPTX PPS PPTM PPSM POTX POTM ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML SWF HTML5 GIF XAML MD MPEG4
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Ruby で POTX を PPSX に変換" h2="オープン ソースの Cloud Ruby用SDK を使用して、Slides データの読み取り、編集、および他の形式へのエクスポート">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Ruby を使用した POTX から PPSX への変換" %}}
1. <a href="https://dashboard.aspose.cloud/">ダッシュボード</a>でアカウントを作成して、無料の API 割り当てと承認の詳細を取得します
1. クライアント ID とクライアント シークレットで ```SlidesApi``` を初期化する
1. 入力 POTX ファイルの場所と結果の PPSX ファイルを保存する場所に応じて、convert メソッドのいずれかを呼び出します。
    - ```convert``` は、ローカル ファイルを変換し、結果をダウンロードします。
    - ```convert_and_save``` は、ローカル ファイルを変換し、結果をストレージに保存します。
    - ```download_presentation``` はストレージ上のファイルを変換し、結果をダウンロードします。
    - ```save_presentation``` はストレージ上のファイルを変換し、結果をストレージに保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="スライド API と Ruby SDK" %}}
[GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-ruby) から Slides Cloud Ruby用SDK ソース コードを取得して、SDK を自分でコンパイルするか、別のダウンロード オプションについては[リリース](https://releases.aspose.cloud/)にアクセスしてください。

Swagger ベースの [API リファレンス](https://apireference.aspose.cloud/slides/)も参照して、[SLIDES REST API](https://products.aspose.cloud/slides/curl/) の詳細を確認してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="convert" language="ruby" format="ppsx" inputFormat="potx" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}