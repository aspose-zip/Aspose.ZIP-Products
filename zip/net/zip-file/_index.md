---
title: C# ZiP File or Multiple Files into Archive
url: /net/zip-file/
description: C# source code that compresses the contents of a file, multiple files or folder into a zip archive programmatically.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Creating ZIP Archive Via C#" h2="Add files or folders to ZIP archives programmatically within any .NET based application." >}}

{{% blocks/products/pf/feature-page-summary %}}

It is a common practice to compress the contents of a file or folder into a ZIP archive for utilizing the space, keeping backup, carrying data and saving data in more organized and managed way. Moreover, later on extracts that content to a new folder or drive. So for **How to Compress and Extract Files**, C# ZIP API has made it simple. C# Programmerts can easily integrate API and write code for compression of images, PDF files, Word documents, Excel Spreadsheets even whole folders. API supports ZipCrypto for generating password protected archives as well as using AES encryption to encrypt archive. Even developers can set parallel compression mode or use BZip2, LZMA or PPMd Compression within archive. Below are few sample code snippets for **creating C# based zip archives**.  

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="C# Create ZIP Image Files Archive" %}}

Creating archives having images including BMP, JPG, GIF, TIFF and more is simple using the API. Process of adding an image to archive is, Create a [FileStream object](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream?view=netframework-4.8) for the output Images ZIP archive. Open the source image into FileStream object. Create API's [Archives class](https://apireference.aspose.com/zip/net/aspose.zip/archive) object. Add the image using [CreateEntry method](https://apireference.aspose.com/zip/net/aspose.zip.archive/createentry/methods/1) into the archive.
Create the archive containing images using [Save method](https://apireference.aspose.com/zip/net/aspose.zip/archive/methods/save).

{{% blocks/products/pf/feature-page-code h3="C# Code for Creating ZIP Archive Containing Image Files" %}}

{{< gist "aspose-com-gists" "0e82250e6c3615557aaa48b2fee2486d" "create-zip-file-containing-images.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C# ZIP PDF Files" %}}


For creating ZIP archive of PDF documents, process is same as of images. Create Archive object, using its object, call the CreateEntry method having PDF file as parameter and finally invoke Save function for zip creation. API also provides some easy ways of compressing PDF files such as adding multiple files to a archive, storing without compression, adding folders and much more.

{{% blocks/products/pf/feature-page-code h3="C# Code for Creating ZIP Archive of PDF Files" %}}


{{< gist "aspose-com-gists" "0e82250e6c3615557aaa48b2fee2486d" "pdf-files-zip-archive-creation.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ZIP Multiple Files With Password" %}}

API supports archiving multiple files and folders with different encryption such as Traditional Encryption, AES128, AES192 and AES256 encryption. Process is same as of images and PDF archiving other than related encryption object.

{{% blocks/products/pf/feature-page-code h3="C# Code for Archiving Multiple Files with Encryption" %}}

{{< gist "aspose-com-gists" "0e82250e6c3615557aaa48b2fee2486d" "create-zip-multiple-files-with-password.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Zip Archive">}}