---
title: Slides PPSM から Android 経由で ODP に変換
description: REST API とオープン ソース Android SDK を使用して Slides PPSM ファイルを作成、編集、ODP に変換します
family: slides
platformtag: android
feature: conversion
informat: PPSM
outformat: ODP
platform: Android
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM OTP PDF XPS JPEG PNG BMP TIFF SVG HTML SWF HTML5 GIF XAML MD MPEG4
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Android で PPSM を ODP に変換" h2="オープン ソースの Cloud Android用SDK を使用して、Slides データの読み取り、編集、および他の形式へのエクスポート">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Android を使用した PPSM から ODP への変換" %}}
1. <a href="https://dashboard.aspose.cloud/">ダッシュボード</a>でアカウントを作成して、無料の API 割り当てと承認の詳細を取得します
1. クライアント ID とクライアント シークレットで ```SlidesApi``` を初期化する
1. 入力 PPSM ファイルの場所と結果の ODP ファイルを保存する場所に応じて、convert メソッドのいずれかを呼び出します。
    - ```convert``` は、ローカル ファイルを変換し、結果をダウンロードします。
    - ```convertAndSave``` は、ローカル ファイルを変換し、結果をストレージに保存します。
    - ```downloadPresentation``` はストレージ上のファイルを変換し、結果をダウンロードします。
    - ```savePresentation``` はストレージ上のファイルを変換し、結果をストレージに保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="スライド API と Android SDK" %}}
[GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-android) から Slides Cloud Android用SDK ソース コードを取得して、SDK を自分でコンパイルするか、別のダウンロード オプションについては[リリース](https://releases.aspose.cloud/)にアクセスしてください。

Swagger ベースの [API リファレンス](https://apireference.aspose.cloud/slides/)も参照して、[SLIDES REST API](https://products.aspose.cloud/slides/curl/) の詳細を確認してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="convert" language="java" format="odp" inputFormat="ppsm" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}