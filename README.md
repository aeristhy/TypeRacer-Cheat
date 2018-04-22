TypeRacer Cheat Code
===================

## 📝 Contents

- [Tutorial](#-tutorial)
- [Hacking](#-hacking)

## 📖 Tutorial
**[Back To Top](#-contents)**

Cloning:

>Click "Clone or download" and click the clipboard icon.
![picture alt](https://cdn.discordapp.com/attachments/419724812592611340/437606358234300416/GitHub-1.png "Screenshot")

>After you've got the clone URL, open any terminal you've got and go to Desktop.
![picture alt](https://cdn.discordapp.com/attachments/419724812592611340/437608387103162390/GitHub-2.png "Screenshot")

>Assuming you still got your terminal open, type git clone and then paste the URL you copied before and hit enter, it should look like the following:
git clone https://github.com/aerisDoesCodes/TypeRacer-Cheat.git
![picture alt](https://cdn.discordapp.com/attachments/419724812592611340/437610296954322955/GitHub-3.png "Screenshot")

## 📖 Hacking
**[Back To Top](#-contents)**
Code:

```javascript
var counter = -1;
var firstWord = document.getElementsByClassName("inputPanel")[0].querySelectorAll("span")[0].innerHTML + document.getElementsByClassName("inputPanel")[0].querySelectorAll("span")[1].innerHTML,
restOfText = document.getElementsByClassName("inputPanel")[0].querySelectorAll("span")[2].innerHTML;
var fullText = firstWord.concat(restOfText);
var inputBox = document.getElementsByClassName('txtInput');
(function getString() {
    setTimeout(function() {
        counter++;
        inputBox[0].value += fullText[counter];
        if(counter != fullText.length) {
            getString();
        }
        //adjust the 100 milliseconds for a faster wpm & be undetected by their new system.
    }, 100);
})()
```

>Copy the code above ^^ then go to [TypeRacer](http://play.typeracer.com)
Enter a Race, on your keyboard press `ctrl + shift + i` to open the console
When the game starts(It says GO!), paste the cheat code you just copied in the console and hit enter
![picture alt](https://cdn.discordapp.com/attachments/419724812592611340/437614460623126549/cheat.png "Screenshot")
