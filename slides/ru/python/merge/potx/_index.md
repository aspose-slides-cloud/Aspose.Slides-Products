---
title: Объединение нескольких POTX файлов с помощью Python
description: Объединение нескольких файлов Slides POTX с помощью REST API и Python SDK с открытым исходным кодом
family: slides
platformtag: python
feature: merge
informat: POTX
outformat: MPEG4
platform: Python
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTM ODP OTP PDF HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Объединение нескольких файлов POTX с помощью Python" h2="Чтение, редактирование и экспорт данных Slides в другие форматы с помощью Cloud SDK с открытым исходным кодом для Python">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Объединение POTX файлов с помощью Python" %}}
1. Создайте учетную запись на <a href="https://dashboard.aspose.cloud/">Панели управления</a>, чтобы получить бесплатную информацию о квотах API и авторизации.
1. Инициализируйте ```SlidesApi``` с помощью идентификатора клиента и секрета клиента
1. Вызовите один из методов слияния в зависимости от того, где находятся ваши входные файлы POTX, где вы хотите сохранить объединенный файл и нужно ли вам объединять части файлов
    - ```merge```, чтобы добавить один или несколько файлов хранилища к файлу в хранилище.
    - ```ordered_merge```, чтобы добавить один или несколько файлов хранилища или их частей к файлу в хранилище. Вы можете указать индексы слайдов, которые нужно взять.
    - ```merge_online```, чтобы объединить несколько локальных файлов, файлов хранилища и/или файлов, доступных по URL-адресу. Вы можете указать индексы слайдов, которые нужно взять. Результат загружается в тело ответа.
    - ```merge_and_save_online```, чтобы объединить несколько локальных файлов, файлов хранилища и/или файлов, доступных по URL-адресу. Вы можете указать индексы слайдов, которые нужно взять. Результат сохраняется в хранилище.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начать работу с Slides API и Python SDK" %}}
Получите исходный код Slides Cloud SDK для Python с [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-python), чтобы скомпилировать SDK самостоятельно, или перейти к [Выпускам](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

Также ознакомьтесь со [Справочником по API](https://apireference.aspose.cloud/slides/) на основе Swagger, чтобы узнать больше о [SLIDES REST API](https://products.aspose.cloud/slides/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="merge" language="python" inputFormat="potx" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}