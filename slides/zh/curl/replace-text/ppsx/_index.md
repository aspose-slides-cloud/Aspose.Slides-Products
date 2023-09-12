---
title: 通过 cURL 替换 PPSX 文件中的文本
description: 使用 REST API 和开源 cURL SDK 替换 Slides PPSX 文件中的文本
family: slides
platformtag: curl
feature: replace-text
informat: PPSX
platform: cURL
otherformats: PPT PPTX PPS PPTM PPSM POTX POTM ODP OTP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="使用 cURL 替换 PPSX 文件中的文本" h2="使用适用于 cURL 的开源 Cloud SDK 查找并替换 Slides 数据中出现的文本">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="使用 cURL 替换 PPSX 文件中的文本" %}}
1. 在<a href="https://dashboard.aspose.cloud/">仪表板</a>创建一个帐户以获取免费的 API 配额和授权详细信息
1. 使用客户端 ID 和客户端密码初始化 ```SlidesApi```
1. 调用其中一种文本替换方法，具体取决于 PPTX 文件的位置以及是否需要替换整个文档中的文本还是单个幻灯片中的文本
    - ```ReplacePresentationText``` 将存储中演示文稿文件的所有幻灯片上出现的所有给定文本替换为另一个文本。
    - ```ReplaceSlideText``` 将存储中的演示文稿文件的一张幻灯片上出现的所有给定文本替换为另一个文本。
    - ```ReplacePresentationTextOnline``` 将请求正文中传递的演示文稿文件的所有幻灯片中出现的所有给定文本替换为另一个文本。
    - ```ReplaceSlideTextOnline``` 将在请求正文中传递的演示文稿文件的一张幻灯片中出现的所有给定文本替换为另一个文本。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="开始使用 Slides API 和 cURL SDK" %}}
从 [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-curl) 获取适用于 cURL 源代码的 Slides Cloud SDK 以自行编译 SDK 或前往[版本](https://releases.aspose.cloud/)以获取其他下载选项。
 
另请查看基于 Swagger 的 [API 参考](https://apireference.aspose.cloud/slides/)以了解有关 [SLIDES REST API](https://products.aspose.cloud/slides/curl/) 的更多信息。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="replaceText" language="curl" inputFormat="ppsx" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}