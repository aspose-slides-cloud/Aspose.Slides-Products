---
title: Разделение Slides PPS на несколько POTM с помощью .NET
description: Разделите файлы Slides PPS на слайды POTM с помощью REST API и .NET SDK с открытым исходным кодом
family: slides
platformtag: net
feature: split
informat: PPS
outformat: POTM
platform: .NET
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 MD GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Разделение PPS на несколько POTM с помощью .NET" h2="Чтение, редактирование и экспорт данных Slides в другие форматы с помощью Cloud SDK с открытым исходным кодом для .NET">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Разделение PPS на POTM с помощью .NET" %}}
1. Создайте учетную запись на <a href="https://dashboard.aspose.cloud/">Панели управления</a>, чтобы получить бесплатную информацию о квотах API и авторизации.
1. Инициализируйте ```SlidesApi``` с помощью идентификатора клиента и секрета клиента
1. Вызовите один из методов разделения в зависимости от того, где находится ваш входной файл PPS и где вы хотите сохранить результирующие файлы POTM
    - ```Split``` для разделения файла в хранилище и сохранения результата в хранилище. Каждый слайд входного PPS сохраняется как отдельный POTM в указанной папке хранилища (или в папке входного файла по умолчанию).
    - ```SplitOnline``` для разделения локального файла и загрузки результата в виде ZIP-архива. Каждый слайд входного PPS загружается как отдельный POTM в ZIP-архиве.
    - ```SplitAndSaveOnline``` для разделения локального файла и сохранения результата в хранилище. Каждый слайд входного PPS сохраняется как отдельный POTM в указанной папке хранилища (или в корневой папке по умолчанию).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начать работу с Slides API и .NET SDK" %}}
Получите исходный код Slides Cloud SDK для .NET с [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-dotnet), чтобы скомпилировать SDK самостоятельно, или перейти к [Выпускам](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

Также ознакомьтесь со [Справочником по API](https://apireference.aspose.cloud/slides/) на основе Swagger, чтобы узнать больше о [SLIDES REST API](https://products.aspose.cloud/slides/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="net" format="potm" inputFormat="pps" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}