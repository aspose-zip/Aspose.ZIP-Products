---
title: Lock ZIP archive via C#
weight: 730
url: /net/lock/ 
description: C# source code for protecting ZIP archives with password. Add single or multiple files and folders to locked ZIP archives programmatically.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Lock ZIP Archive using C#" h2="Protect ZIP archives with password programmatically within any .NET based application." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/zip/aspose_zip-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.ZIP " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/zip/aspose_zip-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-zip" liveDemosLink="https://products.aspose.app/zip/family" docsLink="https://docs.aspose.com/zip/net" installationsDocsLink="https://docs.aspose.com/zip/net" nugetLink="https://www.nuget.org/packages/aspose.zip" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/zip/net" learnAsLink="https://docs.aspose.com/zip/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Lock Zip Archive Using C#" %}}

 For protecting a zip archive, we’ll use
 [Aspose.ZIP for .NET](https://products.aspose.com/zip/net) 
 API which is a feature-rich, powerful and easy to use API. It allows to compress & decompress ZIP, TAR, GZIP, BZ2 file formats on .NET platform without installing any software like WinRAR or 7ZIP. Moreover, developers can convert archive to another format. To add the reference, Open
 [NuGet](https://www.nuget.org/packages/aspose.zip) 
 package manager, search for
 Aspose.ZIP and install. You may also use the following command from the Package Manager Console  ```Install-Package Aspose.ZIP``` .

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Protect Zip Archive in C#" %}}

{{% blocks/products/pf/agp/text %}}

 Protecting archive using password with
 [Aspose.ZIP for .NET](https://products.aspose.com/zip/net) 
 APIs can be done with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

+  Create FileStream object with the output ZIP archive file path as parameter with mod FileMode.Create.
+  Open and read the source file into a FileStream object with mod FileMode.Open and FileAccess.Read.
+  Create Archive class object with ArchiveEntrySettings object as parameter.
+  Use TraditionalEncryptionSettings as parameters to ArchiveEntrySettings.
+  Use Archive.Save(FileStream) method for creating the archive.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Password Protection Requirements" %}}

{{% blocks/products/pf/agp/text %}}

Before executing the code below, please make sure that you have the following prerequisites on your system.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core
-  Development environment like Microsoft Visual Studio
-  Aspose.ZIP for .NET DLL referenced in your project
-  Add namespace in relevant class file

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lock ZIP Archive - C# code example" offSpacer="" %}}

{{< gist "aspose-com-gists" "bfbfe7c21731f4d9465152c6f67da635" "encrypt-via-traditional-encryption.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    <!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Protected ZIP Archiving Operations" %}}

Aspose.Zip also provides some other ways of locking ZIP archives with AES Encryption AES128, AES192 and AES 256. Even developers can encrypt multiple files with mixed encryption techniques.

    {{% /blocks/products/pf/agp/content %}}    

<!-- aboutfile Ends -->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}