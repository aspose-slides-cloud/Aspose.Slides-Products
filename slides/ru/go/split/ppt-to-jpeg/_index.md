---
title: Разделение Slides PPT на несколько JPEG с помощью Go
description: Разделите файлы Slides PPT на слайды JPEG с помощью REST API и Go SDK с открытым исходным кодом
family: slides
platformtag: go
feature: split
informat: PPT
outformat: JPEG
platform: Go
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM ODP OTP PDF XPS PNG BMP TIFF SVG HTML5 GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Разделение PPT на несколько JPEG с помощью Go" h2="Чтение, редактирование и экспорт данных Slides в другие форматы с помощью Cloud SDK с открытым исходным кодом для Go">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Разделение PPT на JPEG с помощью Go" %}}
1. Создайте учетную запись на <a href="https://dashboard.aspose.cloud/">Панели управления</a>, чтобы получить бесплатную информацию о квотах API и авторизации.
1. Инициализируйте ```SlidesApi``` с помощью идентификатора клиента и секрета клиента
1. Вызовите один из методов разделения в зависимости от того, где находится ваш входной файл PPT и где вы хотите сохранить результирующие файлы JPEG
    - ```Split``` для разделения файла в хранилище и сохранения результата в хранилище. Каждый слайд входного PPT сохраняется как отдельный JPEG в указанной папке хранилища (или в папке входного файла по умолчанию).
    - ```SplitOnline``` для разделения локального файла и загрузки результата в виде ZIP-архива. Каждый слайд входного PPT загружается как отдельный JPEG в ZIP-архиве.
    - ```SplitAndSaveOnline``` для разделения локального файла и сохранения результата в хранилище. Каждый слайд входного PPT сохраняется как отдельный JPEG в указанной папке хранилища (или в корневой папке по умолчанию).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начать работу с Slides API и Go SDK" %}}
Получите исходный код Slides Cloud SDK для Go с [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-go), чтобы скомпилировать SDK самостоятельно, или перейти к [Выпускам](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

Также ознакомьтесь со [Справочником по API](https://apireference.aspose.cloud/slides/) на основе Swagger, чтобы узнать больше о [SLIDES REST API](https://products.aspose.cloud/slides/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="go" format="jpeg" inputFormat="ppt" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}