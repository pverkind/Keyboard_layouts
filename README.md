# Keyboard_layouts

Keyboard layouts for transcribing Arabic (and other languages) on Windows PCs.

* translitQW2014: for QWERTY keyboards (most of the world)
* Translit_NL1: for AZERTY keyboards (Belgium, France, ...)
* Simon: for QWERTZ keyboards (Germany)

See the PDF / docx document in the relevant zip folder for the keyboard combinations.

The keyboard layouts were created using MSKLC ([Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134)).

## Installation instructions: 

Download the zip file, unpack it and run the .msi or .exe file in it. 
On Windows 10/11, you may have to activate the .NET 3.5 framework to make the installation possible 
(see [here](https://learn.microsoft.com/en-us/dotnet/framework/install/dotnet-35-windows#enable-the-net-framework-35-in-control-panel)). 

For troubleshooting, see [this discussion](https://answers.microsoft.com/en-us/windows/forum/windows_10-hardware-winpc/custom-keyboard-layout-with-windows-10/b71c7905-1e30-4b0c-861b-253efd2b5a9e). 

To uninstall, go to Start, search for "Add or remove programs"; in the Settings dialog that appears, search for the name of the keyboard layout and click its uninstall button. 

## Design principles: 

-	Includes all signs needed to transliterate Arabic, Persian and Turkish, and to write most European languages
-	Designed for use with UNICODE fonts (e.g. Gentium)
-	As few key combinations as possible
-	Keep the standard keyboard intact, as much as possible 

The basic functioning of the keyboard layout  is very simple:

-	Macron (¯), haček (ˇ) or breve (˘)  under/ above the letter: 	ALT GR + letter 
-	Dot under/above the letter: 					ALT GR + . + letter
-	Çedille (¸) under the letter: 					ALT GR + , + letter

ALT GR is the key to the right of the space bar on your keyboard (sometimes, it’s simply labeled ALT).  

### Vowels:

| diacritic | key combo | result example |
| ------ | ----- | - |
| Umlaut | ″ + a | ä |
| Tilde | ~ + a | ã |
| Macron | ALT GR + a | ā |
| Breve | ALT GR + * + a | ă |
| Acutus | ´ + a | á |
| Gravis | ‘ + a | à |
| Circonflexe | ^ + a | â |

Special vowel diacritics: 

| key combo | result example |
| --------------- | - |
| ALT GR + 0 + a	| å |
| ALT GR + 0 + A	| Å |
| ALT GR + . + i	| ı |
| ALT GR + . + I	| İ |

### Consonants:

|   |	ˇ  /  ˉ  /  ˍ  /  ̮   |   |	̣	 |   | ¸ |   | various |   |
| - | -------------------- | - | - | - | - | - | ------- | - |
| C | ALT GR + c | č |  |  | ALT GR + , + c	 | ç |  |  |
| C | ALT GR + C | Č |  |  | ALT GR + , + C | Ç |  |  |
| D | ALT GR + d | ḏ | ALT GR + . + d | ḍ |  |  |  |  |
|	D | ALT GR + D | Ḏ | ALT GR + . + D | Ḍ |  |  |  |  |
|	G | ALT GR + g | ǧ | ALT GR + . + g | ġ |  |  | ALT GR + * + g | ğ | 
| G | ALT GR + G | Ǧ | ALT GR + . + G | Ġ |  |  | ALT GR + * + G | Ğ | 
| H | ALT GR + h | ḫ | ALT GR + . + h | ḥ |  |  |  |  | 
| H | ALT GR + H | Ḫ | ALT GR + . + H | Ḥ |  |  |  |  | 
| K |  |  | ALT GR + . + k | ḳ |  |  |  |  | 
| K |  |  | ALT GR + . + K | Ḳ |  |  |  |  |
| S | ALT GR + s | š | ALT GR + . + s | ṣ | ALT GR + , + s | ş | ALT GR + / + s | ś | 
| S | ALT GR + S | Š | ALT GR + . + S | Ṣ | ALT GR + , + S | Ş | ALT GR + / + S | Ś | 
| T | ALT GR + t | ṯ | ALT GR + . + t | ṭ |  |  |  |  |
| T | ALT GR + T | Ṯ | ALT GR + . + T | Ṭ |  |  |  |  |
| Z | ALT GR + z | ž | ALT GR + . + z | ẓ |  |  |  |  |
| Z | ALT GR + Z | Ž | ALT GR + . + Z | Ẓ |  |  |  |  |

### Special signs:

| character | key combo | result example |
| ------ | ----- | - |
|ʿain | ʿ | ALT GR + ´ (apostroph) |
| Hamza | ʾ | ALT GR + SHIFT + ´ |
| Euro | € | ALT GR + 5 |
| Ringel-S | ß | ALT GR + B |
| Degree | ° | ALT GR + 0 |
| Inverted question mark | ¿ | ALT GR + / |
| Inverted exclamation mark | ¡ | ALT GR + 1 |
