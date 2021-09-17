---
title: Create a Simple or Protected ZIP archive via C#
weight: 730
url: /net/zip-file/create/ 
description: C# source code for creating ZIP archives. Add single or multiple files and folders to ZIP archives programmatically.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Create ZIP Archive using C#" h2="Add files or folders to ZIP archives programmatically within any .NET based application." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/zip/aspose_zip-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.ZIP" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.ZIP " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/zip/aspose_zip-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-zip" liveDemosLink="https://products.aspose.app/zip/family" docsLink="https://docs.aspose.com/zip/net" installationsDocsLink="https://docs.aspose.com/zip/net" nugetLink="https://www.nuget.org/packages/aspose.zip" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/zip/net" learnAsLink="https://docs.aspose.com/zip/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Create Zip Archive Using C#" %}}

 For creating a zip archive, we’ll use
 [Aspose.ZIP for .NET](https://products.aspose.com/zip/net) 
 API which is a feature-rich, powerful and easy to use. API allows to compress & decompress ZIP, TAR, GZIP, BZ2 file formats on .NET platform without any installing any software like WinRAR or 7ZIP. Moreover, developers can convert archive to another format. To add the reference, Open
 [NuGet](https://www.nuget.org/packages/aspose.zip) 
 package manager, search for
 **Aspose.ZIP** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.ZIP

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps for 3DS Files Compression in C#" %}}

{{% blocks/products/pf/agp/text %}}

 Creating simple archive with
 [Aspose.ZIP for .NET](https://products.aspose.com/zip/net) 
 APIs can be done with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

+  Create FileStream object with the output ZIP archive file path as parameter.
+  Open and read the source file into a FileStream object with mod FileMode.Open and FileAccess.Read.
+  Create Archive class object.
+  use Archive.CreateEntry(string, FileStream) method to add the file into the archive.
+  Use Archive.Save(FileStream) method for creating the archive.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

Before executing the code below, please make sure that you have the following prerequisites on your system.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core
-  Development environment like Microsoft Visual Studio
-  Aspose.ZIP for .NET DLL referenced in your project
-  Add namespace in relevant class file

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Create ZIP Archive - C# code example" offSpacer="" %}}

```cs
using (FileStream createdZip = File.Open(dataDir + "Compress_File_out.zip", FileMode.Create)){
    using (FileStream src1 = File.Open(dataDir + "test.txt", FileMode.Open, FileAccess.Read)){
        using (var arch = new Archive(new ArchiveEntrySettings())){

            arch.CreateEntry("test.txt", src1);            
            arch.Save(createdZip);
        }
    }
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    <!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="ZIP Archiving Operations" %}}

Aspose.Zip also provides some easy ways of compressing files or folders and creating ZIP archives programmatically using C#. Applications can perform tasks such as

- Store multiple files to a ZIP archive
- Store Files to Archives without compression as well
- Add folders
- Create a password protected ZIP archive using ZipCrypto
- Encrypt ZIP archive with AES encryption
- Set parallel compression mode or use LZMA, BZip2 or PPMd Compression within ZIP Archive


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online Archiving Live Demos" sectionDescription="Compress documents right now by visiting our [Live Demos website](https://products.aspose.app/zip/zip-file). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="  You will get compressed archives instantly." >}}


    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}