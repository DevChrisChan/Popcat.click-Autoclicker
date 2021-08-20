<h1 align="center">
  <img src="https://raw.githubusercontent.com/DevChrisChan/Popcat.click-Autoclicker/main/assets/popcat-logo.GIF" width="224px"/><br>
  https://popcat.click Autoclicker
</h1>

<p align="center">Want to get your country to 🥇 <b>number 1</b> at popcat leaderboard? Get the scripts for your device and help your country!</p>

## Desktop
If this snippet does not work, please clear your browser cookies.
```js
var event = new KeyboardEvent('keydown', {
	key: 'h',
	ctrlKey: true
});

setInterval(function(){
	for (i = 0; i < 100; i++) {
		document.dispatchEvent(event);
	}
}, 0);
```
