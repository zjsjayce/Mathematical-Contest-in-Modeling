The translation files are in UTF-16 format, to support any special characters characteristic of some language.
If you don't save them as UTF-16, is it possible that you cannot see correctly the text.

…:::::::EXPLANATION OF THE Translate_XX.txt file:::::::…

- NAME OF THE FILE

	The name of the file have to be Translate_[prefix of the language].txt
	The software will use only file with this name

- FIRST LINE

	[NAME OF THE LANGUAGE]<>[PREFIX]

	Name of the language => The text that will appear in the menu of language selection inside the software
	Prefix => This prefix will be used from the software to locate these translated strings

	Example: 	English<>en
			Italiano<>it
			Dutch<>be

- OTHER LINES

	[VARIABLE]<>[FIRST LINE]<>[SECOND LINE (optional)]<>[THIRD LINE (optional)]

	Variable => Do not modify this variable name, the software point to it to find the translation
	First line => The text translated for this variable

	If you find text also in the 2nd and 3rd line, is because that control have more text. Do not use 2nd and 3rd line if they are blank

…:::::::HOW TO CREATE NEW LANGUAGE FILES:::::::…
	
	For to create new language files, you have to copy the Translate_EN.txt file and rename it.
	After that, you have to translate all the text lines inside and re-save always in UTF-16 format to preserve special characters.

	Your translate strings length have to be no longer than the english strings.


Bye
DDAAXX