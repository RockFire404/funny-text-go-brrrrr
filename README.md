funny-text-go-brrrrrr
Bookmarklet
**************************************
here is the bookmarklet, just copy and paste it in your bookmark bar.

javascript:(function() {
    var elements = document.getElementsByTagName('*');
    for (var i = 0; i < elements.length; i++) {
        elements[i].style.fontSize = Math.floor(Math.random() * 50) + 10 + 'px';
    }
})();
*******************
Here is a separate version I've more compact, it also changes the color of text

javascript:(function(){var s=document.getElementsByTagName('*');for(var i=0;i<s.length;i++){s[i].style.fontSize=Math.floor(Math.random()*60)+'px';s[i].style.fontFamily=['Arial','Times New Roman','Comic Sans MS','Courier New','Verdana','Impact','Georgia','Trebuchet MS','Lucida Console','Lucida Sans Unicode','Book Antiqua'][Math.floor(Math.random()*11)];}})();

*************
!test!


javascript:(function()%7B%3Chtml%3E%3Chead%3E%3Cstyle%3Ebody%20%7Bfont-family%3A%20%22Arial%22%2C%20sans-serif%3Bcolor%3A%20%23000%3Btext-align%3A%20center%3B%7D%3C%2Fstyle%3E%3C%2Fhead%3E%3Cscript%3Evar%20fontFamily%20%3D%20%5B%22Arial%22%2C%20%22Georgia%22%2C%20%22Times%20New%20Roman%22%5D%3Bvar%20color%20%3D%20%5B%22blue%22%2C%20%22red%22%2C%20%22green%22%5D%3Bvar%20randomIndex%20%3D%20Math.floor(Math.random()%20*%20fontFamily.length)%3Bvar%20randomIndex2%20%3D%20Math.floor(Math.random()%20*%20color.length)%3Bdocument.body.style.fontFamily%20%3D%20fontFamily%5BrandomIndex%5D%3Bdocument.body.style.color%20%3D%20color%5BrandomIndex2%5D%3B%3C%2Fscript%3E%3C%2Fhtml%3E%7D)()
