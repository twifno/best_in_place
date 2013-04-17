Customized Best in place
========================

Introduction
------------

This is a customized version of [bernat's best in
place, 2.1.0](https://github.com/bernat/best_in_place). Thanks bernat for such
nice in-place-editor.

Additional function includes

* disable part of the blur function (now blur will never cause abort)
* markdown friendly for testarea (a addtional div for button bar)
* a bit more options for style
* button class for textarea (this seems to be a bug for original
  version)

And this extensions add the following options

- **:content_id**, id for textarea
- **:content_class**, class for textarea
- **:content_real_id**, for multi-pagedown-editor support
- **:content_bar_id**, id for pagedown editor button bar
- **:content_bar_class**, id for pagedown editor button class
- **:options_wrapper_class**, wrapper class to group ok and cancel
  button
- **:options_list_class**, second wrapper class to group ok and cancel
  button

The original README was moved to
[here](https://github.com/twifno/best_in_place/blob/master/README.md.bernat)

-----

Authors, License and Stuff
--------------------------

Code based on [Bernat Farrero](http://bernatfarrero.com) from [Itnig Web
Services](http://itnig.net) (it was based on the [original
project](http://github.com/janv/rest_in_place/) of Jan Varwig) and
released under [MIT
license](http://www.opensource.org/licenses/mit-license.php).
