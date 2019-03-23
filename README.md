## Bloc / Thinkful Grading Chrome Extension

Chrome extension for Bloc graders to auto fill with default grading message and students name.

### GIF Demo (for Bloc, works similarly on Thinkful)

![GIF](http://nikib.ro/wn/screenshots/chrome-extension.gif)

- Bloc: Only works when `#submission` is at the end of URL (or textarea is visible on the page): 
[https://www.bloc.io/users/nick-noel/checkpoints/2017#submission](https://www.bloc.io/users/nick-noel/checkpoints/2017#submission) (ie you are clicking on a link from the grading spreadsheet)
- Thinkful: Only works when the url it's from `lark.thinkful.com/grading/`

### Installation instructions

- Download or clone this repo
- In Chrome go to [chrome://extensions/](chrome://extensions/)
- Turn on developer mode
- ![developer mode](http://nikib.ro/wn/screenshots/Extensions_2018-04-09_08-05-18.jpg)
- Click on `load unpacked` and browse to the extension files that you cloned or downloaded
- Thats it!

### Usage
- Go to the options page by clicking on the extension and then on "Options".
- Enter your name and the type of grading you do.
![extension options](https://t.gyazo.com/teams/leovegas/0dbf3354d7e28328794ea6508ed8c2f3.png)
- Go to any submission you're grading and the snippet will be added on page load. It will 
automatically change for bloc/thinkful depending on your type.
- If you grade both Dev and Design, you can easily switch from one to the other and the snippet 
will automatically adapt.
