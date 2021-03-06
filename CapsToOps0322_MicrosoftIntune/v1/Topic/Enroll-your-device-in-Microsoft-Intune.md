---
title: Registrieren Ihres Ger&#228;ts in Microsoft Intune
ms.custom: na
ms.reviewer: na
ms.service: microsoft-intune
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 8373c587-b1ad-4c25-93f9-e0148834d495
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
# Registrieren Ihres Ger&#228;ts in Microsoft Intune
<?xml version="1.0" encoding="utf-8"?>
<caps:SxS xmlns:caps="http://schemas.microsoft.com/build/caps/2013/11">
  <caps:SxSTarget locale="de-DE">
    <developerConceptualDocument xsi:schemaLocation="http://ddue.schemas.microsoft.com/authoring/2003/5 http://dduestorage.blob.core.windows.net/ddueschema/developer.xsd" xmlns="http://ddue.schemas.microsoft.com/authoring/2003/5" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
      <introduction>
        <para>
          <caps:sentence sentenceid="db72f7c059e8ad76aeed0c15ee0eac8c" id="tgt1" class="tgtSentence">Wenn Ihr Unternehmen <token>wit_firstref</token> zum Verwalten von Geräten einsetzt, können Sie zum Schutz von Unternehmensdaten und -ressourcen beitragen, indem Sie Ihr Smartphone oder Tablet in Microsoft Intune registrieren.</caps:sentence>
          <caps:sentence sentenceid="abac7b380a93e32d6be7adf63a70713e" id="tgt2" class="tgtSentence"> Nach der Registrierung können Sie Ihr Mobiltelefon oder Tablet nutzen, um auf das Unternehmensnetzwerk, E-Mail und andere geschäftliche Dateien zuzugreifen sowie um Unternehmens-Apps abzurufen.</caps:sentence>
          <caps:sentence sentenceid="ed5bae15ec87c32cc2a89f0b733b414c" id="tgt3" class="tgtSentence"> Die IT-Abteilung ist anschließend in der Lage, eingeschränkte Aspekte Ihres Mobilgeräts zu verwalten, um für Schutz zu sorgen.</caps:sentence>
          <caps:sentence sentenceid="349ad38156f0fff1fe2f5deb11bcabfd" id="tgt4" class="tgtSentence"> Sie behalten den Zugriff auf persönliche Apps und Daten, und Ihre privaten Dinge bleiben nach wie vor nur für Sie sichtbar.</caps:sentence>
          <caps:sentence sentenceid="180f15cfd9be8d4afd7c4ed12da8087f" id="tgt5" class="tgtSentence"> Weitere Informationen finden Sie unter <externalLink><linkText>Für die IT nach der Geräteregistrierung in Intune einsehbare und nicht einsehbare Elemente</linkText><linkUri>https://technet.microsoft.com/library/jj738616(WIT.1).aspx</linkUri></externalLink>.</caps:sentence>
        </para>
        <para>
          <caps:sentence sentenceid="83f5c2932ca49c0cf70926ff42419945" id="tgt6" class="tgtSentence">Verwenden Sie zum Registrieren den Link, der dem Gerät entspricht, das Sie verwenden:</caps:sentence>
        </para>
        <list class="bullet">
          <listItem>
            <para>
              <caps:sentence sentenceid="7530ec6a030bc66c346a35ae9c931a42" id="tgt7" class="tgtSentence">Windows: <externalLink><linkText>Registrieren Ihres Windows-Geräts in Intune</linkText><linkUri>https://technet.microsoft.com/library/mt427782.aspx</linkUri></externalLink></caps:sentence>
            </para>
          </listItem>
          <listItem>
            <para>
              <caps:sentence sentenceid="10a8b757b0f5bc4ef971b05d498ce617" id="tgt8" class="tgtSentence">Android: <link xlink:href="465763db-b68d-4392-a5a4-732b5b875c2b#BKMK_andr_enroll_devc"> Enroll your device in Intune</link></caps:sentence>
            </para>
          </listItem>
          <listItem>
            <para>
              <caps:sentence sentenceid="2c4b0d9ae2bf4f494ab3f991b631e4e2" id="tgt9" class="tgtSentence">iOS: <externalLink><linkText>Registrieren Ihres iOS-Geräts in Intune</linkText><linkUri>https://technet.microsoft.com/library/mt598622.aspx#BKMK_enroll_ios_device</linkUri></externalLink></caps:sentence>
            </para>
          </listItem>
          <listItem>
            <para>
              <caps:sentence sentenceid="c753d5225f7f4ca99fd3ce7b4d3f03a2" id="tgt10" class="tgtSentence">Mac OS X: <externalLink><linkText>Registrieren Ihres Mac OS X-Geräts in Intune</linkText><linkUri>https://technet.microsoft.com/library/mt598622.aspx#BKMK_ios_enroll_macosx_dev</linkUri></externalLink></caps:sentence>
            </para>
          </listItem>
        </list>
      </introduction>
      <relatedTopics></relatedTopics>
    </developerConceptualDocument>
  </caps:SxSTarget>
  <caps:SxSSource locale="en-US">
    <developerConceptualDocument xsi:schemaLocation="http://ddue.schemas.microsoft.com/authoring/2003/5 http://dduestorage.blob.core.windows.net/ddueschema/developer.xsd" xmlns="http://ddue.schemas.microsoft.com/authoring/2003/5" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
      <introduction>
        <para>
          <caps:sentence id="src1" class="srcSentence">If your company is using <token>wit_firstref</token> to manage devices, you can help keep corporate data and resources protected by enrolling your phone or tablet into Microsoft Intune.</caps:sentence>
          <caps:sentence id="src2" class="srcSentence"> Once you enroll, you can use your mobile phone or tablet to access the company's network, email and other work files and to get company apps.</caps:sentence>
          <caps:sentence id="src3" class="srcSentence"> IT will be able to manage limited aspects of your mobile device to keep us protected.</caps:sentence>
          <caps:sentence id="src4" class="srcSentence"> You'll still have  access to personal apps and data, and  your private stuff is still for your eyes only.</caps:sentence>
          <caps:sentence id="src5" class="srcSentence"> Read More about <externalLink><linkText>What IT can and can't see when you enroll your device in Intune</linkText><linkUri>https://technet.microsoft.com/library/jj738616(WIT.1).aspx</linkUri></externalLink>.</caps:sentence>
        </para>
        <para>
          <caps:sentence id="src6" class="srcSentence">To enroll, use the link that corresponds to the device you are using:</caps:sentence>
        </para>
        <list class="bullet">
          <listItem>
            <para>
              <caps:sentence id="src7" class="srcSentence">Windows: <externalLink><linkText>Enroll your Windows device in Intune</linkText><linkUri>https://technet.microsoft.com/library/mt427782.aspx</linkUri></externalLink></caps:sentence>
            </para>
          </listItem>
          <listItem>
            <para>
              <caps:sentence id="src8" class="srcSentence">Android: <link xlink:href="465763db-b68d-4392-a5a4-732b5b875c2b#BKMK_andr_enroll_devc"> Enroll your device in Intune</link></caps:sentence>
            </para>
          </listItem>
          <listItem>
            <para>
              <caps:sentence id="src9" class="srcSentence">iOS: <externalLink><linkText>Enroll your iOS device in Intune</linkText><linkUri>https://technet.microsoft.com/library/mt598622.aspx#BKMK_enroll_ios_device</linkUri></externalLink></caps:sentence>
            </para>
          </listItem>
          <listItem>
            <para>
              <caps:sentence id="src10" class="srcSentence">Mac OS X: <externalLink><linkText>Enroll your Mac OS X device in Intune</linkText><linkUri>https://technet.microsoft.com/library/mt598622.aspx#BKMK_ios_enroll_macosx_dev</linkUri></externalLink></caps:sentence>
            </para>
          </listItem>
        </list>
      </introduction>
      <relatedTopics></relatedTopics>
    </developerConceptualDocument>
  </caps:SxSSource>
</caps:SxS>