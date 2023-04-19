⁸# funny-text-go-brrrrr
Bookmarklet
**************************************
here is the bookmarklet, just copy and paste it in your bookmark bar.

javascript:(function() {
    var elements = document.getElementsByTagName('*');
    for (var i = 0; i < elements.length; i++) {
        elements[i].style.fontSize = Math.floor(Math.random() * 50) + 10 + 'px';
    }
})();
