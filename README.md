# Centre County DSA Website

## Content Types

Defined in site/static/admin/config.yml so that the admin interface can edit them.

### Current content types

  * _index.md (Homepage)
    * title
    * subtitle
    * image (large main image)
    * intro_blurb
      * heading
      * text

Note: *title* and *date* can be accessed via *.Title* and *.Date*  while others are accessed via *.Params.<custom_var_name>*

**Note**: Variables can be created within templates

     {{$myVarName := "aString" }}
     <p>{{ $myVarName }}</p>

  
