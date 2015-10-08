# blurTrelloTitles
A very little script to blur the content of [Trello](http://trello.com/) cards for taking screenshots and showing what your board looks like.

![Blurred board sample](blurry_board.png)

#### Bookmarklet

Just add the bookmarklet below to your bookmarks bar.

```javascript
javascript:if($('.list-card-title').hasClass('blurTitle')){$('.list-card-title').css({"color":"black","text-shadow":"none"}).removeClass('blurTitle');}else{$('.list-card-title').css({"color":"transparent","text-shadow":"0 0 10px black"}).addClass('blurTitle');};void 0;
```
