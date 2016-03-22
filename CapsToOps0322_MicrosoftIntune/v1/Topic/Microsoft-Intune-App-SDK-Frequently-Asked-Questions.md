---
title: H&#228;ufig gestellte Fragen zu Microsoft Intune App SDK
ms.custom: na
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 133d81c4-e550-404a-980e-64f6e843c649
translation.priority.ht: 
  - cs-cz
  - de-de
  - es-es
  - fr-fr
  - hu-hu
  - it-it
  - ja-jp
  - ko-kr
  - nl-nl
  - pl-pl
  - pt-br
  - pt-pt
  - ru-ru
  - sv-se
  - tr-tr
  - zh-cn
  - zh-tw
---
# H&#228;ufig gestellte Fragen zu Microsoft Intune App SDK
Nachfolgend einige häufig gestellte Fragen in Bezug auf das Intune App Software Development Kit (SDK):

## Ich habe ein Problem mit dem Intune App SDK oder der Dokumentation entdeckt. Wie kann ich Feedback senden oder Probleme melden?

Feedback zum Intune App SDK kann über die Website "Microsoft Connect" gesendet werden. Dort finden Sie eine Option, über die Sie Feedback senden oder ein Problem melden können. Versehen Sie gemeldete Probleme mit Priorität, und das Microsoft Intune-Team wird sich so bald wie möglich darum kümmern.

![App-Feedback-Formular](/Image/App-Feedback-Form.png)

## Wie werden Updates von Betriebssystemen und Kompatibilität vom Intune App SDK behandelt?

Wir sind bemüht sicherzustellen, dass vorhandene SDK-Funktionen so bald wie möglich auch unter neuen Versionen des Betriebssystems funktionieren. Außerdem soll das SDK aufgrund neuer Funktionen des Betriebssystems, die der Endbenutzer aus vorhandenen Anwendungen aufrufen kann, keine Abstürze von Anwendungen oder andere schwerwiegende Folgen für den Endbenutzer verursachen.

Wenn die Vendoren der Betriebssysteme genügend Vorlaufzeit einräumen, kann Intune die Betaversionen der Betriebssysteme unterstützen und vorab das Testen von Anwendungen ermöglichen. ISVs sollten vorab alle ermittelten Kompatibilitätsprobleme oder Pläne für die Veröffentlichung von Anwendungsversionen für Preview-Versionen des Betriebssystems melden.

Ohne Vorankündigung und Zustimmung von Microsoft wirken sich neue Funktionen, die dem SDK hinzugefügt werden, nicht auf die Betriebssystemkompatibilität aus; unbeabsichtigte Kompatibilitätsprobleme werden als Fehler behandelt.

## Wie wirkt sich das Intune App SDK auf meine mobile App aus?

Das SDK kann sich auf drei verschiedene Arten auf Anwendungen auswirken.
* **Leistung**: Die für die Durchsetzung von Richtlinien verwendeten Methoden können die Anwendungsleistung beeinträchtigen. Testen Sie die Leistung, melden Sie alle Probleme als Fehler, und fügen Sie die Ergebnisse der Leistungsmessung mit und ohne Richtlinie für das Szenario bei.
* **Optionale Funktionen**: Das SDK unterstützt über die API-Oberfläche optionale Funktionen (z. B. "Speichern unter"). Für diese Funktionen müssen Anwendungsänderungen unterstützt werden.
    System_CAPS_noteNote

    Telemetrie ist eine "abonnierbare" Funktion. Das iOS MAM SDK protokolliert **standardmäßig** SDK-Telemetriedaten zu Verwendungsereignissen. Diese Daten werden an Microsoft Intune gesendet. Wenn von Ihrer Anwendung keine SDK-Telemetriedaten an Microsoft Intune gesendet werden sollen, müssen Sie die SDK-Telemetrieerfassung deaktivieren, indem Sie unter `IntuneMAMSettings` die Eigenschaft `MAMTelemetryDisabled` auf "YES" setzen.
* **Richtliniendurchsetzung**: Wenn eine MAM-Richtlinie auf SDK-Anwendungen angewendet wird, verändern sich möglicherweise Anwendungsfunktionen und Benutzererfahrung. Anwendungsteams sollten mit dem Intune-Team zusammenarbeiten und ihre Anwendungen testen, um diese Auswirkungen besser zu verstehen.



