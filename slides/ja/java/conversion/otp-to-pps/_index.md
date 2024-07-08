---
title: Slides OTP から Java 経由で PPS に変換
description: REST API とオープン ソース Java SDK を使用して Slides OTP ファイルを作成、編集、PPS に変換します
family: slides
platformtag: java
feature: conversion
informat: OTP
outformat: PPS
platform: Java
otherformats: PPT PPTX PPSX PPTM PPSM POTX POTM ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML SWF HTML5 GIF XAML XML MD MPEG4
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Java で OTP を PPS に変換" h2="オープン ソースの Cloud Java用SDK を使用して、Slides データの読み取り、編集、および他の形式へのエクスポート">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Java を使用した OTP から PPS への変換" %}}
1. <a href="https://dashboard.aspose.cloud/">ダッシュボード</a>でアカウントを作成して、無料の API 割り当てと承認の詳細を取得します
1. クライアント ID とクライアント シークレットで ```SlidesApi``` を初期化する
1. 入力 OTP ファイルの場所と結果の PPS ファイルを保存する場所に応じて、convert メソッドのいずれかを呼び出します。
    - ```convert``` は、ローカル ファイルを変換し、結果をダウンロードします。
    - ```convertAndSave``` は、ローカル ファイルを変換し、結果をストレージに保存します。
    - ```downloadPresentation``` はストレージ上のファイルを変換し、結果をダウンロードします。
    - ```savePresentation``` はストレージ上のファイルを変換し、結果をストレージに保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="スライド API と Java SDK" %}}
[GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-java) から Slides Cloud Java用SDK ソース コードを取得して、SDK を自分でコンパイルするか、別のダウンロード オプションについては[リリース](https://releases.aspose.cloud/)にアクセスしてください。

Swagger ベースの [API リファレンス](https://apireference.aspose.cloud/slides/)も参照して、[SLIDES REST API](https://products.aspose.cloud/slides/curl/) の詳細を確認してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="convert" language="java" format="pps" inputFormat="otp" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}