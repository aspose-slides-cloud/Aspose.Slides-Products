---
title: Slides PPS'i Node.js aracılığıyla birden fazla ODP'ye ayırın
description: REST API ve Open Source Node.js SDK ile Slides PPS dosyalarını ODP slaytlarına ayırın
family: slides
platformtag: nodejs
feature: split
informat: PPS
outformat: ODP
platform: Node.js
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="PPS'i Node.js ile ODP Bölünmesine Dönüştürün" h2="Açık kaynaklı Cloud SDK for Node.js ile Slides verilerini okuyun, düzenleyin ve diğer biçimlere aktarın">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Node.js ile PPS'ten ODP'e Dönüştürme" %}}
1. Ücretsiz API kotası ve yetkilendirme ayrıntılarını almak için <a href="https://dashboard.aspose.cloud/">Gösterge Tablosunda</a> bir hesap oluşturun
1. ```SlidesApi```'yi İstemci Kimliği ve İstemci Sırrı ile Başlatın
1. Girdi PPS dosyanızın nerede olduğuna ve ortaya çıkan ODP dosyalarını nerede depolamak istediğinize bağlı olarak bölme yöntemlerinden birini çağırın
    - ```split```, depolamadaki bir dosyayı bölmek ve sonucu depolamaya kaydetmek için. Girilen PPS'in her slaytı, belirtilen depolama klasörüne (veya varsayılan olarak girdi dosyası klasörüne) ayrı bir ODP olarak kaydedilir.
    - ```splitOnline```, yerel bir dosyayı bölmek ve sonucu bir ZIP arşivi olarak indirmek için. PPS girişinin her slaytı, ZIP arşivi içinde ayrı bir ODP olarak indirilir.
    - ```splitAndSaveOnline```, yerel bir dosyayı bölmek ve sonucu depolamaya kaydetmek için. PPS girişinin her slaytı, belirtilen depolama klasörüne (veya varsayılan olarak kök klasöre) ayrı bir ODP olarak kaydedilir.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Slides API ve Node.js SDK'yı Kullanmaya Başlayın" %}}
SDK'yı kendiniz derlemek için [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-nodejs)'dan Slides Cloud SDK for Node.js kaynak kodunu edinin veya alternatif indirme seçenekleri için [Sürümlere](https://releases.aspose.cloud/) gidin.

[SLIDES REST API](https://products.aspose.cloud/slides/curl/) hakkında daha fazla bilgi edinmek için Swagger tabanlı [API Referansına](https://apireference.aspose.cloud/slides/) da bakın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="nodejs" format="odp" inputFormat="pps" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}