---
title: "Mastering Data Retrieval From Office Docs: Images, Text, & File Extraction Techniques"
date: 2024-08-27 12:31:43
updated: 2024-08-29 10:36:15
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/5ab9533fc8b349be19f63e7cbad029dfd19e210f57907497c693bf48b201e0ff.jpg
---

## Mastering Data Retrieval From Office Docs: Images, Text, & File Extraction Techniques

Say someone sent you a Word document with a lot of images, and you want you to save those images on your hard drive. You can extract images from a Microsoft Office document with a simple trick.

 If you have a Word (.docx), Excel (.xlsx), or PowerPoint (.pptx) file with images or other files embedded, you can extract them (as well as the document's text), without having to save each one separately. And best of all, you don't need any extra software. The Office XML based file formats--docx, xlsx, and pptx--are actually compressed archives that you can open like any normal .zip file with Windows. From there, you can extract images, text, and other embedded files. You can use Windows' built-in .zip support, or [an app like 7-Zip](https://remote-screen-capture.techidaily.com/new-visual-voyage-amds-radeon-reborn-for-2024/) if you prefer.

 If you need to extract files from an older office document--like a .doc, .xls, or .ppt file--you can do so with a small piece of free software. We'll detail that process at the end of this guide.

##  How to Extract the Contents of a Newer Office File (.docx, .xlsx, or .pptx)

 To access the inner contents of an XML based Office document, open File Explorer (or Windows Explorer in Windows 7), navigate to the file from which you want to extract the content, and select the file.

![01_pressing_f2_to_rename_file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/01_pressing_f2_to_rename_file.png) 

 Press “F2” to rename the file and change the extension (.docx, .xlsx, or .pptx) to “.zip”. Leave the main part of the filename alone. Press “Enter” when you’re done.

![02_changing_extension_to_zip](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/02_changing_extension_to_zip.png) 

 The following dialog box displays warning you about changing the file name extension. Click “Yes”.

![02a_rename_confirmation](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/02a_rename_confirmation.png) 

 Windows automatically recognizes the file as a zipped file. To extract the contents of the file, right-click on the file and select “Extract All” from the popup menu.

![03_selecting_extract_all](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/03_selecting_extract_all.png) 

 On the “Select a Destination and Extract Files” dialog box, the path where the content of the .zip file will be extracted displays in the “Files will be extracted to this folder” edit box. By default, a folder with the same name as the name of the file (without the file extension) is created in the same folder as the .zip file. To extract the files to a different folder, click “Browse”.

![04_clicking_browse](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/04_clicking_browse.png) 

 Navigate to where you want the content of the .zip file extracted, clicking “New folder” to create a new folder, if necessary. Click “Select Folder”.

![05_creating_new_folder_and_selecting_it](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/05_creating_new_folder_and_selecting_it.png) 

 To open a File Explorer (or Windows Explorer) window with the folder containing the extracted files showing once they are extracted, select the “Show extracted files when complete” check box so there is a check mark in the box. Click “Extract”.

![06_clicking_extract](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/06_clicking_extract.png) 

###  How to Access the Extracted Images

 Included in the extracted contents is a folder named “word”, if your original file is a Word document (or “xl” for an Excel document or “ppt” for a PowerPoint document). Double-click on the “word” folder to open it.

![07_opening_word_folder](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/07_opening_word_folder.png) 

 Double-click the “media” folder.

![08_opening_media_folder](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/08_opening_media_folder.png) 

 All the images from the original file are in the “media” folder. The extracted files are the original images used by the document. Inside the document, there may be resizing or other properties set, but the extracted files are the raw images without these properties applied.

![09_images_from_file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/09_images_from_file.png) 

###  How to Access the Extracted Text

 If you don’t have Office installed on your PC, and you need to extract text out of a Word (or Excel or PowerPoint) file, you can access the extracted text in the “document.xml” file in the “word” folder.

![10_document_xml_file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/10_document_xml_file.png) 

 You can open this file in a text editor, such as Notepad or WordPad, but it’s easier to read in a special XML editor, such as the free program, [XML Notepad](https://xmlnotepad.codeplex.com/). All the text from the file is available in chunks of plain text regardless of the style and/or formatting applied in the document itself. Of course, if you're going to download free software to view this text, you might as well download [LibreOffice](https://www.libreoffice.org/download/libreoffice-fresh/), which can read Microsoft Office documents.

![11_document_xml_file_open_in_xml_notepad](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/11_document_xml_file_open_in_xml_notepad.png) 

###  How to Extract Embedded OLE Objects or Attached Files

 To access embedded files in a Word document when you don’t have access to Word, first open the Word file in WordPad (which comes built into Windows). You might notice that some of the embedded file icons do not display, but they’re still there. Some of the embedded files might have partial filenames. WordPad does not support all of Word’s features, so some content might be displayed improperly. But you should be able to access the files.

 If we right-click on one of the embedded files in our sample Word file, one of the options is “Open PDF Object”. This opens the PDF file in the default PDF reader program on your PC. From there, you can save the PDF file to your hard drive.

![11a_opening_pdf_file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/11a_opening_pdf_file.png) 

 If WordPad doesn't have an option for opening your file, make note of its file type here. For example, our second file in this document is a .mp3 file.

 Then, go back to your "Files from \[Document\]" folder and double-click the “embeddings” folder inside the “word” folder.

![12_embeddings_folder](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/12_embeddings_folder.png) 

 Unfortunately, the file types are not preserved in the filenames. They all have a “.bin” file extension instead. If you know what types of files are embedded in the file, you can probably deduce which file is which by the size of the file. In our example, we had a PDF file and an MP3 file embedded in our document. Because the MP3 file is most likely larger than the PDF file, we can figure out which file is which by looking at the sizes of the files and then rename them using the correct extensions. Below, we're renaming the MP3 file.

![13_extracted_embedded_files](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/13_extracted_embedded_files-1.png) 

 Note that not all files will necessarily open using this process--for example, our PDF file opened correctly from WordPad, but we couldn't get it to open by renaming its .bin file.

 Once you’ve extracted the content of the zipped file, you can revert the extension of the original file back to .docx, .xlsx, or .pptx. The file will remain intact and can be opened normally in the corresponding program.

##  How to Extract Images from Older Office Documents (.doc, .xls, or .ppt)

 If you need to extract images from an Office 2003 (or earlier) document, there’s a free tool called [Office Image Extraction Wizard](http://www.rlvision.com/officewiz/about.asp) that makes this task easy. This program also allows you to extract images from multiple documents (of the same or different types) at once. Download the program and install it (there's also a portable version available if you'd rather not install it).

 Run the program, and the Welcome screen displays. Click "Next".

![14_welcome_screen](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/14_welcome_screen.png) 

 First, we need to select the file from which you want to extract the images. On the Input & Output screen, click the "Browse" (folder icon) button to the right of the Document edit box.

![15_clicking_browse_for_document](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/15_clicking_browse_for_document.png) 

 Navigate to the folder containing the document you want, select it, and click "Open".

![16_opening_word_file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/16_opening_word_file.png) 

 The folder that contains the selected file automatically becomes the Output folder. To create a subfolder within that folder named the same as the selected file, click the "Create a folder here" check box so there is a check mark in the box. Then, click "Next".

![17_clicking_next](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/17_clicking_next.png) 

 On the Ready to Start screen, click "Start" to begin extracting the images.

![18_ready_to_start](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/18_ready_to_start.png) 

 The following screen displays while the extraction processes.

![19_processing_please_wait](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/19_processing_please_wait.png) 

 On the Finished screen, click the "Click here to open destination folder" to view the resulting image files.

![20_opening_destination_folder](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/20_opening_destination_folder.png) 

 Because we chose to create a subfolder, we get a folder containing the image files extracted from the file.

![21_opening_subfolder](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/21_opening_subfolder.png) 

 You will see all the images as numbered files.

![22_images_from_older_word_file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/22_images_from_older_word_file.png) 

 You can also extract images from multiple files at once. To do this, on the Input & Output screen, click the "Batch Mode" check box so there is a check mark in the box.

![23_clicking_batch_mode](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/23_clicking_batch_mode.png) 

 The Batch Input & Output screen displays. Click "Add Files".

![24_clicking_add_files](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/24_clicking_add_files.png) 

 On the Open dialog box, navigate to the folder containing any of the files from which you want to extract images, select the files using the "Shift" or "Ctrl" key to select multiple files, and click "Open".

 You can add files from another folder by clicking "Add Files" again, navigating to the folder on the Open dialog box, selecting the desired files, and clicking "Open".

![25_opening_files](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/25_opening_files.png) 

 Once you've added all the files from which you want to extract images, you can choose to create a separate folder for each document within the same folder as each document into which the image files will be saved by clicking the "Create a folder for each document" check box so there is a check mark in the box.

![26_clicking_next_on_batch_mode](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/26_clicking_next_on_batch_mode-1.png) 

 You can also specify the Output folder to be the "Same as each file's input folder" or enter or select a custom folder using the edit box and "Browse" button below that option. Click "Next" once you have selected the options you want.

![26a_specifying_output_folder](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/26a_specifying_output_folder-1.png) 

 Click "Start" on the Ready to Start screen.

![27_ready_to_start_for_batch_mode](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/27_ready_to_start_for_batch_mode.png) 

 The following screen displays showing the extraction progress.

![28_processing_screen](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/28_processing_screen.png) 

 The number of images extracted displays on the Finished screen. Click "Close" to close the Office Image Extraction Wizard.

![29_closing_wizard](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/29_closing_wizard.png) 

 If you chose to create a separate folder for each document, you will see folders with the same names as the files containing the images, whichever output folder(s) you specified.

![30_folders_containing_images](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/30_folders_containing_images.png) 

 Again, we get all the images as numbered files for each document.

![31_images_from_one_file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/31_images_from_one_file.png) 

 Now you can rename the images, move them, and use them in your own documents. Just make sure you have the rights to use them legally.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
