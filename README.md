#将Word 文档中的链接的图像转换为嵌入的图片；
#convert all linked images to embedded in Word document

#注意！！！！！使用前请务必先备份文件，以免发生意外，产生损失。

#新增"将链接图片转换为嵌入式.docm"文件，使用word打开自动运行宏,可以选择只单处理一个doc/docx文件或者批量处理一个文件下所有doc/docx文件，处理后全保存为docx文件。

＃以下为原方法

VBA代码保存在txt文件中

修改自：https://www.extendoffice.com/documents/word/5423-word-convert-linked-image-to-embedded.html

使用方法：

    打开 Word。
    按 Alt + F11 打开 VBA 编辑器。
    在 VBA 编辑器中，选择 Insert > Module 插入一个新模块。
    将上述代码粘贴到新模块中。
    关闭 VBA 编辑器，回到 Word。
    按 Alt + F8 打开宏对话框。
    选择 ConvertAllLinkedImagesToEmbedded 宏，然后点击“运行”。
    在弹出的对话框中选择要处理的文件夹。

该脚本会遍历选择的文件夹及其所有子文件夹中的所有 .doc 文件，将文档中的所有链接图片转换为嵌入图片，并将处理后的文档保存为 .docx 文件到原 .doc 文件的位置。原 .doc 文件不会被修改。
