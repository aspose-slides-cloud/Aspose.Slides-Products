---
title: Fusionner plusieurs fichiers POTX via Go
description: Fusionnez plusieurs fichiers Slides POTX avec l'API REST et le SDK Open Source Go
family: slides
platformtag: go
feature: merge
informat: POTX
platform: Go
otherformats: PPT PPTX PPS PPSX PPTM PPSM POTM ODP OTP PDF HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Fusionner plusieurs fichiers POTX avec Go" h2="Lisez, modifiez et exportez des données Slides vers d'autres formats avec le SDK Cloud open source pour Go">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Fusion de fichiers POTX avec Go" %}}
1. Créez un compte sur <a href="https://dashboard.aspose.cloud/">le Tableau de bord</a> pour obtenir un quota d'API gratuit et des détails d'autorisation
1. Initialisez ```SlidesApi``` avec l'identifiant client et le secret client
1. Appelez l'une des méthodes de fusion, selon l'endroit où se trouvent vos fichiers POTX d'entrée, où vous souhaitez stocker le fichier fusionné et si vous devez fusionner des parties de fichiers
    - ```Merge``` pour ajouter un ou plusieurs fichiers de stockage à un fichier sur le stockage.
    - ```OrderedMerge``` pour ajouter un ou plusieurs fichiers de stockage, ou leurs parties, à un fichier sur le stockage. Vous pouvez spécifier des indices de diapositives à prendre.
    - ```MergeOnline``` pour fusionner plusieurs fichiers locaux, fichiers de stockage et/ou fichiers disponibles par URL. Vous pouvez spécifier des indices de diapositives à prendre. Le résultat est téléchargé dans le corps de la réponse.
    - ```MergeAndSaveOnline``` pour fusionner plusieurs fichiers locaux, fichiers de stockage et/ou fichiers disponibles par URL. Vous pouvez spécifier des indices de diapositives à prendre. Le résultat est enregistré dans le stockage.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Premiers pas avec l'API Slides et le SDK Go" %}}
Obtenez le code source du SDK Slides Cloud pour Go auprès de [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-go) pour compiler le SDK vous-même ou dirigez-vous vers [les versions](https://releases.aspose.cloud/) pour d'autres options de téléchargement.

Consultez également [la référence de l'API](https://apireference.aspose.cloud/slides/) basée sur Swagger pour en savoir plus sur [l'API REST de SLIDES](https://products.aspose.cloud/slides/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="merge" language="go" inputFormat="potx" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}