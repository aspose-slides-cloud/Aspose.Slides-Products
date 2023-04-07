---
title: Dividir Slides PPS en múltiples POTM a través de Go
description: cree, edite o convierta archivos Slides con REST API y Go SDK de código abierto
family: slides
platformtag: go
feature: split
informat: PPS
outformat: POTM
platform: Go
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTX ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Dividir PPS en múltiples POTM con Go" h2="Lea, edite y exporte datos de Slides a otros formatos con Cloud SDK de código abierto para Go">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Dividir PPS en POTM con Go" %}}
1. Cree una cuenta en <a href="https://dashboard.aspose.cloud/">el panel de control</a> para obtener una cuota de API gratuita y detalles de autorización
1. Inicialice ```SlidesApi``` con ID de cliente y Secreto de cliente
1. Llame a uno de los métodos de división, según dónde esté su archivo PPS de entrada y dónde desee almacenar los archivos POTM resultantes
    - ```Split``` para dividir un archivo en el almacenamiento y guardar el resultado en el almacenamiento. Cada diapositiva del PPS de entrada se guarda como un POTM independiente en la carpeta de almacenamiento especificada (o en la carpeta de archivos de entrada de forma predeterminada).
    - ```SplitOnline``` para dividir un archivo local y descargar el resultado como un archivo ZIP. Cada diapositiva del PPS de entrada se descargará como un POTM separado dentro del archivo ZIP.
    - ```SplitAndSaveOnline``` para dividir un archivo local y guardar el resultado en el almacenamiento. Cada diapositiva del PPS de entrada se guardará como un POTM independiente en la carpeta de almacenamiento especificada (o en la carpeta raíz de forma predeterminada).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Comience con Slides API y Go SDK" %}}
Obtenga el código fuente de Slides Cloud SDK para Go de [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-go) para compilar el SDK usted mismo o diríjase a [Versiones](https://releases.aspose.cloud/) para ver opciones de descarga alternativas.

También eche un vistazo a la [referencia de API](https://apireference.aspose.cloud/slides/) basada en Swagger para saber más sobre la [API REST SLIDES](https://products.aspose.cloud/slides/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="go" format="potm" inputFormat="pps" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}