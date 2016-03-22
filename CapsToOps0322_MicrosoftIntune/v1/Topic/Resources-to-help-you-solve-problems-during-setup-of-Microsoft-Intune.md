---
title: Ressourcen zum L&#246;sen von Problemen beim Einrichten von Microsoft Intune
ms.custom: na
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 6865f1fb-c2c1-47af-83f5-5704e7210a49
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
# Ressourcen zum L&#246;sen von Problemen beim Einrichten von Microsoft Intune
Da es sich bei [!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)] um einen Clouddienst handelt, ist nur ein geringer Bedarf an Reparaturen und Fehlerumgehungen zu erwarten. Wenn beim Zugriff auf den Dienst Probleme auftreten, können Sie mithilfe der folgenden Abschnitte die nächsten Schritte bestimmen.

## <a name="BKMK_ResolveSetupProblems"></a>Tipps zum Beheben von Problemen beim Einrichten und Konfigurieren von Microsoft Intune
Von [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] werden keine Setup- oder Betriebsprotokolle erstellt, die zur Problembehebung verwendet werden könnten.

Zur Verwaltung stellen Sie die Verbindung mit dem Clouddienst mithilfe eines Webbrowsers her. Probleme beim Zugriff auf den Dienst haben in der Regel eine der folgenden Ursachen:

|Problem|Details|
|-----------|-----------|
|Unzureichende Berechtigungen für das [!INCLUDE[wit_icp_1](../Token/wit_icp_1_md.md)]|Wenn Sie das [!INCLUDE[wit_icp_1](../Token/wit_icp_1_md.md)] verwenden, um mehr als nur Ihr eigenes Benutzerprofil zu verwalten, ist für Ihr Konto Folgendes erforderlich:<br /><br />-   Eine Lizenz zum Verwenden von [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)]<br />-   Anmeldestatus **Zugelassen** für die Anmeldung<br />-   Es muss sich um einen [!INCLUDE[wit_icp_1](../Token/wit_icp_1_md.md)]-Mandantenadministrator handeln<br /><br />Informationen finden Sie unter [Intune-Administratorkonten und spezielle Berechtigungen](../Topic/What-to-know-before-setting-up-Microsoft-Intune.md#BKMK_AdminAccounts).|
|Netzwerkzugriff einschließlich:<br /><br />-   Domänen, die von [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] verwendet werden<br />-   Datenverkehr im Netzwerk<br />-   Webbrowserunterstützung|Zum Herstellen einer Verbindung mit [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] ist Folgendes erforderlich:<br /><br />-   Es muss ein unterstützter Webbrowser verwendet werden<br />-   Es muss durch Firewalls und Proxyserver auf die verschiedenen Domänen zugegriffen werden können, die vom [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)]-Dienst verwendet werden<br /><br />Informationen zu Anforderungen und erforderlichen Konfigurationen für [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] finden Sie unter:<br /><br />-   [Infrastructure requirements](../Topic/Network-infrastructure-requirements-for-Microsoft-Intune.md#BKMK_InfrastructureReqs)<br />-   [Web browsers supported by Microsoft Intune](../Topic/Network-infrastructure-requirements-for-Microsoft-Intune.md#BKMK_SupportedBrowsers)|
|[!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)]-Dienstverfügbarkeit|Um Details online anzuzeigen oder RSS-Feeds zum Zustand des [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)]-Diensts zu abonnieren, navigieren Sie zu:<br /><br />-   [Microsoft Intune-Dienst](http://status.manage.microsoft.com/)|

## Siehe auch
[Einführung in Microsoft Intune](../Topic/Introduction-to-Microsoft-Intune.md)

