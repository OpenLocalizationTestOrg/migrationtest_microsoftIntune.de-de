---
title: Hilfe bei iOS-Registrierungsfehlern
ms.custom: na
ms.reviewer: na
ms.service: microsoft-intune
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: c91075e8-e184-49a9-bedf-4a213872613f
robots: noindex,nofollow
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
# Hilfe bei iOS-Registrierungsfehlern
In diesem Thema erfahren Sie, wie Sie iOS-Registrierungsfehler umgehen.

## iOS-Registrierungsfehler
In der folgenden Tabelle werden Fehler aufgeführt, die bei der Registrierung von iOS-Geräten auftreten können. Für jeden Fehler werden die möglichen Ursachen und Lösungen genannt.

|Fehlermeldung|Mögliche Ursache|Auflösung mit [!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)]|Auflösung mit System Center 2012 R2 Configuration Manager|
|-----------------|--------------------|-----------------------------------------------------------------------|-------------------------------------------------------------|
|DeviceCapReached|Diese Meldung bedeutet, dass der Benutzer bereits zu viele mobile Geräte registriert hat.|Der Benutzer muss eines der derzeit registrierten mobilen Geräte aus dem Unternehmensportal entfernen, bevor er ein weiteres mobiles Gerät registriert.|Der Benutzer muss eines der derzeit registrierten mobilen Geräte aus dem Unternehmensportal entfernen, bevor er ein weiteres mobiles Gerät registriert.|
|APNSCertificateNotValid|Über den Apple Push Notification Service (APNS) ist der Zugriff auf registrierte iOS-Geräte möglich. Wenn die Schritte zur Beschaffung eines APNS-Zertifikats nicht ausgeführt wurden oder das APNS-Zertifikat abgelaufen ist, ist die Registrierung nicht möglich, und es wird diese Meldung angezeigt.|Lesen Sie den Abschnitt „Externe Abhängigkeiten bei der Registrierung von iOS-Geräten“ in [Einrichten der iOS-Verwaltung mit Microsoft Intune](../Topic/Set-up-iOS-and-Mac-management-with-Microsoft-Intune.md).|Lesen Sie den Abschnitt „Externe Abhängigkeiten bei der Registrierung von iOS-Geräten“ in [Einrichten der iOS-Verwaltung mit Microsoft Intune](../Topic/Set-up-iOS-and-Mac-management-with-Microsoft-Intune.md).|
|AccountNotOnboarded|Über den Apple Push Notification Service (APNS) ist der Zugriff auf registrierte iOS-Geräte möglich. Wenn die Schritte zur Beschaffung eines APNS-Zertifikats nicht ausgeführt wurden, ist die Registrierung nicht möglich, und es wird diese Meldung angezeigt.|Lesen Sie den Abschnitt „Externe Abhängigkeiten bei der Registrierung von iOS-Geräten“ in [Einrichten der iOS-Verwaltung mit Microsoft Intune](../Topic/Set-up-iOS-and-Mac-management-with-Microsoft-Intune.md).|Lesen Sie den Abschnitt „Externe Abhängigkeiten bei der Registrierung von iOS-Geräten“ in [Einrichten der iOS-Verwaltung mit Microsoft Intune](../Topic/Set-up-iOS-and-Mac-management-with-Microsoft-Intune.md).|
|DeviceTypeNotSupported|Diese Meldung wird möglicherweise beim Versuch angezeigt, die Registrierung über ein Nicht-iOS-Gerät auszuführen.|Stellen Sie sicher, dass auf dem Gerät mindestens Version 5.0 von iOS ausgeführt wird|Stellen Sie sicher, dass auf dem Gerät mindestens Version 5.0 von iOS ausgeführt wird|
|UserLicenseTypeInvalid|Nur Benutzer, die einer entsprechenden Benutzergruppe angehören, können ihre Geräte registrieren. Diese Meldung bedeutet, dass der Benutzer den falschen Lizenztyp für die festgelegte Autorität für die Verwaltung mobiler Geräte verwendet hat. Beispielsweise wird dieser Fehler angezeigt, wenn [!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)] als Autorität für die Verwaltung mobiler Geräte festgelegt wurde und der Benutzer eine System Center 2012 R2 Configuration Manager-Lizenz verwendet.|Lesen Sie den Abschnitt „Bereitstellen von Benutzern für die Geräteregistrierung“ in [Einrichten der iOS-Verwaltung mit Microsoft Intune](../Topic/Set-up-iOS-and-Mac-management-with-Microsoft-Intune.md).|Lesen Sie den Abschnitt „Bereitstellen von Benutzern für die Geräteregistrierung“ in [Einrichten der iOS-Verwaltung mit Microsoft Intune](../Topic/Set-up-iOS-and-Mac-management-with-Microsoft-Intune.md).|
|MdmAuthorityNotDefined|Diese Meldung bedeutet, dass die Autorität für die Verwaltung mobiler Geräte nicht in [!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)] festgelegt wurde.|Lesen Sie den Abschnitt „Festlegen der Autorität für die Verwaltung mobiler Geräte auf Microsoft Intune“ in [Einrichten der iOS-Verwaltung mit Microsoft Intune](../Topic/Set-up-iOS-and-Mac-management-with-Microsoft-Intune.md).|Lesen Sie den Abschnitt „Festlegen der Autorität für die Verwaltung mobiler Geräte auf Microsoft Intune“ in [Einrichten der iOS-Verwaltung mit Microsoft Intune](../Topic/Set-up-iOS-and-Mac-management-with-Microsoft-Intune.md).|
