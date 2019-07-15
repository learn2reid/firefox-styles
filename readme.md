# Firefox Developer Settings

`userChrome.css` & `userContent.css` settings

## Installation

[How to Create userChrome.css](https://www.userchrome.org/how-create-userchrome-css.html)

1. Open your currently active profile folder
2. Create a new folder named chrome
3. Create a desktop shortcut (alias) to the chrome folder for easier future access
4. Make sure your OS is set to show you file extensions like .txt and .css
5. Create a new text file inside the chrome folder named userChrome.css
6. **Firefox 69 (Beta/Developer):** Change a preference in Firefox so it looks for your files at startup

## How to enable in 69+

[Guide](https://www.ghacks.net/2019/05/24/firefox-69-userchrome-css-and-usercontent-css-disabled-by-default/)

1. Load about:config in the Firefox address bar.
2. Confirm that you will be careful.
3. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` using the search at the top.
4. Toggle the preference. True means Firefox supports the CSS files, False that it ignores them.

## Notes

* Firefox 68: Firefox checks if userChrome.css or userContent.css exist. If yes, preference will be set to True to allow the loading of these files on browser start. If no, preference remains set to False (don't look).
* Firefox 69: new installations will not support userChrome.css and userContent.css by default unless preference is set by the user.

## Links

* https://www.userchrome.org/
* https://github.com/Aris-t2/CustomCSSforFx
* [Hiding Firefox Tab Bar  - 2/2019](https://0x63.me/hiding-firefox-tab-bar/)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

LOLO