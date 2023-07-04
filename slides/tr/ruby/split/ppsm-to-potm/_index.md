---
title: Slides PPSM'i Ruby aracılığıyla birden fazla POTM'ye ayırın
description: REST API ve Open Source Ruby SDK ile Slides PPSM dosyalarını POTM slaytlarına ayırın
family: slides
platformtag: ruby
feature: split
informat: PPSM
outformat: POTM
platform: Ruby
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="PPSM'i Ruby ile POTM Bölünmesine Dönüştürün" h2="Açık kaynaklı Cloud SDK for Ruby ile Slides verilerini okuyun, düzenleyin ve diğer biçimlere aktarın">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Ruby ile PPSM'ten POTM'e Dönüştürme" %}}
1. Ücretsiz API kotası ve yetkilendirme ayrıntılarını almak için <a href="https://dashboard.aspose.cloud/">Gösterge Tablosunda</a> bir hesap oluşturun
1. ```SlidesApi```'yi İstemci Kimliği ve İstemci Sırrı ile Başlatın
1. Girdi PPSM dosyanızın nerede olduğuna ve ortaya çıkan POTM dosyalarını nerede depolamak istediğinize bağlı olarak bölme yöntemlerinden birini çağırın
    - ```split```, depolamadaki bir dosyayı bölmek ve sonucu depolamaya kaydetmek için. Girilen PPSM'in her slaytı, belirtilen depolama klasörüne (veya varsayılan olarak girdi dosyası klasörüne) ayrı bir POTM olarak kaydedilir.
    - ```split_online```, yerel bir dosyayı bölmek ve sonucu bir ZIP arşivi olarak indirmek için. PPSM girişinin her slaytı, ZIP arşivi içinde ayrı bir POTM olarak indirilir.
    - ```split_and_save_online```, yerel bir dosyayı bölmek ve sonucu depolamaya kaydetmek için. PPSM girişinin her slaytı, belirtilen depolama klasörüne (veya varsayılan olarak kök klasöre) ayrı bir POTM olarak kaydedilir.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Slides API ve Ruby SDK'yı Kullanmaya Başlayın" %}}
SDK'yı kendiniz derlemek için [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-ruby)'dan Slides Cloud SDK for Ruby kaynak kodunu edinin veya alternatif indirme seçenekleri için [Sürümlere](https://releases.aspose.cloud/) gidin.

[SLIDES REST API](https://products.aspose.cloud/slides/curl/) hakkında daha fazla bilgi edinmek için Swagger tabanlı [API Referansına](https://apireference.aspose.cloud/slides/) da bakın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="ruby" format="potm" inputFormat="ppsm" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}