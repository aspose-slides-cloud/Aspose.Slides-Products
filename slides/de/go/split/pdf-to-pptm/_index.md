---
title: PDF über Go in mehrere PPTMs aufteilen
description: Teilen Sie Slides-Dateien mit REST API und Open Source Go SDK in Folien auf
family: slides
platformtag: go
feature: split
informat: PDF
outformat: PPTM
platform: Go
otherformats: PPT PPTX PPS PPSX PPSM POTX POTM ODP OTP PDF XPS JPEG PNG BMP TIFF SVG HTML5 GIF XAML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="PDF mit Go in mehrere PPTMs aufteilen" h2="Lesen, bearbeiten und exportieren Sie Slides-Daten in andere Formate mit Open Source Cloud SDK für Go">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Aufteilen von PDF in PPTM mit Go" %}}
1. Erstellen Sie ein Konto bei <a href="https://dashboard.aspose.cloud/">Dashboard</a>, um kostenlose API-Kontingente und Autorisierungsdetails zu erhalten
1. Initialisieren Sie ```SlidesApi``` mit Client-ID und Client-Secret
1. Rufen Sie eine der Split-Methoden auf, je nachdem, wo sich Ihre PDF-Eingabedatei befindet und wo Sie die resultierenden PPTM-Dateien speichern möchten
    - ```Split```, um eine Datei im Speicher aufzuteilen und das Ergebnis im Speicher zu speichern. Jede Folie des Eingabe-PDF wird als separates PPTM im angegebenen Speicherordner (oder standardmäßig im Eingabedateiordner) gespeichert.
    - ```SplitOnline```, um eine lokale Datei aufzuteilen und das Ergebnis als ZIP-Archiv herunterzuladen. Jede Folie des Eingabe-PDF wird als separates PPTM innerhalb des ZIP-Archivs heruntergeladen.
    - ```SplitAndSaveOnline```, um eine lokale Datei aufzuteilen und das Ergebnis im Speicher zu speichern. Jede Folie des Eingabe-PDF wird als separates PPTM im angegebenen Speicherordner (oder standardmäßig im Stammordner) gespeichert.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Erste Schritte mit der Slides-API und dem Go-SDK" %}}
Holen Sie sich den Quellcode des Slides Cloud SDK für Go von [GitHub](https://github.com/aspose-slides-cloud/aspose-slides-cloud-go), um das SDK selbst zu kompilieren, oder gehen Sie zu den [Releases](https://releases.aspose.cloud/) für alternative Download-Optionen.

Sehen Sie sich auch die Swagger-basierte [API-Referenz](https://apireference.aspose.cloud/slides/) an, um mehr über die [SLIDES-REST-API](https://products.aspose.cloud/slides/curl/) zu erfahren.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/cloud-app app="split" language="go" format="pptm" inputFormat="pdf" >}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/i18n/faq-autogen >}}
{{< blocks/products/pf/agp/i18n/other-supported-autogen useCardStyle="true" >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}