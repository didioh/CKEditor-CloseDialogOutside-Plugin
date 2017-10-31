CKEditor-CloseDialogOutside-Plugin
==========================

CKEditor-CloseDialogOutside-Plugin
Indented to enhance the "dialog" CKEditor plugin by adding the functionality of closing (cancel) 
the dialog if click anywhere outside of the dialog box.

### Website
https://github.com/didioh/CKEditor-CloseDialogOutside-Plugin

#### License

Licensed under the terms of the MIT License. See LICENSE.txt

#### Dependecies
The "dialog" CKEditor plugin is required to use this plugin. See https://ckeditor.com/cke4/addon/dialog for details.

#### Installation

 1. Make sure you have the "dialog" plugin installed see https://ckeditor.com/cke4/addon/dialog for details.
 2. Extract the contents of the file into the "plugins" folder of CKEditor.
 3. In the CKEditor configuration file (config.js) add the following code:

````js
config.extraPlugins = 'closedialogoutside';
````

