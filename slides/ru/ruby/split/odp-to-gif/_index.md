---
title: Разделение Slides ODP на несколько GIF с помощью Ruby
description: Разделите файлы Slides ODP на слайды GIF с помощью REST API и Ruby SDK с открытым исходным кодом
family: slides
platformtag: ruby
feature: split
informat: ODP
outformat: GIF
platform: Ruby
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 MD XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Разделение ODP на несколько GIF с помощью Ruby" h2="Чтение, редактирование и экспорт данных Slides в другие форматы с помощью Cloud SDK с открытым исходным кодом для Ruby">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Разделение ODP на GIF с помощью Ruby" %}}
1. Создайте учетную запись на <a href="https://dashboard.aspose.cloud/">Панели управления</a>, чтобы получить бесплатную информацию о квотах API и авторизации.
1. Инициализируйте ```SlidesApi``` с помощью идентификатора клиента и секрета клиента
1. Вызовите один из методов разделения в зависимости от того, где находится ваш входной файл ODP и где вы хотите сохранить результирующие файлы GIF
    - ```split``` для разделения файла в хранилище и сохранения результата в хранилище. Каждый слайд входного ODP сохраняется как отдельный GIF в указанной папке хранилища (или в папке входного файла по умолчанию).
    - ```split_online``` для разделения локального файла и загрузки результата в виде ZIP-архива. Каждый слайд входного ODP загружается как отдельный GIF в ZIP-архиве.
    - ```split_and_save_online``` для разделения локального файла и сохранения результата в хранилище. Каждый слайд входного ODP сохраняется как отдельный GIF в указанной папке хранилища (или в корневой папке по умолчанию).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начать работу с Slides API и Ruby SDK" %}}
Получите исходный код Slides Cloud SDK для Ruby с [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-ruby), чтобы скомпилировать SDK самостоятельно, или перейти к [Выпускам](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

Также ознакомьтесь со [Справочником по API](https://apireference.aspose.cloud/slides/) на основе Swagger, чтобы узнать больше о [SLIDES REST API](https://products.aspose.cloud/slides/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="ruby" format="gif" inputFormat="odp" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}