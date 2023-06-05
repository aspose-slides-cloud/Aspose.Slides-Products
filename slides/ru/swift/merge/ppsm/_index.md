---
title: Объединение нескольких PPSM файлов с помощью Swift
description: Объединение нескольких файлов Slides с помощью REST API и Swift SDK с открытым исходным кодом
family: slides
platformtag: swift
feature: merge
informat: PPSM
outformat: MPEG4
platform: Swift
otherformats: PPT PPTX PPS PPSX PPTM POTX POTM ODP OTP PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Объединение нескольких файлов PPSM с помощью Swift" h2="Чтение, редактирование и экспорт данных Slides в другие форматы с помощью Cloud SDK с открытым исходным кодом для Swift">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Объединение PPSM файлов с помощью Swift" %}}
1. Создайте учетную запись на <a href="https://dashboard.aspose.cloud/">Панели управления</a>, чтобы получить бесплатную информацию о квотах API и авторизации.
1. Инициализируйте ```SlidesApi``` с помощью идентификатора клиента и секрета клиента
1. Вызовите один из методов слияния в зависимости от того, где находятся ваши входные файлы PPSM, где вы хотите сохранить объединенный файл и нужно ли вам объединять части файлов
    - ```merge```, чтобы добавить один или несколько файлов хранилища к файлу в хранилище.
    - ```orderedMerge```, чтобы добавить один или несколько файлов хранилища или их частей к файлу в хранилище. Вы можете указать индексы слайдов, которые нужно взять.
    - ```mergeOnline```, чтобы объединить несколько локальных файлов, файлов хранилища и/или файлов, доступных по URL-адресу. Вы можете указать индексы слайдов, которые нужно взять. Результат загружается в тело ответа.
    - ```mergeAndSaveOnline```, чтобы объединить несколько локальных файлов, файлов хранилища и/или файлов, доступных по URL-адресу. Вы можете указать индексы слайдов, которые нужно взять. Результат сохраняется в хранилище.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начать работу с Slides API и Swift SDK" %}}
Получите исходный код Slides Cloud SDK для Swift с [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-swift), чтобы скомпилировать SDK самостоятельно, или перейти к [Выпускам](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

Также ознакомьтесь со [Справочником по API] на основе Swagger(https://apireference.aspose.cloud/slides/), чтобы узнать больше о [SLIDES REST API](https://products.aspose. облако/slides/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="merge" language="swift" inputFormat="ppsm" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}