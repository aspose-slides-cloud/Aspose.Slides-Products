---
title: Объединение нескольких OTP файлов с помощью cURL
description: Объединение нескольких файлов Slides OTP с помощью REST API и cURL SDK с открытым исходным кодом
family: slides
platformtag: curl
feature: merge
informat: OTP
outformat: MPEG4
platform: cURL
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX POTM ODP PDF HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Объединение нескольких файлов OTP с помощью cURL" h2="Чтение, редактирование и экспорт данных Slides в другие форматы с помощью Cloud SDK с открытым исходным кодом для cURL">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Объединение OTP файлов с помощью cURL" %}}
1. Создайте учетную запись на <a href="https://dashboard.aspose.cloud/">Панели управления</a>, чтобы получить бесплатную информацию о квотах API и авторизации.
1. Инициализируйте ```SlidesApi``` с помощью идентификатора клиента и секрета клиента
1. Вызовите один из методов слияния в зависимости от того, где находятся ваши входные файлы OTP, где вы хотите сохранить объединенный файл и нужно ли вам объединять части файлов
    - ```Merge```, чтобы добавить один или несколько файлов хранилища к файлу в хранилище.
    - ```OrderedMerge```, чтобы добавить один или несколько файлов хранилища или их частей к файлу в хранилище. Вы можете указать индексы слайдов, которые нужно взять.
    - ```MergeOnline```, чтобы объединить несколько локальных файлов, файлов хранилища и/или файлов, доступных по URL-адресу. Вы можете указать индексы слайдов, которые нужно взять. Результат загружается в тело ответа.
    - ```MergeAndSaveOnline```, чтобы объединить несколько локальных файлов, файлов хранилища и/или файлов, доступных по URL-адресу. Вы можете указать индексы слайдов, которые нужно взять. Результат сохраняется в хранилище.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начать работу с Slides API и cURL SDK" %}}
Получите исходный код Slides Cloud SDK для cURL с [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-curl), чтобы скомпилировать SDK самостоятельно, или перейти к [Выпускам](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

Также ознакомьтесь со [Справочником по API](https://apireference.aspose.cloud/slides/) на основе Swagger, чтобы узнать больше о [SLIDES REST API](https://products.aspose.cloud/slides/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="merge" language="curl" inputFormat="otp" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}