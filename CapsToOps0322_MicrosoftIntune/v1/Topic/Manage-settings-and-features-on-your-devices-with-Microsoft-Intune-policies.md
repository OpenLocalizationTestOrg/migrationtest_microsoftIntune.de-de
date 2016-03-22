---
title: Verwalten von Einstellungen und Features auf Ihren Ger&#228;ten mit Microsoft Intune-Richtlinien
ms.custom: na
ms.reviewer: na
ms.service: microsoft-intune
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: d27f2739-9791-4aae-a9db-01a4e59ccfe5
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
# Verwalten von Einstellungen und Features auf Ihren Ger&#228;ten mit Microsoft Intune-Richtlinien
[!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)] verwendet **Richtlinien**, mit denen Sie viele Sicherheits- und Funktionseinstellungen für registrierte mobile Geräte konfigurieren können. Dazu zählen u. a.:

-   Hardwareeinstellungen wie das Zulassen der Nutzung der Gerätekamera oder Bluetooth-Funktion

-   Kennworteinstellungen wie Kennwortlänge und -sicherheit

-   Zulassen und Blockieren von Apps – Sie können Apps konfigurieren, die für Ihre Organisation kompatibel oder nicht kompatibel sind, und anschließend nicht kompatible Geräte melden lassen (bei Windows Phone-Geräten können Sie die Installation oder Nutzung von Apps sperren).

-   Einstellungen für den Kioskmodus – Sie können bestimmte Features des Geräts einschränken, so z. B. nur die Ausführung einer einzigen App zulassen oder den An-/Aus-Schalter oder die Lautstärkeregelung deaktivieren.

Anhand der Informationen in diesem Thema können Sie entscheiden, welche Richtlinie Sie zum Verwalten Ihrer Geräte benötigen.

> [!TIP]
> Weitere Informationen über die Verwendung von Richtlinien finden Sie unter [Verwenden von Richtlinien zum Verwalten von Computern und mobilen Geräten mit Microsoft Intune](../Topic/Use-policies-to-manage-computers-and-mobile-devices-with-Microsoft-Intune.md).

## <a name="BKMK_WhatPol"></a>Auswählen der zu verwendenden Richtlinie

### Android

|Name der Richtlinie|Zweck|
|-----------------------|---------|
|**Benutzerdefinierte Konfiguration (Android 4 und höher, Samsung KNOX Standard 4.0 und höher)**|-   Bereitstellen von OMA-URI-Einstellungen, wie z. B. WLAN-Einstellungen, die zum Steuern von Gerätefunktionen dienen. Dies ist hilfreich, wenn die benötigte Einstellung nicht in einer Konfigurationsrichtlinie für mobile Geräte verfügbar ist.<br /><br />Details finden Sie unter [Benutzerdefinierte Android-Richtlinieneinstellungen in Microsoft Intune](../Topic/Android-custom-policy-settings-in-Microsoft-Intune.md).|
|**E-Mail-Profil (Samsung KNOX Standard 4.0 und höher)**|-   Erstellen, Bereitstellen und Überwachen von Exchange ActiveSync-E-Mail-Einstellungen auf verwalteten Geräten. Auf diese Weise erhalten Benutzer Zugriff auf Unternehmens-E-Mails auf ihren persönlichen Geräten, ohne dafür ein Setup vornehmen zu müssen.<br /><br />Details finden Sie unter [Konfigurieren des Zugriffs auf Unternehmens-E-Mail mithilfe von E-Mail-Profilen in Microsoft Intune](../Topic/Configure-access-to-corporate-email-using-email-profiles-with-Microsoft-Intune.md).|
|**Allgemeine Konfiguration (Android 4 und höher, Samsung KNOX Standard 4.0 und höher)**|-   Konfigurieren der Sicherheits- und Funktionseinstellungen mobiler Geräte.<br />-   Angeben kompatibler und nicht kompatibler Apps und Melden ihrer Nutzung.<br />-   Konfigurieren des Kioskmodus, bei dem auf Geräten alle außer bestimmten Features gesperrten werden, sodass das Gerät z. B. nur eine App ausführen kann oder der Lautstärkeregler deaktiviert wird.<br /><br />Details finden Sie unter [Einstellungen für Android-Konfigurationsrichtlinien in Microsoft Intune](../Topic/Android-configuration-policy-settings-in-Microsoft-Intune.md).|
|**PKCS #12-Zertifikatprofil (PFX) (Android 4 und höher)**|-   Verwenden Sie dieses Profil, um PFX-Einstellungen für Gerätezertifikatanforderungen bereitzustellen.<br /><br />Details finden Sie unter [Aktivieren des Zugriffs auf Unternehmensressourcen mithilfe von Zertifikatprofilen in Microsoft Intune](../Topic/Enable-access-to-company-resources-using-certificate-profiles-with-Microsoft-Intune.md).|
|**SCEP-Zertifikatprofil (Android 4 und höher)**|-   Konfigurieren eines Simple Certificate Enrollment Protocol-Zertifikats, das mit einem Zertifikat eines vertrauenswürdigen mobilen Geräts zum Authentifizieren von mobilen Geräten verwendet werden kann, damit diese Zugriff auf Netzwerkressourcen wie z. B. die von WLAN- und VPN-Profilen konfigurierten erhalten.<br /><br />Details finden Sie unter [Aktivieren des Zugriffs auf Unternehmensressourcen mithilfe von Zertifikatprofilen in Microsoft Intune](../Topic/Enable-access-to-company-resources-using-certificate-profiles-with-Microsoft-Intune.md).|
|**Vertrauenswürdiges Zertifikatprofil (Android 4 und höher)**|-   Konfigurieren eines Zertifikats für ein vertrauenswürdiges mobiles Gerät, das zum Authentifizieren von mobilen Geräten verwendet werden kann, damit diese Zugriff auf Netzwerkressourcen wie z. B. die von WLAN- und VPN-Profilen konfigurierten erhalten.<br /><br />Details finden Sie unter [Aktivieren des Zugriffs auf Unternehmensressourcen mithilfe von Zertifikatprofilen in Microsoft Intune](../Topic/Enable-access-to-company-resources-using-certificate-profiles-with-Microsoft-Intune.md).|
|**VPN-Profil (Android 4 und höher)**|-   Konfigurieren und Bereitstellen von Einstellungen, mit denen Benutzer sicheren Zugriff auf ihr Unternehmensnetzwerk von ihrem mobilen Gerät aus erhalten. Durch Bereitstellen dieser Einstellungen erleichtern Sie dem Endbenutzer, sich mit der Arbeit zu verbinden.<br /><br />Details finden Sie unter [Unterstützen von Benutzern beim Verbinden mit ihrer Arbeit über VPN-Profile in Microsoft Intune](../Topic/Help-users-connect-to-their-work-using-VPN-profiles-with-Microsoft-Intune.md).|
|**WLAN-Profil (Android 4 und höher)**|-   Konfigurieren und Bereitstellen von Einstellungen für drahtlose Netzwerke für Benutzer in Ihrer Organisation. Durch Bereitstellen dieser Einstellungen erleichtern Sie dem Endbenutzer das Herstellen einer Verbindung mit dem drahtlosen Netzwerk.<br /><br />Details finden Sie unter [Benutzern mithilfe von WLAN-Profilen mit Microsoft Intune die Verbindung mit Unternehmensnetzwerken erleichtern](../Topic/Help-users-connect-to-company-networks-using-Wi-Fi-profiles-with-Microsoft-Intune.md).|

### iOS

|Name der Richtlinie|Zweck|
|-----------------------|---------|
|**Benutzerdefinierte Konfiguration (iOS 7.1 und höher)**|-   Bereitstellen von Konfigurationsprofilen für iOS-Geräte, die Sie mit dem Apple-Konfigurator-Tool erstellt haben, Dies ist hilfreich, wenn die benötigte Einstellung nicht in einer Konfigurationsrichtlinie für mobile Geräte verfügbar ist.<br /><br />Details finden Sie unter [Benutzerdefinierte iOS-Richtlinieneinstellungen in Microsoft Intune](../Topic/iOS-custom-policy-settings-in-Microsoft-Intune.md).|
|**E-Mail-Profil (iOS 7.1 und höher)**|-   Erstellen, Bereitstellen und Überwachen von Exchange ActiveSync-E-Mail-Einstellungen auf verwalteten Geräten. Auf diese Weise erhalten Benutzer Zugriff auf Unternehmens-E-Mails auf ihren persönlichen Geräten, ohne dafür ein Setup vornehmen zu müssen.<br /><br />Details finden Sie unter [Konfigurieren des Zugriffs auf Unternehmens-E-Mail mithilfe von E-Mail-Profilen in Microsoft Intune](../Topic/Configure-access-to-corporate-email-using-email-profiles-with-Microsoft-Intune.md).|
|**Allgemeine Konfiguration (iOS 7.1 und höher)**|-   Konfigurieren der Sicherheits- und Funktionseinstellungen mobiler Geräte.<br />-   Angeben kompatibler und nicht kompatibler Apps und Melden ihrer Nutzung.<br />-   Konfigurieren des Kioskmodus, bei dem auf Geräten alle außer bestimmten Features gesperrten werden, sodass das Gerät z. B. nur eine App ausführen kann oder der Lautstärkeregler deaktiviert wird.<br /><br />Details finden Sie unter [Einstellungen für iOS-Konfigurationsrichtlinien in Microsoft Intune](../Topic/iOS-configuration-policy-settings-in-Microsoft-Intune.md).|
|**SCEP-Zertifikatprofil (iOS 7.1 und höher)**|-   Konfigurieren eines Simple Certificate Enrollment Protocol-Zertifikats, das mit einem Zertifikat eines vertrauenswürdigen mobilen Geräts zum Authentifizieren von mobilen Geräten verwendet werden kann, damit diese Zugriff auf Netzwerkressourcen wie z. B. die von WLAN- und VPN-Profilen konfigurierten erhalten.<br /><br />Details finden Sie unter [Aktivieren des Zugriffs auf Unternehmensressourcen mithilfe von Zertifikatprofilen in Microsoft Intune](../Topic/Enable-access-to-company-resources-using-certificate-profiles-with-Microsoft-Intune.md).|
|**Vertrauenswürdiges Zertifikatprofil (iOS 7.1 und höher)**|-   Konfigurieren eines Zertifikats für ein vertrauenswürdiges mobiles Gerät, das zum Authentifizieren von mobilen Geräten verwendet werden kann, damit diese Zugriff auf Netzwerkressourcen wie z. B. die von WLAN- und VPN-Profilen konfigurierten erhalten.<br /><br />Details finden Sie unter [Aktivieren des Zugriffs auf Unternehmensressourcen mithilfe von Zertifikatprofilen in Microsoft Intune](../Topic/Enable-access-to-company-resources-using-certificate-profiles-with-Microsoft-Intune.md).|
|**VPN-Profil (iOS 7.1 und höher)**|-   Konfigurieren und Bereitstellen von Einstellungen, mit denen Benutzer sicheren Zugriff auf ihr Unternehmensnetzwerk von ihrem mobilen Gerät aus erhalten. Durch Bereitstellen dieser Einstellungen erleichtern Sie dem Endbenutzer, sich mit der Arbeit zu verbinden.<br /><br />Details finden Sie unter [Unterstützen von Benutzern beim Verbinden mit ihrer Arbeit über VPN-Profile in Microsoft Intune](../Topic/Help-users-connect-to-their-work-using-VPN-profiles-with-Microsoft-Intune.md).|
|**WLAN-Profil (iOS 7.1 und höher)**|-   Konfigurieren und Bereitstellen von Einstellungen für drahtlose Netzwerke für Benutzer in Ihrer Organisation. Durch Bereitstellen dieser Einstellungen erleichtern Sie dem Endbenutzer das Herstellen einer Verbindung mit dem drahtlosen Netzwerk.<br /><br />Details finden Sie unter [Benutzern mithilfe von WLAN-Profilen mit Microsoft Intune die Verbindung mit Unternehmensnetzwerken erleichtern](../Topic/Help-users-connect-to-company-networks-using-Wi-Fi-profiles-with-Microsoft-Intune.md).|
|**Konfigurationsrichtlinie für mobile Apps (iOS 7.1 und höher)**|-   Verwenden Sie Konfigurationsrichtlinien für mobile Apps, um automatisch Einstellungen bereitzustellen, die beim Ausführen einer iOS-App durch den Benutzer erforderlich sind.<br /><br />Details finden Sie unter [Konfigurieren von Apps mit Konfigurationsrichtlinien für mobile Apps in Microsoft Intune](../Topic/Configure-apps-with-mobile-app-configuration-policies-in-Microsoft-Intune.md).|

### Mac OS X

|Name der Richtlinie|Zweck|
|-----------------------|---------|
|**Benutzerdefinierte Konfiguration (Mac OS X 10.9 und höher)**|-   Bereitstellen von Konfigurationsprofilen für Mac-Computer, die Sie mit dem Apple Configurator-Tool erstellt haben. Dies ist hilfreich, wenn die benötigte Einstellung nicht in einer Konfigurationsrichtlinie für mobile Geräte verfügbar ist.<br /><br />Details finden Sie unter [Benutzerdefinierte Mac OS X-Richtlinieneinstellungen in Microsoft Intune](../Topic/Mac-OS-X-custom-policy-settings-in-Microsoft-Intune.md).|
|**Allgemeine Konfiguration (Mac OS X 10.9 und höher)**|-   Konfigurieren der Sicherheits- und Funktionseinstellungen mobiler Geräte.<br />-   Angeben kompatibler und nicht kompatibler Apps und Melden ihrer Nutzung.<br /><br />Details finden Sie unter [Einstellungen für Mac OS X-Konfigurationsrichtlinien in Microsoft Intune](../Topic/Mac-OS-X-configuration-policy-settings-in-Microsoft-Intune.md).|
|**SCEP-Zertifikatprofil (Mac OS X 10.9 und höher)**|-   Konfigurieren eines Simple Certificate Enrollment Protocol-Zertifikats, das mit einem Zertifikat eines vertrauenswürdigen mobilen Geräts zum Authentifizieren von mobilen Geräten verwendet werden kann, damit diese Zugriff auf Netzwerkressourcen wie z. B. die von WLAN- und VPN-Profilen konfigurierten erhalten.<br /><br />Details finden Sie unter [Aktivieren des Zugriffs auf Unternehmensressourcen mithilfe von Zertifikatprofilen in Microsoft Intune](../Topic/Enable-access-to-company-resources-using-certificate-profiles-with-Microsoft-Intune.md).|
|**Vertrauenswürdiges Zertifikatprofil (Mac OS X 10.9 und höher)**|-   Konfigurieren eines Zertifikats für ein vertrauenswürdiges mobiles Gerät, das zum Authentifizieren von mobilen Geräten verwendet werden kann, damit diese Zugriff auf Netzwerkressourcen wie z. B. die von WLAN- und VPN-Profilen konfigurierten erhalten.<br /><br />Details finden Sie unter [Aktivieren des Zugriffs auf Unternehmensressourcen mithilfe von Zertifikatprofilen in Microsoft Intune](../Topic/Enable-access-to-company-resources-using-certificate-profiles-with-Microsoft-Intune.md).|
|**VPN-Profil (Mac OS X 10.9 und höher)**|-   Konfigurieren und Bereitstellen von Einstellungen, mit denen Benutzer sicheren Zugriff auf ihr Unternehmensnetzwerk von ihrem mobilen Gerät aus erhalten. Durch Bereitstellen dieser Einstellungen erleichtern Sie dem Endbenutzer, sich mit der Arbeit zu verbinden.<br /><br />Details finden Sie unter [Unterstützen von Benutzern beim Verbinden mit ihrer Arbeit über VPN-Profile in Microsoft Intune](../Topic/Help-users-connect-to-their-work-using-VPN-profiles-with-Microsoft-Intune.md).|
|**WLAN-Profil (Mac OS X 10.9 und höher)**|-   Konfigurieren und Bereitstellen von Einstellungen für drahtlose Netzwerke für Benutzer in Ihrer Organisation. Durch Bereitstellen dieser Einstellungen erleichtern Sie dem Endbenutzer das Herstellen einer Verbindung mit dem drahtlosen Netzwerk.<br /><br />Details finden Sie unter [Benutzern mithilfe von WLAN-Profilen mit Microsoft Intune die Verbindung mit Unternehmensnetzwerken erleichtern](../Topic/Help-users-connect-to-company-networks-using-Wi-Fi-profiles-with-Microsoft-Intune.md).|

### Windows
Gilt nur für Windows Phone und registrierte Windows-Geräte.

|Name der Richtlinie|Zweck|
|-----------------------|---------|
|**Benutzerdefinierte Konfiguration (Windows 10 Desktop und Mobile und höher)**|-   Bereitstellen von OMA-URI-Einstellungen, die zum Steuern von Gerätefunktionen verwendet werden können. Dies ist hilfreich, wenn die benötigte Einstellung nicht in einer Konfigurationsrichtlinie für mobile Geräte verfügbar ist.<br />    Eine Liste der verfügbaren Einstellungen finden Sie unter [Benutzerdefinierte URI-Einstellungen für Windows 10-Geräte](../Topic/Custom-URI-settings-for-Windows-10-devices.md).<br /><br />Details finden Sie unter [Benutzerdefinierte Windows 10-Richtlinieneinstellungen in Microsoft Intune](../Topic/Windows-10-custom-policy-settings-in-Microsoft-Intune.md).|
|**Benutzerdefinierte Konfiguration (Windows Phone 8.1 und höher)**|-   Bereitstellen von OMA-URI-Einstellungen, die zum Steuern von Gerätefunktionen verwendet werden können. Dies ist hilfreich, wenn die benötigte Einstellung nicht in einer Konfigurationsrichtlinie für mobile Geräte verfügbar ist.<br /><br />Details finden Sie unter [Benutzerdefinierte Windows Phone-Richtlinieneinstellungen in Microsoft Intune](../Topic/Windows-Phone-custom-policy-settings-in-Microsoft-Intune.md).|
|**E-Mail-Profil (Windows Phone 8 und höher)**<br /><br />**E-Mail-Profil (Windows 10 Desktop und Windows 10 Mobile oder höher)**|-   Erstellen, Bereitstellen und Überwachen von Exchange ActiveSync-E-Mail-Einstellungen auf verwalteten Geräten. Auf diese Weise erhalten Benutzer Zugriff auf Unternehmens-E-Mails auf ihren persönlichen Geräten, ohne dafür ein Setup vornehmen zu müssen.<br /><br />Details finden Sie unter [Konfigurieren des Zugriffs auf Unternehmens-E-Mail mithilfe von E-Mail-Profilen in Microsoft Intune](../Topic/Configure-access-to-corporate-email-using-email-profiles-with-Microsoft-Intune.md).|
|**Allgemeine Konfiguration (Windows 10 Desktop und Mobile und höher)**|-   Konfigurieren der Sicherheits- und Funktionseinstellungen für registrierte mobile Geräte unter Windows 10 Desktop und Mobile.<br /><br />Details finden Sie unter [Einstellungen für Windows 10-Konfigurationsrichtlinien in Microsoft Intune](../Topic/Windows-10-configuration-policy-settings-in-Microsoft-Intune.md).|
|**Allgemeine Konfiguration (Windows 10 Team und höher)**|-   Konfigurieren Sie die Gerätesicherheit und die Funktionseinstellungen für registrierte Windows 10 Team-Geräte (z. B. ein Surface Hub-Gerät).<br /><br />Details finden Sie unter [Einstellungen für Windows Team-Konfigurationsrichtlinie in Microsoft Intune](../Topic/Windows-Team-configuration-policy-settings-in-Microsoft-Intune.md).|
|**Allgemeine Konfiguration (Windows 8.1 und höher)**|-   Konfigurieren der Sicherheit- und Funktionseinstellungen mobiler Geräte für registrierte Windows-Geräte.<br /><br />Details finden Sie unter [Einstellungen für Windows-Konfigurationsrichtlinien in Microsoft Intune](../Topic/Windows-configuration-policy-settings-in-Microsoft-Intune.md).|
|**Allgemeine Konfiguration (Windows Phone 8.1 und höher)**|-   Konfigurieren der Sicherheits- und Funktionseinstellungen mobiler Geräte.<br />-   Angeben von Apps, die Benutzer verwenden bzw. nicht verwenden können, um zu verhindern, dass nicht kompatible Apps installiert oder verwendet werden.<br /><br />Details finden Sie unter [Einstellungen für Windows Phone-Konfigurationsrichtlinien in Microsoft Intune](../Topic/Windows-Phone-configuration-policy-settings-in-Microsoft-Intune.md).|
|**PKCS #12-Zertifikatprofil (PFX) (Windows 10 Desktop und Mobile und höher)**|-   Verwenden Sie dieses Profil, um PFX-Einstellungen für Gerätezertifikatanforderungen bereitzustellen.<br /><br />Details finden Sie unter [Aktivieren des Zugriffs auf Unternehmensressourcen mithilfe von Zertifikatprofilen in Microsoft Intune](../Topic/Enable-access-to-company-resources-using-certificate-profiles-with-Microsoft-Intune.md).|
|**SCEP-Zertifikatprofil (Windows 8.1 und höher)**<br /><br />**SCEP-Zertifikatprofil (Windows Phone 8.1 und höher)**|-   Konfigurieren eines Simple Certificate Enrollment Protocol-Zertifikats, das mit einem Zertifikat eines vertrauenswürdigen mobilen Geräts zum Authentifizieren von mobilen Geräten verwendet werden kann, damit diese Zugriff auf Netzwerkressourcen wie z. B. die von WLAN- und VPN-Profilen konfigurierten erhalten.<br /><br />Details finden Sie unter [Aktivieren des Zugriffs auf Unternehmensressourcen mithilfe von Zertifikatprofilen in Microsoft Intune](../Topic/Enable-access-to-company-resources-using-certificate-profiles-with-Microsoft-Intune.md).|
|**Vertrauenswürdiges Zertifikatprofil (Windows 8.1 und höher)**<br /><br />**Vertrauenswürdiges Zertifikatprofil (Windows Phone 8.1 und höher)**|-   Konfigurieren eines Zertifikats für ein vertrauenswürdiges mobiles Gerät, das zum Authentifizieren von mobilen Geräten verwendet werden kann, damit diese Zugriff auf Netzwerkressourcen wie z. B. die von WLAN- und VPN-Profilen konfigurierten erhalten.<br /><br />Details finden Sie unter [Aktivieren des Zugriffs auf Unternehmensressourcen mithilfe von Zertifikatprofilen in Microsoft Intune](../Topic/Enable-access-to-company-resources-using-certificate-profiles-with-Microsoft-Intune.md).|
|**VPN-Profil (Windows 10 Desktop und Mobile und höher)**<br /><br />**VPN-Profil (Windows 8.1 und höher)**<br /><br />**VPN-Profil (Windows Phone 8.1 und höher)**|-   Konfigurieren und Bereitstellen von Einstellungen, mit denen Benutzer sicheren Zugriff auf ihr Unternehmensnetzwerk von ihrem mobilen Gerät aus erhalten. Durch Bereitstellen dieser Einstellungen erleichtern Sie dem Endbenutzer, sich mit der Arbeit zu verbinden.<br /><br />Details finden Sie unter [Unterstützen von Benutzern beim Verbinden mit ihrer Arbeit über VPN-Profile in Microsoft Intune](../Topic/Help-users-connect-to-their-work-using-VPN-profiles-with-Microsoft-Intune.md).|
|**Importieren von WLAN-Konfigurationen**|-   Importieren und Bereitstellen von Windows Wi-Fi-Konfigurationen, die Sie zuvor in eine Datei exportiert haben.<br /><br />Details finden Sie unter [Benutzern mithilfe von WLAN-Profilen mit Microsoft Intune die Verbindung mit Unternehmensnetzwerken erleichtern](../Topic/Help-users-connect-to-company-networks-using-Wi-Fi-profiles-with-Microsoft-Intune.md).|

### Software

|Name der Richtlinie|Zweck|
|-----------------------|---------|
|**Richtlinie für Managed Browser (Android 4 und höher)**<br /><br />**Richtlinie für Managed Browser (iOS 7.1 und höher)**|-   Angeben der Websites, auf die Benutzer zugreifen bzw. nicht zugreifen können, wenn sie die Managed Browser-App verwenden.<br /><br />Details finden Sie unter [Verwalten des Internetzugriffs mittels Richtlinien für verwaltete Browser mit Microsoft Intune](../Topic/Manage-Internet-access-using-managed-browser-policies-with-Microsoft-Intune.md).|
|**Richtlinie zur mobilen Anwendungsverwaltung (Android 4 und höher)**<br /><br />**Richtlinie zur Verwaltung von mobilen Anwendungen (iOS 7.1 und höher)**|-   Ändern der Funktionalität von bereitgestellten Apps, um sie an die Konformitäts- und Sicherheitsrichtlinien Ihres Unternehmens anzupassen. Sie können z. B. Ausschneide-, Kopier- und Einfügevorgänge innerhalb einer eingeschränkten App einschränken oder eine App so konfigurieren, dass alle Weblinks innerhalb des Managed Browser geöffnet werden.<br /><br />Weitere Einzelheiten finden Sie unter [Schützen von Daten mithilfe der Verwaltungsrichtlinien für mobile Anwendungen mit Microsoft Intune](../Topic/Configure-and-deploy-mobile-application-management-policies-in-the-Microsoft-Intune-console.md).|

### Allgemeine Einstellungen für mobile Geräte

|Name der Richtlinie|Zweck|
|-----------------------|---------|
|**Exchange ActiveSync-Richtlinie**|-   Konfigurieren von Sicherheits- und Funktionseinstellungen mobiler Geräte für Geräte, die von Exchange ActiveSync verwaltet werden.<br /><br />Details finden Sie unter [Einstellungen für Exchange ActiveSync-Richtlinien in Microsoft Intune](../Topic/Exchange-ActiveSync-policy-settings-in-Microsoft-Intune.md).|
|**Sicherheitsrichtlinie für mobiles Gerät**|<ul><li>Konfiguriert die Einstellungen für mobile Geräte (alle Plattformen), einschließlich:<br /><br /><ul><li>Sicherheit</li><li>Verschlüsselung</li><li>System</li><li>E-Mail</li><li>Applications</li></ul></li></ul> **Important:** [!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)] bietet jetzt getrennte **Konfigurationsrichtlinien** für jede Geräteplattform, wobei diese Richtlinien die neuesten Einstellungen berücksichtigen, die Sie verwenden können. Sie können die Sicherheitsrichtlinie für mobile Geräte weiter nutzen, wobei alle vorhandenen Bereitstellungen weiterhin funktionieren. Sie sollten allerdings die Migration zu den neuen Konfigurationsrichtlinien so bald wie möglich planen.<br />Details finden Sie unter [Sicherheitsrichtlinieneinstellungen für mobile Geräte in Microsoft Intune](../Topic/Mobile-device-security-policy-settings-in-Microsoft-Intune.md).|

### Bedingter Zugriff und Kompatibilitätsrichtlinien

#### Bedingter Zugriff

|Name der Richtlinie|Zweck|
|-----------------------|---------|
|**Exchange Online-Richtlinie**<br /><br />**Lokale Exchange-Richtlinie**|-   Verwalten des Zugriffs auf Microsoft Exchange-E-Mail auf Geräten, die nicht von [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] verwaltet werden oder nicht mit einer von Ihnen erstellten Richtlinie kompatibel sind.<br /><br />Details finden Sie unter [Verwalten des E-Mail-Zugriffs mit Microsoft Intune](../Topic/Manage-email-access-with-Microsoft-Intune.md).|
|**SharePoint Online-Richtlinie**|-   Verwalten des Zugriffs auf SharePoint Online auf Geräten, die nicht von [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] verwaltet werden oder nicht mit einer von Ihnen erstellten Richtlinie kompatibel sind.<br /><br />Details finden Sie unter [Verwalten des Zugriffs auf SharePoint Online mit Microsoft Intune](../Topic/Manage-SharePoint-Online-access-with-Microsoft-Intune.md).|
> [!NOTE]
> Sie stellen Benutzern und Geräten keine bedingten Zugriffsrichtlinien bereit. Stattdessen konfigurieren Sie die benötigte Richtlinie und wenden sie auf alle Gruppen an, für die die Richtlinie gelten soll.

#### Kompatibilitätsrichtlinien

|Name der Richtlinie|Zweck|
|-----------------------|---------|
|**Kompatibilitätsrichtlinien**|-   Definieren des Grads der Kompatibilität für Geräte und Melden nicht kompatibler Geräte. Diese Richtlinien werden mit bedingtem Zugriff verwendet, um Geräte einfacher zu bestimmen, die für Dienste gesperrt werden sollen.<br /><br />Details finden Sie unter [Verwalten von Gerätekonformitätsrichtlinien für Microsoft Intune](../Topic/Manage-device-compliance-policies-for-Microsoft-Intune.md).|

### Computerverwaltung

|Name der Richtlinie|Zweck|
|-----------------------|---------|
|**Microsoft Intune-Agent-Einstellungen**|Konfigurieren des [!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)]-Clients auf Computern samt Einstellungen für u. a.:<br /><br />-   Endpoint Protection<br />-   Softwareupdates<br />-   Zeitplan für die Richtlinienprüfung<br /><br />Dieser Richtlinientyp kann nur für Gruppen von Geräten bereitgestellt werden.<br /><br />Neue und aktualisierte Richtlinien werden von [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)]-Clients entsprechend der Einstellung **Häufigkeit der Suche nach Updates und Anwendungen** heruntergeladen, die standardmäßig einen Wert von 8 Stunden hat. Allerdings können Sie jederzeit eine Aktualisierung der Richtlinie auf Computern erzwingen.<br /><br />Details finden Sie unter [Aktualisieren Ihrer Windows-PCs mit Softwareupdates in Microsoft Intune](../Topic/Keep-Windows-PCs-up-to-date-with-software-updates-in-Microsoft-Intune.md).|
|**Microsoft Intune Center-Einstellungen**|Konfigurieren von Details im [!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)] Center auf verwalteten Computern.<br /><br />Dieser Richtlinientyp kann nur für Gruppen von Geräten bereitgestellt werden.<br /><br />Details finden Sie unter [Allgemeine Aufgaben zur Verwaltung von Windows-PCs mit dem Microsoft Intune-Computerclient](../Topic/Common-Windows-PC-management-tasks-with-the-Microsoft-Intune-computer-client.md).|
|**Einstellungen der Windows Firewall**|Hiermit werden die Windows-Firewall-Einstellungen und Ausnahmen für die allgemeine Netzwerkkommunikation auf Computern einschließlich der folgenden Elemente konfiguriert:<br /><br />-   BranchCache<br />-   Remoteunterstützung<br />-   Gemeinsame Nutzung von Medien<br /><br />Dieser Richtlinientyp kann nur für Gruppen von Geräten bereitgestellt werden.<br /><br />Details finden Sie unter [Schützen von Windows-PCs mit Endpoint Protection für Microsoft Intune](../Topic/Help-secure-Windows-PCs-with-Endpoint-Protection-for-Microsoft-Intune.md).|

## Siehe auch
[Konfigurieren und Verwalten von Geräten mit Microsoft Intune](../Topic/Configure-and-manage-devices-with-Microsoft-Intune.md)
[Verwenden von Richtlinien zum Verwalten von Computern und mobilen Geräten mit Microsoft Intune](../Topic/Use-policies-to-manage-computers-and-mobile-devices-with-Microsoft-Intune.md)

