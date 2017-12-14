# Views UI: Edit Basic Settings

This module provides for a user to be given simple access to edit 
components of a Views page without use of the full Views UI. Most of a 
Views page is generated from data fields that are under user control, 
but some components such as a header or footer require Views UI access. 

The module places edit tabs on Views pages, similar to those on node 
pages, and allows users with the correct permission to modify their
header, footer, title, 'no results' text, or number of items to display. 

This module provides two admin pages, one to enable admin to
define which views are editable using this module and the fields
that can be edited, the other to give the user a list with links to
the views and fields that they may edit. 

## Administration
+ Install and enable the module.
+ Define which views and fields the user may edit, at 
  Structure > Views > 'Editable basic settings'. This is also 
  available as an additional tab on the list of views.
+ Flush all caches.
+ Set the permission "edit views basic settings" for one or more
  user roles.
  
## Use

+ The editable views are listed on a new admin page at
  Content > Edit views. 
+ Each entry in this list has links to the editable fields.

Please note fields will automatically use the "override" Views setting
on save, leaving the "default" value unmodified.

## License

This project is GPL v2 software. See the LICENSE.txt file in this 
directory for the complete text.
 

## Credits

### Porting to Backdrop

Graham Oliver (github.com/Graham-72/)

### Maintainers for Drupal:

Simon Georges
Jonah Ellison


### Acknowledgement

This port to Backdrop would not, of course, be possible without all
the work done by the developers and maintainers of the Drupal module.