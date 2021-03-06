---
title: Convert CAB to TAR.LZ via C# 
weight: 1010
url: /net/conversion/cab-to-tarlz/ 
description: Source code for CAB to TAR.LZ C# conversion. Use API example code for batch CAB files to TAR.LZ conversion within VB.NET Asp.NET or any .NET based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert CAB to TAR.LZ via C#" h2="Extract entries from CAB archive and immediately put it to TAR.LZ archive" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/zip/aspose_zip-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.ZIP " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/zip/aspose_zip-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-zip" liveDemosLink="https://products.aspose.app/zip/family" docsLink="https://docs.aspose.com/zip/net" installationsDocsLink="https://docs.aspose.com/zip/net" nugetLink="https://www.nuget.org/packages/aspose.zip" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/zip/net" learnAsLink="https://docs.aspose.com/zip/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert CAB to TAR.LZ Using C#" %}}

 In order to convert CAB to TAR.LZ, we’ll use
 [Aspose.ZIP for .NET](https://products.aspose.com/zip/net) 
 API which is a feature-rich, powerful and easy to use archive conversion API for C# platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.zip) 
 package manager, search for
 Aspose.ZIP and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Zip

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert CAB to TAR.LZ via C#" %}}

{{% blocks/products/pf/agp/text %}}

Convertation from one archive format to another consist of following steps:

{{% /blocks/products/pf/agp/text %}}

1.  Extract archive to intermediate storage
1.  Compress extracted data to desired format

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before running the conversion example code, make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, Mono and COM Interop.
-  Development environment like Microsoft Visual Studio.
-  Aspose.ZIP for .NET DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

<h2 class="h2title">
     Sample code to convert from CAB to TAR.LZ 
    </h2>
    <p>
		Code from CAB to various formats. The CAB archive contains several records, and the GZ, LZ, Z, XZ, BZ2 formats compress one source. Therefore, compression into these formats is done by packaging first into a TAR archive, which is typical for Linux.
    </p>
	<div class="codeblock" id="code">
     <h3>
      Convert from CAB to TAR.LZ - C#
     </h3>
     <pre><code class="cs">
using (TarArchive tarArchive = new TarArchive())
{
    using (CabArchive cabArchive = new CabArchive("archive.cab"))
    {
        for (int i = 0; i < cabArchive.Entries.Count; i++)
        {
            var ms = new MemoryStream();
            cabArchive.Entries[i].Extract(ms);
            ms.Seek(0, SeekOrigin.Begin);
            tarArchive.CreateEntry(cabArchive.Entries[i].Name.Replace('\\', '/'), ms);
        }
    }

    tarArchive.SaveLzipped("output.tar.lz");
}
</code></pre>
</div>

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert CAB to TAR.LZ" sectionDescription="Check our live demos for [CAB to TAR.LZ conversion](https://products.aspose.app/zip/conversion/cab-to-tarlz) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your CAB archive and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for TAR.LZ file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 A reliable Aspose.ZIP Library that can compress, extract, encrypt, decrypt, convert and merge archives. Aspose.ZIP for .NET API allows to manipulate various archive types without without going into the underlying complexity of the compress file formats with minimum coding efforts.


    {{% /blocks/products/pf/agp/content %}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert CAB into many other file formats including few listed below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/zip/net/conversion/cab-to-zip" name="CAB TO ZIP" description="Zipped (compressed) Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/zip/net/conversion/cab-to-7zip" name="CAB TO 7ZIP" description="7zip Archive" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/zip/net/conversion/cab-to-tarbz2" name="CAB TO TAR.BZ2" description="Burrows–Wheeler Compressor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/zip/net/conversion/cab-to-cpio" name="CAB TO CPIO" description="Copy In, Copy Out Archive" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/zip/net/conversion/cab-to-targz" name="CAB TO TAR.GZ" description="Streaming Deflate Compressor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/zip/net/conversion/cab-to-tarlz" name="CAB TO TAR.LZ" description="LZMA Multi-Block Compressed Data" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/zip/net/conversion/cab-to-tar" name="CAB TO TAR" description="Tape Archive" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/zip/net/conversion/cab-to-tarxz" name="CAB TO TAR.XZ" description="Container for Compressed Streams" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/zip/net/conversion/cab-to-tarz" name="CAB TO TAR.Z" description="LZW Compressor" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}