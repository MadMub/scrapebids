scrapebids
==========

Single webpage that scrapes quibids.com's recently completed page

* You need to bypass same origin policy ex:
```
chromium-browser --disable-web-security index.html
```
* Make sure recently completed page is in listview
* Script uses:
    * [jQuery](http://jquery.com/) for parsing
    * [PouchDB](http://pouchdb.com/) for storage
    * [DataTables](http://www.datatables.net/) for displaying results