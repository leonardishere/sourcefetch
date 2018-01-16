# sourcefetch
An Atom plugin that searches stackoverflow for answers and pastes their code in yours.

## Installation

Clone this into your atom workspace. On windows, this is likely C:\Users\\<username\>\\.atom\packages  
Open a terminal window in the sourcefetch folder.
Run the following commands:
```
npm install --save request@2.73.0  
npm install --save cheerio@0.20.0  
npm install --save google@2.0.0  
apm install  
```
## How to use

The file you're in should have its language set to the correct language.
Type out what you would like to search for. For example, "how to sort an array"
Select the text to search.
Activate sourcefetch using ctrl-alt-o, the menu bar, or the context menu.
The results should replace the selected text.
