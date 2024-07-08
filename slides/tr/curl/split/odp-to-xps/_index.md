---
title: Slides ODP'i cURL aracılığıyla birden fazla XPS'ye ayırın
description: REST API ve Open Source cURL SDK ile Slides ODP dosyalarını XPS slaytlarına ayırın
family: slides
platformtag: curl
feature: split
informat: ODP
outformat: XPS
platform: cURL
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM ODP OTP PDF JPEG PNG BMP TIFF SVG HTML5 MD GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="ODP'i cURL ile XPS Bölünmesine Dönüştürün" h2="Açık kaynaklı Cloud SDK for cURL ile Slides verilerini okuyun, düzenleyin ve diğer biçimlere aktarın">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="cURL ile ODP'ten XPS'e Dönüştürme" %}}
1. Ücretsiz API kotası ve yetkilendirme ayrıntılarını almak için <a href="https://dashboard.aspose.cloud/">Gösterge Tablosunda</a> bir hesap oluşturun
1. ```SlidesApi```'yi İstemci Kimliği ve İstemci Sırrı ile Başlatın
1. Girdi ODP dosyanızın nerede olduğuna ve ortaya çıkan XPS dosyalarını nerede depolamak istediğinize bağlı olarak bölme yöntemlerinden birini çağırın
    - ```Split```, depolamadaki bir dosyayı bölmek ve sonucu depolamaya kaydetmek için. Girilen ODP'in her slaytı, belirtilen depolama klasörüne (veya varsayılan olarak girdi dosyası klasörüne) ayrı bir XPS olarak kaydedilir.
    - ```SplitOnline```, yerel bir dosyayı bölmek ve sonucu bir ZIP arşivi olarak indirmek için. ODP girişinin her slaytı, ZIP arşivi içinde ayrı bir XPS olarak indirilir.
    - ```SplitAndSaveOnline```, yerel bir dosyayı bölmek ve sonucu depolamaya kaydetmek için. ODP girişinin her slaytı, belirtilen depolama klasörüne (veya varsayılan olarak kök klasöre) ayrı bir XPS olarak kaydedilir.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Slides API ve cURL SDK'yı Kullanmaya Başlayın" %}}
SDK'yı kendiniz derlemek için [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-curl)'dan Slides Cloud SDK for cURL kaynak kodunu edinin veya alternatif indirme seçenekleri için [Sürümlere](https://releases.aspose.cloud/) gidin.

[SLIDES REST API](https://products.aspose.cloud/slides/curl/) hakkında daha fazla bilgi edinmek için Swagger tabanlı [API Referansına](https://apireference.aspose.cloud/slides/) da bakın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="curl" format="xps" inputFormat="odp" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}