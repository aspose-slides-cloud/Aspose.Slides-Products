---
title: Slides OTP'i Perl aracılığıyla birden fazla PPSX'ye ayırın
description: REST API ve Open Source Perl SDK ile Slides OTP dosyalarını PPSX slaytlarına ayırın
family: slides
platformtag: perl
feature: split
informat: OTP
outformat: PPSX
platform: Perl
otherformats: PPT PPTX PPS PPTM PPSM POTX POTM ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="OTP'i Perl ile PPSX Bölünmesine Dönüştürün" h2="Açık kaynaklı Cloud SDK for Perl ile Slides verilerini okuyun, düzenleyin ve diğer biçimlere aktarın">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Perl ile OTP'ten PPSX'e Dönüştürme" %}}
1. Ücretsiz API kotası ve yetkilendirme ayrıntılarını almak için <a href="https://dashboard.aspose.cloud/">Gösterge Tablosunda</a> bir hesap oluşturun
1. ```SlidesApi```'yi İstemci Kimliği ve İstemci Sırrı ile Başlatın
1. Girdi OTP dosyanızın nerede olduğuna ve ortaya çıkan PPSX dosyalarını nerede depolamak istediğinize bağlı olarak bölme yöntemlerinden birini çağırın
    - ```split```, depolamadaki bir dosyayı bölmek ve sonucu depolamaya kaydetmek için. Girilen OTP'in her slaytı, belirtilen depolama klasörüne (veya varsayılan olarak girdi dosyası klasörüne) ayrı bir PPSX olarak kaydedilir.
    - ```split_online```, yerel bir dosyayı bölmek ve sonucu bir ZIP arşivi olarak indirmek için. OTP girişinin her slaytı, ZIP arşivi içinde ayrı bir PPSX olarak indirilir.
    - ```split_and_save_online```, yerel bir dosyayı bölmek ve sonucu depolamaya kaydetmek için. OTP girişinin her slaytı, belirtilen depolama klasörüne (veya varsayılan olarak kök klasöre) ayrı bir PPSX olarak kaydedilir.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Slides API ve Perl SDK'yı Kullanmaya Başlayın" %}}
SDK'yı kendiniz derlemek için [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-perl)'dan Slides Cloud SDK for Perl kaynak kodunu edinin veya alternatif indirme seçenekleri için [Sürümlere](https://releases.aspose.cloud/) gidin.

[SLIDES REST API](https://products.aspose.cloud/slides/curl/) hakkında daha fazla bilgi edinmek için Swagger tabanlı [API Referansına](https://apireference.aspose.cloud/slides/) da bakın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="perl" format="ppsx" inputFormat="otp" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}