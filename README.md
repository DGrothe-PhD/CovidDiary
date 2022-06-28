# LocalCovidDiary
Browser-based local page for fast-typing entries of where you have been, which collects entries in the session window. The entries can be exported as CSV for further usage in Excel, for example.
Only javascript and CSS code is included, there is not any external link so that it can be used e. g. in flight mode. 

## Usage
### Desktop version
 * Save the `LocalCovidDiaryDE.html` and the icons in some folder on your computer, for example. Then open it in your browser.
 * Favourite places can be added by the user by adding the place names as HTML `<span>...</span>` tags, to which javascript automatically adds an on-click function. When the user clicks on such a `<span>` item, the text in it is added to the appropriate form field. With `Save entry`/`Eintrag hinzufügen`, the entry is added to the list of entries in the text area at the bottom of the page. By clicking on `copy to clipboard`/`Kopieren` button, the content of the text area is copied to the clipboard of the device, then can be pasted into a text editor or e-mail.
 * If there are some regular scheduled trains you take very often, or similar times every day, you can add some customized time-setting `<span>...</span>` tags as well. Time spans are checked and inappropriate time formats are highlighted.

The page on github only includes general public place names such as <em>Marktplatz</em> and <em>Einkaufszentrum</em> and some groceries known in Germany are added on github as examples. The users can add their own list of places and nicknames, by adding some items like `XYZ snack bar`.



## Browser support
This works on
 * Recent Desktop Firefox versions such as Firefox 78.
  * If you have NoScript, just add "file:" to the allowed list. That's all!

## Excel template spreadsheets
Template Excel spreadsheets are also available. You can copy new entries from the HTML diary and directly paste them into an empty cell below prior entries in column A. Then save your changes, that's all!
The following spreadsheet files are in the repository:
 * in German `CTTagebuchLeer.xlsx`
 * in English `CTDiaryEmpty.xlsx`
