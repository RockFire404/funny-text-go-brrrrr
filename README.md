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

