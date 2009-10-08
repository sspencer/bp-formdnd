# Form Drag and Drop

JavaScript file to progressively enhance a file upload form if Yahoo's BrowserPlus is installed.  The [input type="file"] tag is replaced with a desktop drag+drop enabled [div] and file select button.  Mime-type filtering is possible, so the user can be forced to choose an image only.  

Note that this script is designed to only accept a single file.  If you want a multiple file uploader, there's already the [Upload Tool](http://browserplus.yahoo.com/developer/web/toolbox/upload/).

## BrowserPlus Services Used

* Built-in DragAndDrop
* Built-in FileBrowser
* Uploader

## External JavaScript Files Required

* Latest browserplus initialization script (version here may not be up-to-date): [http://bp.yahooapis.com/2.4.17/browserplus-min.js](http://bp.yahooapis.com/2.4.17/browserplus-min.js)
* bp_form_dnd.js

## Ideas for Later

* Show file preview
* Allow basic Image Editing (rotate, image filters, cropping)