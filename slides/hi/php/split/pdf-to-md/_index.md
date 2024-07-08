---
title: Slides PDF को PHP के माध्यम से एकाधिक MDमें विभाजित करें
description: REST API और ओपन सोर्स PHP SDK के साथ Slides PDF फ़ाइलों को MD स्लाइडों में विभाजित करें
family: slides
platformtag: php
feature: split
informat: PDF
outformat: MD
platform: PHP
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="PDF को PHP के साथ अनेक MD में विभाजित करें" h2="PHP के लिए ओपन सोर्स क्लाउड एसडीके के साथ Slides डेटा को अन्य प्रारूपों में पढ़ें, संपादित करें और निर्यात करें">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="PDF को MD में विभाजित करें PHP के साथ विभाजित करें" %}}
1. मुफ़्त एपीआई कोटा और प्राधिकरण विवरण प्राप्त करने के लिए <a href="https://dashboard.aspose.cloud/">डैशबोर्ड</a> पर एक खाता बनाएं
1. क्लाइंट आईडी और क्लाइंट सीक्रेट के साथ ```SlidesApi``` प्रारंभ करें
1. विभाजन विधियों में से किसी एक को कॉल करें, यह इस बात पर निर्भर करता है कि आपकी इनपुट PDF फ़ाइल कहां है और आप परिणामी MD फ़ाइलों को कहां संग्रहीत करना चाहते हैं
    - ```split``` किसी फ़ाइल को स्टोरेज पर विभाजित करने और परिणाम को स्टोरेज में सहेजने के लिए। इनपुट PDF की प्रत्येक स्लाइड को निर्दिष्ट स्टोरेज फ़ोल्डर में (या डिफ़ॉल्ट रूप से इनपुट फ़ाइल फ़ोल्डर में) एक अलग MD के रूप में सहेजा जाता है।
    - ```splitOnline``` एक स्थानीय फ़ाइल को विभाजित करने और परिणाम को ज़िप संग्रह के रूप में डाउनलोड करने के लिए। इनपुट की प्रत्येक स्लाइड PDF को ज़िप संग्रह के भीतर एक अलग MD के रूप में डाउनलोड किया जाता है।
    - ```splitAndSaveOnline``` एक स्थानीय फ़ाइल को विभाजित करने और परिणाम को स्टोरेज में सहेजने के लिए। इनपुट PDF की प्रत्येक स्लाइड को निर्दिष्ट स्टोरेज फ़ोल्डर में (या डिफ़ॉल्ट रूप से रूट फ़ोल्डर में) एक अलग MD के रूप में सहेजा जाता है।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="स्लाइड्स एपीआई और PHP एसडीके के साथ आरंभ करें" %}}
एसडीके को स्वयं संकलित करने के लिए [गिटहब](https://github.com/aspose-slides-cloud/aspose-slides-cloud-php) से PHP स्रोत कोड के लिए स्लाइड्स क्लाउड एसडीके प्राप्त करें या वैकल्पिक डाउनलोड विकल्पों के लिए [रिलीज़](https://releases.aspose.cloud/) पर जाएं।

[स्लाइड्स रेस्ट एपीआई](https://products.aspose.cloud/slides/curl/) के बारे में अधिक जानने के लिए स्वैगर-आधारित [एपीआई संदर्भ](https://apireference.aspose.cloud/slides/) पर भी एक नजर डालें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="php" format="md" inputFormat="pdf" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}