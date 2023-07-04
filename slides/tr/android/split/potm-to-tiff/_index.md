---
title: Slides POTM'i Android aracılığıyla birden fazla TIFF'ye ayırın
description: REST API ve Open Source Android SDK ile Slides POTM dosyalarını TIFF slaytlarına ayırın
family: slides
platformtag: android
feature: split
informat: POTM
outformat: TIFF
platform: Android
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM ODP OTP PDF XPS JPEG PNG BMP SVG HTML5 GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="POTM'i Android ile TIFF Bölünmesine Dönüştürün" h2="Açık kaynaklı Cloud SDK for Android ile Slides verilerini okuyun, düzenleyin ve diğer biçimlere aktarın">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Android ile POTM'ten TIFF'e Dönüştürme" %}}
1. Ücretsiz API kotası ve yetkilendirme ayrıntılarını almak için <a href="https://dashboard.aspose.cloud/">Gösterge Tablosunda</a> bir hesap oluşturun
1. ```SlidesApi```'yi İstemci Kimliği ve İstemci Sırrı ile Başlatın
1. Girdi POTM dosyanızın nerede olduğuna ve ortaya çıkan TIFF dosyalarını nerede depolamak istediğinize bağlı olarak bölme yöntemlerinden birini çağırın
    - ```split```, depolamadaki bir dosyayı bölmek ve sonucu depolamaya kaydetmek için. Girilen POTM'in her slaytı, belirtilen depolama klasörüne (veya varsayılan olarak girdi dosyası klasörüne) ayrı bir TIFF olarak kaydedilir.
    - ```splitOnline```, yerel bir dosyayı bölmek ve sonucu bir ZIP arşivi olarak indirmek için. POTM girişinin her slaytı, ZIP arşivi içinde ayrı bir TIFF olarak indirilir.
    - ```splitAndSaveOnline```, yerel bir dosyayı bölmek ve sonucu depolamaya kaydetmek için. POTM girişinin her slaytı, belirtilen depolama klasörüne (veya varsayılan olarak kök klasöre) ayrı bir TIFF olarak kaydedilir.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Slides API ve Android SDK'yı Kullanmaya Başlayın" %}}
SDK'yı kendiniz derlemek için [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-android)'dan Slides Cloud SDK for Android kaynak kodunu edinin veya alternatif indirme seçenekleri için [Sürümlere](https://releases.aspose.cloud/) gidin.

[SLIDES REST API](https://products.aspose.cloud/slides/curl/) hakkında daha fazla bilgi edinmek için Swagger tabanlı [API Referansına](https://apireference.aspose.cloud/slides/) da bakın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="java" format="tiff" inputFormat="potm" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}