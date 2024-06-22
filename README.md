### ABOUT ###

This program is designed to generate a 90-card sealed pod for deckbuilding from a 540 card cube CSV file of Magic: The Gathering cards. After a desired pod is generated, the program sorts the cards by color and allows the user to build a deck that can be exported as a .txt or .csv file.
        
Double click on a card name to see an image obtained through the Scryfall API (right- or middle-click will generate an image of the card's first printing).
                       

### INSTRUCTIONS FOR CSV CLEANER ###
CSV Clean is used to convert a .csv file obtained through the internet into a workable .csv file for this program.

1. Download a .csv file of your cube.
2. Click 'CSV Clean' from the menu.
3. The file will be saved as a new .csv file with the same name as your original .csv file, followed by '_cg'. Use this file for 'Open CSV'
                                       

###	CARD GUIDELINES ###
If values are missing and you wish to manually enter card values, please adhere to the following guidelines for csv values to function properly within program.

The general format of card entries is:
* name,mv,color,type,subtype

Accepted color values:
* W [white]
* U [blue]
* B [black]
* R [red]
* G [green]
* C [colorless]
* L [land]
* Multicolor combinations of the above in the following order: BGRUW [examples: BU, GR, BGU, BGUW, etc...]

Leave blank fields if no value is present, e.g. cards with no subtype value or no casting cost, but leave the comma that would normally separate that cell value.

Cards with full values, no end comma needed:
* Liliana of the Veil,1BB,B,Legendary Planeswalker,Liliana
* Stoneforge Mystic,1W,W,Creature,Kor Artificer
      
Cards missing values (note trailing commas for missing subtype values and additional comma for missing mana values):
* Dark Ritual,B,B,Instant,
* Mox Sapphire,0,C,Artifact,
* Ancestral Vision,,U,Sorcery,
* Bazaar of Baghdad,,L,Land,

Please use double-quotes for cards containing a comma or single apostrophe:
* "Sheoldred, the Apocalypse",2BB,B,Legendary Creature,Phyrexian Praetor
* "Sheoldred's Edict",1B,B,Instant,

Please replace any characters with diacritics with an equivalent character without. For example, the card 'Palantír of Orthanc' should be formatted as:
* Palantir of Orthanc,3,C,Legendary Artifact,

### ###

This program is fan-made and I do not own the rights to Magic: The Gathering or Scryfall.

Scrython belongs to Nanda Scott and is used in accordance with the following terms:
                   
MIT License
Copyright (c) 2018 Nanda Scott

"Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

        The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

        THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE."
        
