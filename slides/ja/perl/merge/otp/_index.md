---
title: Perl経由で複数のOTPファイルをマージ
description: REST API とオープン ソース Perl SDK を使用して複数の Slides OTP ファイルをマージする
family: slides
platformtag: perl
feature: merge
informat: OTP
platform: Perl
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM ODP PDF HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="複数の OTP ファイルを Perl でマージする" h2="オープン ソースの Cloud Perl用SDK を使用して、Slides データの読み取り、編集、および他の形式へのエクスポート">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="OTP ファイルと Perl のマージ" %}}
1. <a href="https://dashboard.aspose.cloud/">ダッシュボード</a>でアカウントを作成して、無料の API 割り当てと承認の詳細を取得します
1. クライアント ID とクライアント シークレットで ```SlidesApi``` を初期化する
1. 入力 OTP ファイルの場所、マージされたファイルを保存する場所、およびファイルの一部をマージする必要があるかどうかに応じて、いずれかのマージ メソッドを呼び出します。
    - ```merge``` を使用して、ストレージ上のファイルに 1 つまたは複数のストレージ ファイルを追加します。
    - ```ordered_merge``` を使用して、1 つまたは複数のストレージ ファイルまたはその一部をストレージ上のファイルに追加します。 撮影するスライドのインデックスを指定できます。
    - ```merge_online``` は、複数のローカル ファイル、ストレージ ファイル、および/または URL で利用可能なファイルをマージします。 撮影するスライドのインデックスを指定できます。 結果はレスポンスボディにダウンロードされます。
    - ```merge_and_save_online``` は、複数のローカル ファイル、ストレージ ファイル、および/または URL で利用可能なファイルをマージします。 撮影するスライドのインデックスを指定できます。 結果はストレージに保存されます。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="スライド API と Perl SDK" %}}
[GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-perl) から Slides Cloud Perl用SDK ソース コードを取得して、SDK を自分でコンパイルするか、別のダウンロード オプションについては[リリース](https://releases.aspose.cloud/)にアクセスしてください。

Swagger ベースの [API リファレンス](https://apireference.aspose.cloud/slides/)も参照して、[SLIDES REST API](https://products.aspose.cloud/slides/curl/) の詳細を確認してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="merge" language="perl" inputFormat="otp" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}