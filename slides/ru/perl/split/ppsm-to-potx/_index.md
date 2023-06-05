---
title: Разделение Slides PPSM на несколько POTX с помощью Perl
description: Разделите файлы Slides на слайды с помощью REST API и Perl SDK с открытым исходным кодом
family: slides
platformtag: perl
feature: split
informat: PPSM
outformat: POTX
platform: Perl
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTM ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Разделение PPSM на несколько POTX с помощью Perl" h2="Чтение, редактирование и экспорт данных Slides в другие форматы с помощью Cloud SDK с открытым исходным кодом для Perl">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Разделение PPSM на POTX с помощью Perl" %}}
1. Создайте учетную запись на <a href="https://dashboard.aspose.cloud/">Панели управления</a>, чтобы получить бесплатную информацию о квотах API и авторизации.
1. Инициализируйте ```SlidesApi``` с помощью идентификатора клиента и секрета клиента
1. Вызовите один из методов разделения в зависимости от того, где находится ваш входной файл PPSM и где вы хотите сохранить результирующие файлы POTX
    - ```split``` для разделения файла в хранилище и сохранения результата в хранилище. Каждый слайд входного PPSM сохраняется как отдельный POTX в указанной папке хранилища (или в папке входного файла по умолчанию).
    - ```split_online``` для разделения локального файла и загрузки результата в виде ZIP-архива. Каждый слайд входного PPSM загружается как отдельный POTX в ZIP-архиве.
    - ```split_and_save_online``` для разделения локального файла и сохранения результата в хранилище. Каждый слайд входного PPSM сохраняется как отдельный POTX в указанной папке хранилища (или в корневой папке по умолчанию).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начать работу с Slides API и Perl SDK" %}}
Получите исходный код Slides Cloud SDK для Perl с [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-perl), чтобы скомпилировать SDK самостоятельно, или перейти к [Выпускам](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

Также ознакомьтесь со [Справочником по API] на основе Swagger(https://apireference.aspose.cloud/slides/), чтобы узнать больше о [SLIDES REST API](https://products.aspose. облако/slides/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="perl" format="potx" inputFormat="ppsm" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}