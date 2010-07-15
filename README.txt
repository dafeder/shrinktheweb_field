/* $Id$ */

-- SUMMARY --

Snapcasa Field provides a simple means to display web page thumbnails using
the Websnapr service.

This module is just a slight modification on the websnapr field module 
v6.x-1.2, which I did not write.

For a full description of that module, visit the project page:
  http://drupal.org/project/websnapr_field

-- REQUIREMENTS --

None.


-- INSTALLATION --

* Install as usual, see http://drupal.org/node/70151 for further information.


-- CONFIGURATION --

* A prerequisite for the use of this module is a Snapcasa account. One
  account is required for each site on which it is used. Register at
  snapcasa.com and get your account key before continuing.
* Login as a site adminstrator and go to Administer >> Site configuration >>
  Snapcasa account. Enter your Snapcasa account code into the field and save it.
* From Content Management >> Content types you can now add fields you want to
  display as thumbnails using the Link data type.
* For each field, on the Display Fields panel select one of the Websnapr options
  to display the field as a thumbnail image.

-- CUSTOMIZATION --

* To change the way a Websnapr field is displayed you may override the theme function:

     Copy the entire theme_snapcasa_field_formatter() function into your template.php,
     rename it to phptemplate_snapcasa_field_formatter() or THEMENAME_snapcasa_field_formatter(),
     and customize the output according to your needs.


-- CONTACT --

Current maintainers:
* Alfred Armstrong (alfaguru) - http://drupal.org/user/112814