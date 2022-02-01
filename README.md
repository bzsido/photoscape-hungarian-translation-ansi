# Photoscape Hungarian translation ansi

Photoscape offers a way to write your own translation to the program in form of a .txt "language file". Although sadly Photscape seems to only support ANSI character encoding, which can make it difficult to import translations using non-standard latinic characters. If you experience strange characters when trying to import a custom language to Photoscape, please follow the steps below to convert your language .txt file encoding from UTF-8 to ANSI.

* This fix has been tested with the Hungarian translation for Photoscape versions 3.4 - 3.7
* I expect, that it will also work for other languages, that are written with the latinic alphabet and include special characters
* Open the translator's guide on the official PhotoScape website: http://www.photoscape.org/ps/main/help.php?id=translate
* Open the specific language you are interested in
* Copy the text from the browser to notepad++
* Change the Encoding of the translation text from UTF-8 to ANSI by clicking on **Encoding/Convert to ANSI** on the menu bar
* Save the language file in the following format: lang_3_4.txt for photoscape 3.4, lang_3_6.txt for photoscape 3.6 and lang_3_7.txt for photoscape 3.7
* Copy the previously saved language file to the `C:\Program Files (x86)\PhotoScape` folder
* Restart Photoscape
* Shouldn't PhotoScape automatically load the Language file, click on the Language button and choose the "Language File" option
