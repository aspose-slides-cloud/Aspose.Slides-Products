---
title: Разделение Slides PPTM на несколько SVG с помощью PHP
description: Разделите файлы Slides PPTM на слайды SVG с помощью REST API и PHP SDK с открытым исходным кодом
family: slides
platformtag: php
feature: split
informat: PPTM
outformat: SVG
platform: PHP
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM ODP OTP PDF XPS JPEG PNG BMP TIFF HTML5 MD GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Разделение PPTM на несколько SVG с помощью PHP" h2="Чтение, редактирование и экспорт данных Slides в другие форматы с помощью Cloud SDK с открытым исходным кодом для PHP">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Разделение PPTM на SVG с помощью PHP" %}}
1. Создайте учетную запись на <a href="https://dashboard.aspose.cloud/">Панели управления</a>, чтобы получить бесплатную информацию о квотах API и авторизации.
1. Инициализируйте ```SlidesApi``` с помощью идентификатора клиента и секрета клиента
1. Вызовите один из методов разделения в зависимости от того, где находится ваш входной файл PPTM и где вы хотите сохранить результирующие файлы SVG
    - ```split``` для разделения файла в хранилище и сохранения результата в хранилище. Каждый слайд входного PPTM сохраняется как отдельный SVG в указанной папке хранилища (или в папке входного файла по умолчанию).
    - ```splitOnline``` для разделения локального файла и загрузки результата в виде ZIP-архива. Каждый слайд входного PPTM загружается как отдельный SVG в ZIP-архиве.
    - ```splitAndSaveOnline``` для разделения локального файла и сохранения результата в хранилище. Каждый слайд входного PPTM сохраняется как отдельный SVG в указанной папке хранилища (или в корневой папке по умолчанию).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начать работу с Slides API и PHP SDK" %}}
Получите исходный код Slides Cloud SDK для PHP с [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-php), чтобы скомпилировать SDK самостоятельно, или перейти к [Выпускам](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

Также ознакомьтесь со [Справочником по API](https://apireference.aspose.cloud/slides/) на основе Swagger, чтобы узнать больше о [SLIDES REST API](https://products.aspose.cloud/slides/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="php" format="svg" inputFormat="pptm" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}