#### v0.94 (Build 20181201)
* Various improvements

#### v0.92 (Build 20180429)
* NEW: Menu Category > Select - Select a category from the list of categories for the selected theme. The list is sorted by category.Keys handled: Enter, Esc
* NEW: Menu Memo > Select - Select a memo from the list for the selected theme. The list is sorted by memo title. Keys handled: Enter, Esc
* NEW: Menu Search > Recent - Search for an item from the search history list
* NEW: Menu Search > Go to > ID - Go to an item Category or Memo by ID
* NEW: Menu Settings - Editor (dialog which enables to set the font family, size, & tab size) (replaces Menu > Tools > Font size & Tab size), Clipboard History (to set its use), Markup (moved from Menu > Tools)
* NEW: Menu Theme > Select - Select a theme from the list of themes for the current database. The list is sorted by theme. Keys handled: Enter, Esc
* NEW: Menu View > Clipboard - Show the text content of the clipboard (if any)
* NEW: Menu View > Clipboard History - Build a list for text copied from the editor. Item can be selected and copied to the clipboard
* NEW: Markup map file part of the asset folder - is used when Look4How is started first time
* NEW: Markup place holders - (enclosed in hash tags) LINE to show the current line, RB to replace blank, LINERB show current line with blanks replaced
* NEW: Markup place holders - CODE /CODE (enclosed in brackets) converted into HTML tags CODE and /CODE and other examples (see file Markup.map)
* NEW: Tasks - Added field Status; Reworked the layout, export HTML & text format to accomodate the status
* UPD: Menu Memo > Delete - After deleting the memo, scroll to the first entry in the items list
* UPD: Menu Memo > Move - Category list sorted; Menu title changed from Memo Move to Move
* UPD: Menu Search > Find item changed - When items found, the Tools Search Tab is shown
* UPD: Menu Theme > Export > HTML Navigation - Exporting to folder <application folder>\export\theme (the theme name blanks are stripped out)
* UPD: Search history list increased items from 10 to 20
* UPD: All Tools layout redesigned. Form style Utility is used instead Undecorated. Close button replaced by system close icon [X] (top right) of the window
* UPD: Documentation (PDF format)
* FIX: Menu Memo > Rename - Wrong category if no category selected prior rename - ensure memo category is set
* FIX: Menu Theme > Export > HTML Navigation - Look4HowUploader refreshes remote file list after upload; No local file list is fetch is folder is empty
* Various improvements

#### v0.90 (Build 20180413)
* UPD: Decided NOT to look into alternatives for the JavaFX TextArea control = too much effort, external dependencies might cause issues, complexity.
* NEW: Look4HowUploader to FTP upload files created via Theme > Export > HTML Navigation to a remote server. The uploader is a separate B4J application running standalone
* NEW: Theme > Export > Navigation - Dialog to set options Show Files in Browser and Upload Files; Menu shortcut CTRL+F4
* NEW: Menu Items - Added fontawesome icons to most of the menu items
* NEW: Menu Search - Quick find item, Find item, Find item changed, Go to item... (first, next, prev,last)
* NEW: Tab Search - Button to search from the search history list; max 10 items, the items are not stored when closing the application
* NEW: Items List Search - Buttons to navigate through the list of items (first, prev, next, last) see also Menu Search Go to
* NEW: Help > Author Website - pointer to view what else the author is exploring & making
* NEW: Editor > Special Function > Insert File - Insert the content of a text file at caret position
* NEW: View > Always on Top - set the application always on top
* NEW: Settings JavaPath=java, FTPUploader=Look4HowUploader.jar
* DEL: Menu Tools - Moved Quick find item, Find item, Find item changed to menu Search
* DEL: Tools > Stay on Top - renamed to Always on Top and moved to menu View
* UPD: File > Open Dialog title format set to lightgray
* UPD: Tasks export HTML icon set same as HTML icon mainform
* UPD: MainForm - All buttons style transparent
* UPD: MainForm left split pane - max size increased from 300 to 400
* UPD: Menu Search > Find Item Changed - for month or day < 10, a 0 is pre set to ensure complying the search condition yyyy-MM-dd
* UPD: Help > Help > PDF documentation
* FIX: Tasks search for task entry did not select all tasks meeting the search condition
* Various minor improvements

#### v0.80 (Build 20180329)
Look4How has (now) fully replaced my (good old) Delphi application (used for almost 10 years) for capturing and generating howtos and other information.
The latest version of the B4JHowTos is included in the download and loaded by default.

* NEW: Search Listview context menu: Copy titles - copy the titles found to the clipboard
* NEW: Search Listview context menu: Copy content - copy the titles found with content to the clipboard
* UPD: Search Listview - categories found are listed italic
* NEW: Tools > Find item changed - searchs for items which are changed since certain date in format YYYY-MM-dd (i.e. 2018-01-01)
* UPD: Tools > Search items changed to Find item
* NEW: Tools > Stay on Top - set the application allways on top
* NEW: Editor special functions Date Time, Date, Time
* NEW: Main Form added button for quick access tasks
* UPD: Main Form starts up faster by changing form maximized using primary screen method instead of API setmaximized
* UPD: HTML ColorPicker color search also updates RGB spinner values; Improved color conversion routines
* FIX: Menu item View HTML Source enabled linked to menu item View HTML Preview
* NEW: Tasks context menu tasklist with copy (the selected task to the clipboard) and delete (the selected task)
* NEW: Tasks option to hide completed tasks from the list
* NEW: Tasks add On Hold as a priority (in addition to High, Normal, Low)
* UPD: Tasks export HTML adjusted table size
* Various minor improvements
