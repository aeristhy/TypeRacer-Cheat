TypeRacer Cheat Code
===================

## 📖 Hacking

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
