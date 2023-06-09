---
title: Разделение Slides PPSM на несколько XAML с помощью Android
description: Разделите файлы Slides на слайды с помощью REST API и Android SDK с открытым исходным кодом
family: slides
platformtag: android
feature: split
informat: PPSM
outformat: XAML
platform: Android
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 GIF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Разделение PPSM на несколько XAML с помощью Android" h2="Чтение, редактирование и экспорт данных Slides в другие форматы с помощью Cloud SDK с открытым исходным кодом для Android">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Разделение PPSM на XAML с помощью Android" %}}
1. Создайте учетную запись на <a href="https://dashboard.aspose.cloud/">Панели управления</a>, чтобы получить бесплатную информацию о квотах API и авторизации.
1. Инициализируйте ```SlidesApi``` с помощью идентификатора клиента и секрета клиента
1. Вызовите один из методов разделения в зависимости от того, где находится ваш входной файл PPSM и где вы хотите сохранить результирующие файлы XAML
    - ```split``` для разделения файла в хранилище и сохранения результата в хранилище. Каждый слайд входного PPSM сохраняется как отдельный XAML в указанной папке хранилища (или в папке входного файла по умолчанию).
    - ```splitOnline``` для разделения локального файла и загрузки результата в виде ZIP-архива. Каждый слайд входного PPSM загружается как отдельный XAML в ZIP-архиве.
    - ```splitAndSaveOnline``` для разделения локального файла и сохранения результата в хранилище. Каждый слайд входного PPSM сохраняется как отдельный XAML в указанной папке хранилища (или в корневой папке по умолчанию).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начать работу с Slides API и Android SDK" %}}
Получите исходный код Slides Cloud SDK для Android с [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-android), чтобы скомпилировать SDK самостоятельно, или перейти к [Выпускам](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

Также ознакомьтесь со [Справочником по API](https://apireference.aspose.cloud/slides/) на основе Swagger, чтобы узнать больше о [SLIDES REST API](https://products.aspose.cloud/slides/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="java" format="xaml" inputFormat="ppsm" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}