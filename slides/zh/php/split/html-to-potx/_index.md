---
title: 通过 PHP 将 Slides HTML 拆分为多个 POTX
description: 使用 REST API 和开源 PHP SDK 将 Slides HTML 文件拆分成 POTX 幻灯片
family: slides
platformtag: php
feature: split
informat: HTML
outformat: POTX
platform: PHP
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTM ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 MD GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="使用 PHP 将 HTML 拆分为多个 POTX" h2="使用适用于 PHP 的开源 Cloud SDK 读取、编辑 Slides 数据并将其导出为其他格式">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="使用 PHP 将 HTML 转换为 POTX 拆分" %}}
1. 在<a href="https://dashboard.aspose.cloud/">仪表板</a>创建一个帐户以获取免费的 API 配额和授权详细信息
1. 使用客户端 ID 和客户端密码初始化 ```SlidesApi```
1. 调用其中一种拆分方法，具体取决于输入 HTML 文件的位置以及要存储生成的 POTX 文件的位置
    - ```split``` 在存储上拆分文件并将结果保存到存储中。 输入HTML的每张幻灯片在指定的存储文件夹中保存为单独的POTX（或默认保存到输入文件夹）。
    - ```splitOnline``` 拆分本地文件并将结果下载为 ZIP 存档。 输入 HTML 的每张幻灯片都在 ZIP 存档中作为单独的 POTX 下载。
    - ```splitAndSaveOnline``` 拆分本地文件并将结果保存到存储中。 输入的 HTML 的每张幻灯片都作为单独的 POTX 保存在指定的存储文件夹中（或默认保存到根文件夹）。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="开始使用 Slides API 和 PHP SDK" %}}
从 [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-php) 获取适用于 PHP 源代码的 Slides Cloud SDK 以自行编译 SDK 或前往[版本](https://releases.aspose.cloud/)以获取其他下载选项。
 
另请查看基于 Swagger 的 [API 参考](https://apireference.aspose.cloud/slides/)以了解有关 [SLIDES REST API](https://products.aspose.cloud/slides/curl/) 的更多信息。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="php" format="potx" inputFormat="html" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}