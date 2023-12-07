# LibreOffice Decimal Step
This is just an extremely basic macro for LibreOffice that multiplies or divides the selected cells by 10. I ran into the problem of having a bunch of grades inputted out of 100 in a spreadsheet and needed to divide them all by 100 to convert them to a decimal out of 1. I couldn't find any built-in function for this, so I made a macro.

__Running DecStpInc on a selection does this:__

| Grades | (DecStpInc) | Grades | (DecStpInc) | Grades |
| ------ | ----------- | ------ | ----------- | ------ |
| 90     |             | 9.0    |             | .9     |
| 100    |             | 10     |             | 1      |
| 100    |             | 10     |             | 1      |
| 66     |             | 6.6    |             | .66    |
| 83.5   |             | 8.35   |             | .835   |
| 100    |             | 10     |             | 1      |
## Usage
If you want to bind the macro to a key, you need to bind it to two: one for multiplying times 10 (DecStpInc), and one for dividing (DecStpDec). 

Simply select the cells to change and run the macro.
## Installation
This is a .zip of the BASIC Library. You must import it. Instructions: [https://books.libreoffice.org/en/GS70/GS7013-GettingStartedWithMacros.html#toc25](https://books.libreoffice.org/en/GS70/GS7013-GettingStartedWithMacros.html#toc25)
