---
title: PPS dosyalarındaki metni cURL aracılığıyla değiştirin
description: Slides PPS dosyalarındaki metni REST API ve Açık Kaynak cURL SDK ile değiştirin
family: slides
platformtag: curl
feature: replace-text
informat: PPS
platform: cURL
otherformats: PPT PPTX PPSX PPTM PPSM POTX POTM ODP OTP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="PPS dosyalarındaki metni cURL ile değiştirme" h2="{platform}} için açık kaynak Cloud SDK ile Slides verilerindeki metin oluşumlarını bulun ve değiştirin">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="PPS Dosyalarındaki Metni cURL ile Değiştirmek" %}}
1. Ücretsiz API kotası ve yetkilendirme ayrıntılarını almak için <a href="https://dashboard.aspose.cloud/">Gösterge Tablosunda</a> bir hesap oluşturun
1. ```SlidesApi```'yi İstemci Kimliği ve İstemci Sırrı ile Başlatın
1. PPS dosyalarınızın nerede olduğuna ve metni belgenin tamamında mı yoksa tek bir slaytta mı değiştirmeniz gerektiğine bağlı olarak metin değiştirme yöntemlerinden birini arayın
    - ```ReplacePresentationText```, depolamadaki bir sunum dosyasının tüm slaytlarında belirli bir metnin tüm oluşumlarını başka bir metinle değiştirmek için.
    - ```ReplaceSlideText```, depolamadaki bir sunum dosyasının bir slaytındaki belirli bir metnin tüm oluşumlarını bir başkasıyla değiştirmek için.
    - ```ReplacePresentationTextOnline```, istek gövdesinde iletilen bir sunum dosyasının tüm slaytlarında verilen metnin tüm oluşumlarını başka bir metinle değiştirmek için.
    - ```ReplaceSlideTextOnline```, istek gövdesinde iletilen bir sunum dosyasının bir slaydında verilen metnin tüm tekrarlarını başka bir metinle değiştirmek için kullanılır.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Slides API ve cURL SDK'yı Kullanmaya Başlayın" %}}
SDK'yı kendiniz derlemek için [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-curl)'dan Slides Cloud SDK for cURL kaynak kodunu edinin veya alternatif indirme seçenekleri için [Sürümlere](https://releases.aspose.cloud/) gidin.

[SLIDES REST API](https://products.aspose.cloud/slides/curl/) hakkında daha fazla bilgi edinmek için Swagger tabanlı [API Referansına](https://apireference.aspose.cloud/slides/) da bakın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="replaceText" language="curl" inputFormat="pps" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}