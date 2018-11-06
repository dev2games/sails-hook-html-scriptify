# sails-hook-html-scriptify
Modified version of Sails core html-scriptify hook. Allows to expose locals without the <script> tags

Use-case: To expose locals without the script tag, you might want to do this if you will be rendering your locals in a separate view, with 'Content-Type: application/javascript' mime-type. 

The 'raw' parameter is now an option to display the scriptify data without the script tag

```
exposeLocalsToBrowser({
    raw: true
});
````
