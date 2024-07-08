---
title: Slides POTM から cURL 経由で POTX に変換
description: REST API とオープン ソース cURL SDK を使用して Slides POTM ファイルを作成、編集、POTX に変換します
family: slides
platformtag: curl
feature: conversion
informat: POTM
outformat: POTX
platform: cURL
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTM ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML SWF HTML5 GIF XAML MD MPEG4
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="cURL で POTM を POTX に変換" h2="オープン ソースの Cloud cURL用SDK を使用して、Slides データの読み取り、編集、および他の形式へのエクスポート">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="cURL を使用した POTM から POTX への変換" %}}
1. <a href="https://dashboard.aspose.cloud/">ダッシュボード</a>でアカウントを作成して、無料の API 割り当てと承認の詳細を取得します
1. クライアント ID とクライアント シークレットで ```SlidesApi``` を初期化する
1. 入力 POTM ファイルの場所と結果の POTX ファイルを保存する場所に応じて、convert メソッドのいずれかを呼び出します。
    - ```Convert``` は、ローカル ファイルを変換し、結果をダウンロードします。
    - ```ConvertAndSave``` は、ローカル ファイルを変換し、結果をストレージに保存します。
    - ```DownloadPresentation``` はストレージ上のファイルを変換し、結果をダウンロードします。
    - ```SavePresentation``` はストレージ上のファイルを変換し、結果をストレージに保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="スライド API と cURL SDK" %}}
[GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-curl) から Slides Cloud cURL用SDK ソース コードを取得して、SDK を自分でコンパイルするか、別のダウンロード オプションについては[リリース](https://releases.aspose.cloud/)にアクセスしてください。

Swagger ベースの [API リファレンス](https://apireference.aspose.cloud/slides/)も参照して、[SLIDES REST API](https://products.aspose.cloud/slides/curl/) の詳細を確認してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="convert" language="curl" format="potx" inputFormat="potm" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}